---
layout: post
title:  "Unit testing audio code using ASCII art waveforms"
date:   2020-06-16 0:00:00 -0600
category: draft
tags:   audio
---

It appears difficult at first glance to effectively unit test audio processing code. For most business logic, this is easy: find some inputs that should exercize the system under test, plug them into the system, and assert against the expected output. It's not quite so obvious with code that generates a buffer of audio samples.

<!-- I have a feature in my project that performs real-time fades (which include fade ins, fade outs, and pans between channels). -->

Then I ran into a very fascinating blog post at the [Jane Street Tech Blog](https://blog.janestreet.com/), called _[Using ASCII Waveforms][jane-st-ascii-waveforms]_.

[jane-st-ascii-waveforms]:  https://blog.janestreet.com/using-ascii-waveforms-to-test-hardware-designs/
[NAudio]:   
