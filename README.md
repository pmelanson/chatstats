# ChatStats

ChatsStats is a data visualizer for a Facebook Messenger conversation. Try it out with your group chats or your chat with a significant other. You don't need to be an experienced programmer to use it!

## Example

You can see the results of Chat Stats here: TODO

## How To

Note: Not tested on Windows.

### Pre-requisites

You will need the following installed:

* Git
* Python3
* Pip3

### Step One: Getting Your Facebook Data

To get your entire chat history:

1. Go to [https://www.facebook.com/settings](https://www.facebook.com/settings). At the bottom of the settings list is an option "Download a copy of your Facebook data." Select it and follow the instructions.
2. Facebook takes a few minutes to generate a download link for you. You can do **Step Two** while waiting for the link.
3. Once you receive an email from Facebook with a download link, save the file to your computer and unzip it. Note that this is very sensitive information, so be careful storing it.

### Step Two: Set Up ChatStats

1. Clone or fork this repository:
```
git clone https://github.com/baieric/chatstats.git
```
2. Install the dependencies:
```
pip3 install -r requirements.txt
```

### Step Three: Generate Graphs!

1. Go to your Facebook data folder, and open `index.htm` in your browser.
2. Go to the "Messages" page on the left navbar. Find the conversation you want to use and go to its page.
3. Copy the page's URL from your browser, and run the following command:
```
python3 chatstats.py <conversation_url>
```
This creates a directory in `chatstats/generated/` with all the graphs saved as images, as well as some underlying data files used to create those graphs.

## Advanced Usage

TODO