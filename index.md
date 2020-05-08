# Cocoaphony's guide to giving a Virtual Talk

With all these virtual conferences going on, a lot of folks are giving their first virtual talks. I've been giving talks at conferences for years, but virtual adds some interesting challenges. This page captures a few quickly jotted-down lessons I've learned so far in how to make these work the best they can. For more about me, see the [Cocoaphony blog](https://robnapier.net) or [@cocoaphony](http://twitter.com/cocoaphony/status/1258791650501033985).

## My setup

My setup may not be the same as your, so not everything here may work for you. Mostly I'm going to document how I do it,
and you can take from it what works.

Quick summary: 

I have a dedicated office with a stand-up desk and a large monitor, along with my MacBookPro which I use as a second monitor.
Both are on arms to hold them up to eye level. I use Keynote for my talks, and will focus on how to set that up. I mostly
work with Zoom, so I'll discuss that too.

## Setting up your desktop

I really like having two screens so that I can share one, full screen. You should share the smallest of your screens (probably
the laptop). However large it is will be large enough for sharing, and smaller screens use less bandwidth. Sharing a full
screen makes it easy to know what you're sharing and what you're not.

Clear everything off your second screen. It should just have a background and the menu bar. If you're a packrat and keep
tons of things all over your desktop, make a folder and stick everything in that folder for while you're presenting. That
way the desktop is not distracting when you close Keynote or switch to Xcode, etc.

## Setting up Keynote

Keynote works well in a 2-monitor configuration. You can present on the small screen (that you're sharing) and view your notes
on the large screen. Cmd-Opt-P will start presenting. If the windows are on the wrong screen, press X to switch them.

Your camera should be on the screen with your notes. If you use speaker notes, I suggest reorganizing the presenter window
to puth the notes at the top. Here's my layout.

![Presenter screen layout example](https://github.com/rnapier/virtual-conf-howto/raw/master/Presenter%20Screen%20Layout.png)

You can edit your layout by clicking the edit button:

![Presenter Layout Editor Button](https://github.com/rnapier/virtual-conf-howto/raw/master/Presenter%20Layout%20Editor.png)

It'll appear in the upper-right when you mouse over the presenter screen.

Some key points about this layout:

* I use presenter notes extensively. Note that they're placed at the top. This allows me to look at the camera while still seeing the notes.
* I've limited the width of the notes so I don't have to turn my head while I read them. The notes are also slightly off-center to the right. Since there is generally more text on the left of a page than the right, and once I start a sentence, I usually remember how to finish it without reading, this keeps my eyes more centered.
* I've increased the font size, and made the window large enough to hold my longest text. In some rare cases where I have a very large amount of text, I sometimes duplicate a slide with no transition, just so the rest of the text is easily read without looking down the page.
* If you generally speak without notes, you probably want to put the current slide at the top-center for the same reasons.

## Checking video

To see how your setup is working, I highly recommend Photo Booth (built-in, in /Applications). It has a simple video recorder, and is a very easy way to see what you're going to look like on video. Start it, start your presentation, and give the first few seconds of your talk.

Check what's behind you in the frame. Is there a lamp that looks like it's growing out of your head? Are your company's secret plans on the whiteboard behind you? Is your background filled with a clutter? Is there a lot of glare that makes you squint. This is the time to fix all that.

You want some light shining on your face if possible. People came to see you, not dramatic shadows. And low-light makes the camera have to turn up the gain, which can make things grainy. You may want to put a lamp behind your screen if possible, or rearrange a bit so that you face a window. Remember what time of day your talk will be. Natural lighting might change dramatically.

## Turning off Distractions

First, this button in the upper-right corner is your friend.

![Notifications Button](https://github.com/rnapier/virtual-conf-howto/raw/master/Notifications%20Button.png)

Option-click it so it's dimmed. That puts you in do-not disturb. It's also available as a toggle by left-clicking the button and going to the Notifications pane.

![Do Not Distrub setting](https://github.com/rnapier/virtual-conf-howto/raw/master/Do%20Not%20Disturb.png)

That doesn't fix everything, but it's a start. 

When I speak at conferences, I generally turn off wi-fi entirely, but that's not possible in a virtual conference. But do turn off everything you can. Quit all programs other than Keynote (and Xcode if you need it). You may need to run some number of programs for the conference, including possibly a web browser, but if you can quit it, quit it.

Also, remember to silence your phone and your watch. (I always forget about my watch, and it chirps at me at weird times....)

Don't forget to warn your two-legged housemates, and plan for your four-legged ones. Delightful as all the kids and cats bursting into a Zoom call can be, it's distracting. If your family is home with you, let them know exactly when you're going to be speaking. It's not just a kindness for the audience; it's also to let your family know when you're *not* speaking and when it's fine to go about their lives. (I've forgotten this before, and my family spent hours being unnecessarily cautious about noise.)

## Setting up Zoom

First, if the conference is using Zoom, make sure you've set it up and tested it before-hand. [While I don't like the choices they've made about their desktop app](https://www.tomsguide.com/news/zoom-security-privacy-woes), if you plan to use the web app instead to present, make sure you've tested with it first.

If you have multiple headsets laying around, I recommend testing the audio with everything you have. There's a "Test Mic" option in the settings.

![Zoom Settings](https://github.com/rnapier/virtual-conf-howto/raw/master/Zoom%20Settings.png)

Switching from my preferred wireless headset to a USB wired headset dramatically improved audio quality. My wireless headset is more comfortable, and the audio is fine, but my USB headset is just much better. I recommend testing every microphone you can put your hands on with Zoom's "Test Mic" feature. Zoom applies various audio processing, and you want to know what's going to sound best with Zoom. (Zoom has an option on the Advanced pane to allow turning off all audio processing, and if you have a more advanced setup, you might want to test with that.)

Use a headset or a dedicated, external microphone. Do not use your computer's built-in mic to give a presentation. Zoom has various filters to try to make it not horrible, but it's going to sound horrible. Even the most basic headset is going to be much better.

## Communication

Things go wrong. That's the nature of conferences. But in a virtual conference, you don't have all the helpful staff right there to help you get out of it. So you need to plan in advance.

What are you going to do if your home network goes out ten minutes before your talk? You want a way to contact the conference staff that is out-of-band. If it's domestic, share phone numbers. If it's international, make sure you have some backup messaging system (Slack, etc.) where you can reach each other that works from your phone over cellular. The goal isn't to make sure that the talk can go forward; it's to allow the staff to decide when it's worth waiting a few minutes vs. canceling the talk and moving to something else.
