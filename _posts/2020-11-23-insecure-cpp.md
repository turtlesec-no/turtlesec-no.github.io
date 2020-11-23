---
layout: post
title:  "(In)Security in C++"
date:   2020-11-23
description: Secure Coding Practices in C++
excerpt: Training aimed at providing a foundation for C++ programmers in security for native applications.
image: "/images/aker_brygge.1000.jpg"
---

## (In)Security in C++

### Secure Coding Practices in C++

The training will provide its students with:

- vocabulary to understand reported vulnerabilities
- knowledge on how to receive vulnerability reports professionally
- knowledge on how to use tools to find and fix vulnerabilities in their own code
- knowledge on how to design a more secure product
- knowledge on how to design a CI/CD pipeline that will improve the security of their own codebase

### Practical information

The training can be done both remotely and on-site. When done remotely this setup is used:

- **Audio/Video** - [Zoom][1] + [Zoom Breakout Rooms][2]: Can be attended from a browser or a Zoom client
- **Chat** - [Slack][3]: Will be setup a week in advance to facilitate resolving of any technical issue
- **Exercises** - Cloud VMs and a [Cyber Dojo][4] cloud instance: guarantees same environment

This training is explicitly targeted at C++ developers, though C developers will also benefit.

### Goals of the training

- Demystify exploitation, show that exploitation is a mindset, not a set of techniques
- Demonstrate the motivation for mitigations in the platforms, languages and tools
- Show that C++ and C are not easy to reason about
- Teach the students to recognize constructs that have a higher risk of having vulnerabilities
- Teach the students to which tools can be used to find bugs before others find them
- Teach the students about tools they can use locally while coding
- Teach the students about tools they can integrate in their CI/CD pipeline
- Help them think about how security fits into the team context
- Help them view their application in a new ways

## Four day training

### Day 1 - Introduction, Fuzzing and Numbers

- Introduction: Training
- Introduction: Specs
- Introduction: Tooling
- Introduction: UB and Compiler Optimizations
- Exploit: Heartbleed
- Theory: Fuzzing (on Linux)
- Exploitable: Numbers

### Day 2 - Stack Buffer Overflow, Shellcode, Reverse Engineering and Sandboxing on Linux

- Mitigations: Stack Buffer Overflow
- Exploit: Shellcode 1 (on Linux)
- Exploit: Shellcode 2 (on Linux)
- Theory: Reverse Engineering
- Theory: Linux Sandboxing (Examples from Chromium)

### Day 3 - Return Oriented Programming, Format String Vulnerabilities, Good Practices and Security Culture

- Exploit: Return Oriented Programming (ROP)
- Exploit: Format Strings (on Linux)
- Practice: Avoid the Pitfalls
- Practice: Functionality
- Practice: Resource Management
- Exploitable: Modern C++
- Discussion: Security Culture
- Practice: Make It Fixable

### Day 4 - Memory, Heap Exploitation and Conclusion

- Theory: Memory Managers (on Linux)
- Theory: Heap Exploitation
- Exploitable: Memory 1
- Exploitable: Memory 2
- Exploit: Eternal Exploits
- Mitigations: Memory
- Practice: Prefer C++ to C
- Practice: I'd Really Rather You Didn't
- Practice: 6 Hacks for Dev[Sec]Ops
- Discussion: Conclusion

[1]: https://zoom.us/
[2]: https://youtu.be/jbPpdyn16sY
[3]: https://slack.com/intl/en-no/
[4]: https://cyber-dojo.org/
