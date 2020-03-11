## How to Run 

Make sure to have [Python](https://www.python.org/) installed. Download the entire package onto your computer and `cd` into the `Facebook` folder and run `python FacebookScroll.py`. For the first prompt, copy & paste the `See Older Messages` URL from https://mobile.facebook.com/home.php?soft=messages of any messanger conversation. The second prompt will ask for the amount of months you would want to travel back.

Inspired by [this Quora Post](https://www.quora.com/How-can-I-scroll-up-to-the-beginning-of-a-long-Facebook-chat-Is-there-a-way-to-do-this-without-manually-scrolling-all-the-way-up)

### To Find Your First Facebook Messages With Someone

1. Go to mobile.facebook.com/messages and select the person (or group).

2. Right click on "See Older Messages..." and copy the link.

3. The URL you copied will include something like this: &last_message_timestamp=1234567890123 — The number in this URL is telling Facebook what time and date to begin looking for messages. This timestamp is a Unix Timestamp and is measured in milliseconds (not seconds). So if you decrease this number by 60,000, it will show you messages from a minute earlier.

Decrease the timestamp until you find your first messages with someone. If you know your first messages are from many months ago, you will have to decrease the number significantly. (For reference, 1 billion milliseconds is about 11.6 days.)

Alternatively, it may be easier to go directly to a specific timestamp if you know a rough date or month that you begin chatting with someone. To find a specific timestamp, visit currentmillis.com and type in a date. It will generate a timestamp for you that you can enter into the URL.

Note: Originally, the start parameter in the URL would allow you to jump back a specified number of messages (start=123 for example), but this parameter no longer works.
