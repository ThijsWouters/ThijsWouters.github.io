---
layout: post
title: "A Wet Basement"
date: 2015-02-07T11:02:20+01:00
---
Our basement is wet, so we rented a dehumidifier. It generates a lot of water,
there is a bucket under it. But I did not want to check it all the time. So I 
made something that did the checking for me.

I took my [Raspberry Pi][] and I made a simple circuit. 

The circuit comes down to:

1. Connect wire to ground,
2. connect wire to pin,
3. done.

Now to the programme that is running. It needs to send an email when the two
wires are connected. You can download it [here][code].

You will need an account on [mailgun.com][] to receive emails.

[Raspberry Pi]: http://www.raspberrypi.org/
[code]: https://github.com/ThijsWouters/wet-basement
[mailgun.com]: http://mailgun.com

