---
layout: post
title:  "(In)Secure C++"
date:   2020-11-23
description: Understanding Exploitation to Find and Fix Vulnerabilities
excerpt: 4-day workshop on finding, exploiting and fixing vulnerabilities in C++ and C code.
image: "/images/aker_brygge"
image_alt: "View of Akerbrygge"
---

## (In)Secure C++

The 4-day (In)Secure C++ training is designed to provide you with the essential knowledge and tools
to effectively find and fix vulnerabilities in your own C++ and C code.

For private trainings, online or on-site, please get in touch for an offer.

<h2 id="public_training">Upcoming public trainings</h2>

<h3>USA (PST)</h3>

<h4>2023</h4>

<ul>
    <li>Oct 31st - Nov 3rd (8am - 16pm PST) - <b>Online</b> - <a href="../blog/insecure-cpp/">(In)Secure C++, 4-day</a> <b>[<a href="mailto:patricia@turtlesec.no?subject=Book (In)Secure C%2B%2B (Oct 31st - Nov 3rd)">Book 2000$</a>]</b></li>
</ul>

### Understanding Exploitation to Find and Fix Vulnerabilities

The (In)Secure C++ training is designed to provide you with the essential knowledge and tools to
effectively find and fix vulnerabilities in your own C++ and C code. To do this, we __*demystify
exploitation*__ by showcasing that it is a mindset, not just a set of techniques.

You'll gain insights into the __*motivations behind mitigations*__ in platforms, languages,
and tools by understanding the vulnerabilities they are trying to protect against. You'll get a
deeper understanding of why C++ and C are not easy to reason about. With our training, you'll
learn how to design a more secure product, how to establish a robust CI/CD pipeline that
improves the security of your codebase and __*how to find and fix vulnerabilities in your own 
codebase before others do*__. And if others find them first, how to understand their vulnerability 
reports and how to receive and respond to them in a professional manner.

Throughout the four-day training, you'll dive deep into various topics, including fuzzing,
sanitizers, buffer overflows, remote code execution, custom shellcode, reverse engineering,
sandboxing as a security boundary, return-oriented programming (ROP), format string 
vulnerabilities, heap exploitation, good coding practices and establishing a security culture. Each
day is carefully crafted to provide you with __*practical knowledge, real-world examples, and 
hands-on exercises.*__

This training is explicitly targeted at C++ developers, though C developers will also benefit.

### Practical information

The training can be done both remotely and on-site.

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
* __Memory Managers and Heap Exploitation__: How to understand and manipulate the memory layout and
  exploit heap-based vulnerabilities. Here we will look at things like Heap Spraying, Heap Feng 
  Shui, Use After Free, Heap Buffer Overflow and different techniques for getting code execution 
  on the heap.
* __Reverse Engineering and Sandboxing__: How to analyze binary code and use sandboxing techniques
  to isolate untrusted code.
* __Secure Coding Practices__: How to write more secure C++ code and to avoid common pitfalls.

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

- Vulnerability: Stack Buffer Overflow
- Exploitation: Writing and Testing Custom Shellcode
- Reverse Engineering
- Sandboxing on Linux (Examples from Chromium)

### Day 3 - Mitigation Evasion and Secure Coding Practices

- Exploitation: Return Oriented Programming (ROP)
- Exploitation: Format String Exploitation
- Secure Coding Practices, Mitigations and Tooling - Part 1

### Day 4 - Heap Exploitation

- Vulnerability: Memory Managers and Heap Allocation
- Exploitation: Heap Exploitation
- Case Study: Eternal Exploits
- Secure Coding Practices, Mitigations and Tooling - Part 2
- Practice: Vulnerability Management
- Summary and Conclusion

[1]: https://meet.google.com/
[2]: https://slack.com/intl/en-no/
[3]: https://cyber-dojo.org/
