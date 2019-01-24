# Mass-Delete-Discord-Messages

You can use this through either Discord's desktop app or through the browser.

Instructions are also found as comments in the code.

For ``lastmsg``, go to the message you want the code to start at and 'Copy ID'

For ``youruser``, this is your Discord name. **Do not include the # symbol or the four numbers after it.**

For ``authToken``:
1. On your browser go to any discord conversation/server. Press ``F12``.
2. On the desktop app, the dev tool key is ``CTRL`` + ``SHIFT`` + ``i``.
3. Delete a message. Under the 'Network' tab, should be the last entry but look for the shortest entry
4. It should be an entry of JUST numbers
5. Scroll down to 'Request Headers' on the right me
6. Look for 'authorization'. Thats your authToken. **DO. NOT. SHARE. THIS. KEY.** At all. With anyone.

For channel, this is the ~18 digit number in the URL, on the browser version of discord. You will need to access
  the conversation through a browser to get this number.
  
-------------------
  
The code only tracks how many messages it deletes of yours. You *can* add a variable like i to keep
  track of how many messages the other person has sent. This is not necessary, and WILL make
  your console.log spam. Be careful.
    
Feel free to PM me if you have any questions about Altoids1 code, or my updated version.

**Do not repost this code, or Altoids1, without credit. Don't be a dick.**

Altoid1's Code:
https://gist.github.com/CarletonStuberg/0c838a6248772c6fea1339ddad503cce#gistcomment-2774603
