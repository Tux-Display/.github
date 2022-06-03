## Hi there 👋

We created Tux Display as an open and privacy focused smart dipslay to rival the Big Tech companies that can do whatever they want with your data. 
This project was created by four high school students in the Netherlands and is currently not being actively supported so some files might not work.
We based our smart display off of [MycroftAI](https://mycroft.ai/) furthermore we added our own skills, like an automatic skills cloner and a nice looking homescreen.

## Requirements

* **Raspberry Pi 3, 3B+, or 4**
  <br>_Older Raspberry Pi versions do not have sufficient processing power,
  and if they work they will be very slow_
* **Speaker**
  <br>Any analog speaker, or an HDMI monitor with speaker
* **Microphone**
  <br>A [list of Community tested hardware](https://mycroft-ai.gitbook.io/docs/using-mycroft-ai/get-mycroft/picroft#tested-hardware) is available in our documentation.
* **2.5 Amp or better power supply**
  <br>Don't skimp on this!  It might appear to work, but you'll have weird
  issues with a cheapo supply.
* **MicroSD Card**
  <br>8 GB or larger
* HDMI Monitor and keyboard, only required during setup
* Raspberry Pi DSI Touchscreen


## Installation (sort of)

While making our Smart Display we didn't necessarily think about the end user experience of creating the device itself, so it isnt really that pollised, but it should be possible.
This organization consists of two Mycroft AI skills, one used to git clone our own repos [Cloner](https://github.com/Tux-Display/Cloner), just for ease of use and our [Clock-Display](https://github.com/Tux-Display/Clock-Display) skill which shows our representation of Mycroft and on swipe show the current time, the HTML/CSS/JS files required for this the work are stored in the [Homescreen](https://github.com/Tux-Display/Homescreen) repo. 
The skills can be installed by git cloning the repos into ~/mycroft-core/skills

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
