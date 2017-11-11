# Misc
Random commands, which aren't really related to any other cogs

* `ping`
  >Pings the bot's websocket, timing how long it took.  
  Also good for like, finding out if the bot is even on and ... well, testing that your own discord works.

* `shrug`
  >Chooses a random shrug face from a list, and posts it for you

* `lenny`
  >Chooses a random lenny face from a list, and posts it for you

* `rip <name or message>`
  >Displays a nice little tombstone with the name or message engraved in it.  
  Protip: don't make the name or message longer than 18 characters. Or else ...

* `choose <choices...>`
  >Chooses one choice from the list of choices.  
  The list should be split with spaces. To have multiple word choices, enclose them in double qutoes.  
  E.g. `choose "play games" "read a book"`

* `quote <message id> [channel id] [guild id]`
  >Quotes a message.  
  A message id is required. This can be gotten by enabling developer mode,  
  and right clicking (or long tapping) on the message.  
  By default, the bot searches for the message in the current channel. To search elsewhere,  
  provide a channel id.  
  A guild id is also optional. If provided, this searches in that other guild,  
  provided that the bot is actually *in* that guild

* `spoken [number=50] [user] [channel]`
  >Tells you how many times member has spoken in a channel in the last *number* messages.  
  If no user is provided, the author is used instead. If no channel is provided, the current channel is used.