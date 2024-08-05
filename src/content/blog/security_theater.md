---
author: tie304 
pubDatetime: 2024-03-18T9:21:00
modDatetime: 2024-03-18T08:14:47
title: Security Theater 
slug: "security-theater" 
featured: true
draft: false
tags:
  - philosophy
  - security
description:
 
  They who can give up essential liberty to obtain a little temporary safety, deserve neither liberty nor safety. - Benjamin Franklin
---
It was a dark day when I realized I had about 10 minutes left of power in my laptop. You see, it was plugged in but not charging, and I didn't realize it. I had been working on an important project very focused. I spent the next 5 minutes trying to determine why it would not charge. But you see, this is a gaming laptop with a high-end graphics card and 4k display. I'm losing 1% per minute. I failed to fix the problem and, in a panic, I ran:

```bash
tar -czvf home.tar.gz /home
```
In an attempt to back up my files.

"NO, DON'T SAVE THE NODE MODULES!" I screamed in my head.

My laptop died. I was not fast enough.

I brought my laptop the next day to a repair center, where they believed it was the charger. It was not. (They also tried to scam me. Be careful doing business in Peru.) I took my laptop back. It's now an expensive paperweight. Luckily, I reached out to System 76 support, and they will repair it under my warranty. Long story short, I live outside the US and will need to wait until I go back to the states.

Luckily, I have my old Dell XPS 17. I fired it up, installed Ubuntu, and we're good to go. I go to access my GitHub and it requires two-factor authentication. I don't have GitHub added to any authenticator app; okay, just use the recovery codes (which I have been doing to log in normally; the sessions on GitHub last a very long time) but, uh-oh, my codes are on my bricked laptop. It turns out you can just submit a support ticket to disable OAuth, but it can take up to a few days. I had to submit my GitHub token... which was on my other bricked laptop, but luckily, I had another totally inadvisable way to access it. Two days later, I got access, and I have new recovery codes.
## Why force me to be secure? Why force me into oauth? 
I would love a simple username and password login. It's my choice. All these extra layers of security I find unnecessary and intrusive. All applications should offer you options on how secure you'd like to be. Perhaps even setting defaults to the maximum, but users should have the option to disable them to the very minimal authentication system.

## My Banks now blocks any IP outside the US 

Why? Does it make the security people feel better about themselves? I just use a VPN, but perhaps there are other less technical users who travel outside the country and want to access their bank online. What if they start blocking VPNs like HBO Max? Now I'll have to route my traffic through one of my friends' home networks or use TOR or something. But what does this accomplish? Does it stop the baddies? No, I doubt this.

## Freedom is the power to make your own decisions. 
Freedom is username and password auth. 
Freedom is the ability to decide to give up some safety for more liberty. More security means less freedom, in all dimensions of life.



That is all.
