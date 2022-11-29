---
layout: post
title:  "(In)Secure C++ : Sec Edition"
date:   2022-11-29
description: Native Vulnerabilities
excerpt: Training aimed at providing an introduction to vulnerabilities for native applications.
image: "/images/oslo-g0d4acfbda_640"
image_alt: "Picture of a woman playing the violin projected on to an outcrop on the opera buildings roof"
---

## (In)Secure C++ : Sec Edition

Training aimed at providing an introduction to finding and exploiting vulnerabilities in C and C++ applications.

### Secure Coding Practices in C++

The training will provide its students with:

- knowledge on how to use tools to find vulnerabilities in native applications
- give a hands-on experience in some exploitation techniques

### Practical information

The training can be done both remotely and on-site.

- **Chat** - Slack: Will be setup a week in advance to facilitate resolving of any technical issue
- **Exercises** - Cloud VMs and a [Cyber Dojo][1] cloud instance: guarantees same environment

This training is explicitly targeted at security professionals with some programming experience in C or C++.

### Goals of the training

- Demystify exploitation, show that exploitation is a mindset, not a set of techniques
- Demonstrate the motivation for mitigations in the platforms, languages and tools
- Show that C++ and C are not easy to reason about
- Teach the students to recognize constructs that have a higher risk of having vulnerabilities
- Teach the students which tools can be used to find bugs

## Two-day training

### Day 1 - Finding Vulnerabilities Using Fuzzing

- Meta: Training
- Theory: Introduction and Specs
- Mitigations: Tooling
- Exploitable: UB and Compiler Optimizations
- Theory: Address Sanitizer
- Exploit: Heartbleed
- Theory: Fuzzing (AFL and libFuzzer)
- Theory: Debugging in gdb

### Day 2 - Exploitation and Writing Shellcode

- Exploit: Format Strings Vulnerabilities
- Exploit: Stack Buffer Overflow
- Exploit: Shellcode 1
- Exploit: Shellcode 2
- Exploit: Return Oriented Programming (ROP)
- Discussion: Conclusion

[1]: https://cyber-dojo.org/
