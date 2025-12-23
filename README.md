# Breadboard Diaries

I really enjoy breadboarding. Not just putting stuff together with wires and measuring results. I see my breadboard as a canvas, a blank slate upon which I can bring my ideas to life. I know how long each of my wire sets are, so I know how to position stuff to look really neat. It's a fun exercise that keeps me destressed. 

I've worked on a couple projects so far, some being part of courses where I get to choose my topic. It's hard to do much with coursework taking up time, but I generally try to stay in touch with breadboards through 1 project per semester. I like analog. 

So here's a small summary of the projects in my repo. I am more proud of the neatness than anything, lol.

> [!NOTE]
> Not all my projects are available. Projects like the audio equalizer are a part of coursework related to ECE 20007, a course for which I was a Teaching Assistant. So I'm not keeping any of that available publicly.

## Table of Contents

- [Audio Equalizer](#audio-equalizer)
- [Function Generator](#function-generator)
- [Heartbeat Monitor](#heartbeat-monitor)
- [My Op-Amp](#my-opamp)
- [AM Radio](#am-radio)

<a id="audio-equalizer"></a>
## 🔊 Audio Equalizer

[Project Details](./01-audio-equalizer/README.md)

This is a simple project made in 2024 to seperate an AUX cable signal into 3 groups, seperately amplify / reduce, and a final stage for recombinatuon and power amplifying. Can't show details on this one since I'm a TA for this class. 

<a id="function-generator"></a>
## 🌊 Function Generator

[Project Details](./02-function-generator/README.md)

A function generator from two LMC 555 timers to produce modifiable waveforms. Cool project, probably my first time peering through datasheets to make circuits and come up with some creative solutions to some unexpected problems.

<a id="heartbeat-monitor"></a>
## 💖 Heartbeat Monitor

[Heartbeat Monitor](./03-heartbeat-monitor/README.md)

A photoresistor based analog heartbeat detection circuit. Pretty sensitive, needed lots of tuning. Closely tied to ECE 20007 (it's the course after, ECE 20008) so keeping this private.

<a id="my-opamp"></a>
## 🍪 Op-Amp

[Op-Amp](./04-my-opamp/README.md)

Made a 3 stage operational amplifier using ALD 1106-8 MOSFET ICs. Uses a differential amplifier, and then CS and CD amplifiers. Verified it by making an opamp circuit and seeing amplification.

<a id="am-radio"></a>
## 📻 AM Radio

[Radio](./05-am-radio/README.md)

Made an AM radio transmitter and receiver. Capable of transmitting 2 seperate AUX cable signals at 2 frequencies. The receiver has a 555 timer based demodulator to inject the signal down to an intermediate frequency, and then goes through filtering and envelope detection to reconstruct the signal. One of my favorites so far, just because I liked working with Fourier math.

---

More coming soon :)

---

Creator: Surya Turaga. 
Maintained with ❤️.