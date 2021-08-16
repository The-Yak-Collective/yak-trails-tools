Stubborn
========
2021-07-19
----------
### Build Name
Stubborn
### What did you do last week?
Going down the rabbit hole of Raspberry Pi and related ecosystem to explore how it can support the Rover. 
### What do you plan to do next week?
The new 3D printer arrived today, so I'll probably be doing a lot of learning to support improved mechanical systems. I'm still trying to get the ground station radio working on the Pi.
### Any blockers?
Too much to learn, not enough time to satisfy my curiosity.
### What's one interesting thing from last week
While some of the interfaces for doing embedded systems programming on a raspberry pi and an Arduino are similar having a linux kernel intermediary leads to some surprises. For example, handling interrupts is not as support as I would have guessed. I think they require kernel level code to work with. All the work that has gone into the ecosystem though means you can do a surprising amount of pretty low-level stuff in user space, and in python, which is quite impressive.


2021-07-26
----------
### Build Name
Stubborn
### What did you do last week?
Setup and started working with a 3D printer. Iterated on my Rover's rear board mount for a tighter build. This is going to be a great distraction.
### What do you plan to do next week?
Traveling this week so no direct rover work. Hoping to find some time to work on some pure software bits or maybe do some design on parts to print.
### Any blockers?
nope
### What's one interesting thing from last week
3D printers are immensely satisfying. Highly recommend.


2021-08-02
----------
### Build Name
Stubborn
### What did you do last week?
On the road with no hardware access, but I spent some time rebuilding my ground station to be raspberry pi / linux-based by breaking up the components into more composable (and replaceable) parts. For example, I have a dedicated radio process where any other program can open up the named socket /var/stubborn/radio and read and write bytes to it.

I don't quite have an end-to-end system put back together yet but it's getting pretty close. Hopefully it's working before vacation is over.
### What do you plan to do next week?
Get the new ground station wired up end-to-end from an interface through the radio.
### Any blockers?
nope
### What's one interesting thing from last week
I've been remarkable successful using VSCode, SSH and Tailscale (VPN) to develop remotely on the raspberry pi which I left at home. I only had to have my lab assistant go and reboot it remotely once so far.


2021-08-10
----------
### Build Name
Stubborn
### What did you do last week?
Not a lot. Sun and sand got in the way.
### What do you plan to do next week?
This week I should get some end-to-end connection for my new ground station. Now that I'm home I can verify the radio really works with the rover as opposed to just simulating it.
### Any blockers?
Nope
### What's one interesting thing from last week
I would be very unproductive if I lived at the beach.

