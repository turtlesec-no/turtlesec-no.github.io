---
layout: post
title:  "(In)Secure C++ : Sec Edition"
date:   2022-11-29
description: Understanding Exploitation and Finding Vulnerabilities
excerpt: 2-day workshop on finding and exploiting vulnerabilities in C++ and C code.
image: "/images/oslo-g0d4acfbda_640"
image_alt: "Picture of a woman playing the violin projected on to an outcrop on the opera buildings roof"
---

## (In)Secure C++ : Sec Edition

This 2-day training is a shorter version of the 4-day (In)Secure C++ training. To make that 
possible this training focuses specifically on finding vulnerabilities and how they can be 
exploited.

For private trainings, online or on-site, please get in touch for an offer.

### Understanding Exploitation and Finding Vulnerabilities

Gain essential knowledge, and hands-on experience, in effective vulnerability detection tools and 
techniques, and how these vulnerabilities are wielded in exploitation of C++ and C applications. 
By deepening your understanding of exploitation, the motivations driving mitigations, and the 
identification of high-risk constructs, you will be able to design software that better meets 
your security needs.

This training is explicitly targeted at C++ developers, though C developers will also benefit.

### Practical information

The training can be done both remotely and on-site. When done remotely this setup is used:

- **Audio/Video** - [Google Meet][1] + Breakout Rooms (for online trainings)
- **Chat** - [Slack][2]: Will be set up a week in advance to facilitate the resolution of any
  technical issues, and is used during the training to pace exercises and facilitate discussions.
- **Exercises** - Individual Ubuntu 22.04 cloud VMs and a [Cyber Dojo][3] cloud instance
  guarantees the same environment for all students.

### Some of the topics covered

* __Fuzzing and Sanitizers__: How to use tools like Address Sanitizer and fuzzers like AFL/libFuzzer
  to find and fix security vulnerabilities. Here you will use fuzzing to find the Heartbleed
  vulnerability in OpenSSL. You will also be tasked with fixing Heartbleed, and then reviewing 
  the fix that was shipped at the time, to get a realistic impression of how difficult it can be 
  to analyze and fix vulnerabilities in real life scenarios.
* __Exploiting Buffer Overflows with Custom Exploit Shellcode__: How to exploit buffer overflows and
  execute arbitrary code, and the mitigations that can help prevent it from happening. Here you will
  exploit a program with your own custom shellcode.
* __Return Oriented Programming (ROP) and Format Strings__: How to bypass stack protection
  mechanisms using ROP and generated ROP chains. And we'll use format string vulnerabilities as an
  example of a completely different way of exploiting applications.

## Training Schedule

### Day 1 - Finding Vulnerabilities Using Fuzzing

- Introduction and Setup
- Introduction to exploitation, vulnerabilities and specifications
- Mitigations and Tooling: Static and Dynamic Analysis
- Undefined Behaviour and Compiler Optimizations
- Address Sanitizer
- Case Study: Heartbleed
- Fuzzing: AFL and libFuzzer
- Debugging Shellcode in GDB

### Day 2 - Exploitation and Writing Shellcode

- Exploitation: Format String Exploitation
- Vulnerability: Stack Buffer Overflow
- Exploitation: Writing and Testing Custom Shellcode
- Exploitation: Return Oriented Programming (ROP)
- Summary and Conclusion

[1]: https://meet.google.com/
[2]: https://slack.com/intl/en-no/
[3]: https://cyber-dojo.org/
