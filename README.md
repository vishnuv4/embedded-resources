# Embedded Resources

The aim of this repository is to collect all the cool stuff I've come across on the internet related to embedded systems. I like reading and I like embedded systems, so it makes sense that I would maintain a repository of (mostly) reading material related to embedded systems. There are also some videos that I've found useful.

## Roadmaps/Compilations:

- [m3y54m's Embedded Engineering Roadmap](https://github.com/m3y54m/Embedded-Engineering-Roadmap?tab=readme-ov-file)
- [Embedded Systems Roadmaps - Nathan Jones](https://www.embeddedrelated.com/showarticle/1589.php)
- [So You Want To Be An Embedded Systems Developer - Steve Branam](https://www.embeddedrelated.com/showarticle/1324.php)
- [Skills For Embedded Systems Software Developers - Steve Branam](https://www.embeddedrelated.com/showarticle/1460.php)
- [A skills tree by Elecia White](https://static1.squarespace.com/static/50834ba9c4aa1a31c651078b/t/65282cd79af38b46be8da4db/1697131736219/20231012_Embedded_Systems_Skill_Tree.pdf)

## Forums and Blogs

Forums are a great resource to get information from people in the industry. The information may be a bit disorganized, but the tradeoff is that it's the most "up to date" information in the industry compared to textbooks, courses and things that people have had time to organize.

- [Embedded Artistry](https://embeddedartistry.com/)
- [Embedded Related](https://www.embeddedrelated.com/)
- [Interrupt by Memfault](https://interrupt.memfault.com/blog/)
- [Embedded.fm](https://embedded.fm/)
- [Beningo Group blog](https://www.beningo.com/blog/)
- [Barr Group's How-To guides](https://barrgroup.com/embedded-systems/how-to/articles)

## Books

- [Making Embedded Systems: Design Patterns for Great Software: Elecia White](https://www.amazon.com/Making-Embedded-Systems-Patterns-Software/dp/1098151542/ref=sr_1_1?crid=1X9EMQ4QM4JYE&dib=eyJ2IjoiMSJ9.cJD-fub3W8rCFgU7dV_WfXK48c5NoL0RlZEdZFcrDIt4jIMxp_oUV4kWxFk9AYdofKgLWLXedgzpTPNJXbFbtWXcRyfoPx4CB6K_P04cJzF4rikoV4-lZuT9DzEJbva6uj9rbIb6GGYAVDlF_MysHxbOktGWPMdc6I64tGwatUfrt7CVdr59nlbVS3iAcsrzKrdsB0NexrC5GJhVhCgUGqGuFZBd7bD8Ww97zWvARXI.QjoCvdAikEwp15tOhMNiISnbi5lxegF5S-DOCmwwCzY&dib_tag=se&keywords=making+embedded+systems&qid=1729913168&sprefix=making+embed%2Caps%2C100&sr=8-1)
    - A classic. At least the first 4 chapters are a must-read.
- [Debugging: David J. Agans](https://www.amazon.com/Debugging-Indispensable-Software-Hardware-Problems/dp/0814474578)
    - One of my all time top recommendations. Gives you some principles to follow while debugging embedded systems.
- [Better Embedded System Software: Philip Koopman](https://www.amazon.com/Better-Embedded-System-Software-Koopman/dp/B08TZ9LYXC)
    - A comprehensive guide to writing good embedded software.
- [Embedded C Coding Standard: Barr Group](https://barrgroup.com/sites/default/files/barr_c_coding_standard_2018.pdf)
    - Though I found this on a blog, it's long enough to be a book. What I like about this standard is that it's not a standard based on stylistic preferences or convention - each rule is designed to minimize software defects, and along with every rule is accompanying reasoning (so you can see for yourself how it minimizes defects) and an idea on how to enforce it.
- [Reusable Firmware Development: Jacob Beningo](https://www.amazon.com/Reusable-Firmware-Development-Practical-Approach/dp/1484232968/ref=sr_1_1?crid=1ALQIVXC3BJB&dib=eyJ2IjoiMSJ9.aMHouBNuOYUQw2QNR8xvlU8mMqHnhpJLD9Hv-xpPK4N6jI53f4bXVZnlXwb8QTUVSiqfzpKimuD9f_HUv-8Ec3BgCFko6cVJB0zA1LZChkGqw-7pS1u9YQV3bmxcMJIPJZIFfaaEmfm-Df6Ufgsq4EuLqqfG8eSxXYLCYnB5XjsJbNyN5W89qB1bvbgrg9vV6RWR0S0Y4ZpAcXPuVAFrCUXfppVxKKrPS_HLdux_Mqs.5BxKVbZYQbHSDmfhFFXDdfYWwOvN8g0e77LSIqh8Gss&dib_tag=se&keywords=reusable+firmware&qid=1729439930&sprefix=reusable+firmware%2Caps%2C84&sr=8-1)
    - A book that focuses on how to write platform-independent embedded software.
- [High Speed Digital Design: A Handbook of Black Magic: Howard Johnson, Martin Graham](https://www.amazon.com/High-Speed-Digital-Design-Handbook/dp/0133957241/ref=sr_1_1?crid=1S7AUIY5MVSAX&dib=eyJ2IjoiMSJ9.4xxk1wefGbHuRgJDmv1pKT7h8tCsrvNxd9eAZpL8ZuDGX7q5kQcXYNDf1hxhsoc_.0Z-w85hW6K4-vE9PUgtLF8b7JEicx3Crn6mvEDUSpiA&dib_tag=se&keywords=high+speed+digital+design+a+handbook+of+black+magic&qid=1729439987&sprefix=high+speed+digit%2Caps%2C88&sr=8-1)
    - Talks about how the problems with analog circuits show up in digital circuits. An important note is that the ideas in this book don't just apply to RF and high frequency digital signals - these issues show up even in low frequency digital signals with high slew rate (dV/dt). So it's applicable to pretty much any modern hardware system that relies on digital signals.
- [Troubleshooting Analog Circuits: Robert Pease](https://www.amazon.com/Troubleshooting-Analog-Circuits-Design-Engineers/dp/0750694998/ref=sr_1_1?crid=34SOQMGWLPPR9&dib=eyJ2IjoiMSJ9.1KGBPTqpnVtoIei8k84aF6WWbMDxk33-GrCfvLPOjvprr3tpFhoz7SsNFadJwb0wcmTZFYa8okY2D1Xr5JiqZUta_VBSNHr6TX6k4jqiJARjLo_t7EKyxkudOq-remcdYXmTegmiG3HZqLwZ1xwUqHzIxtqIra78Nmn2fsiHoDB-AazeF4f-VLqynNyDVVM3LvNqwgNKR1jKYdtZqZMeoVQAL7WOsgRiHCTlzJsmQwU.6O1-6WPZkTXOR2LAJTZxYplBVfxkgdTLSbqTaUY4cow&dib_tag=se&keywords=troubleshooting+analog+circuits&qid=1729440176&sprefix=troubleshooting+analog+circuits%2Caps%2C84&sr=8-1)
    - A book that has helped me troubleshoot some analog circuits that I've designed before. Highly recommend.
- [The Art of Electronics: Paul Horowitz, Winfield Hill](https://www.amazon.com/Art-Electronics-Paul-Horowitz/dp/0521809266/ref=sr_1_1?crid=14Q7Y73WOZ8H7&dib=eyJ2IjoiMSJ9.iEOxsXZGsiAjWaIcEQckAIBiQ_PmOUt3eQV7ohjoTbhl2cbUKJDfvknRlYgZ755FF-7W0hujKOgymS09vypLVxfR0DVMig8ng00Upa-BBc5fKgSnCUHBitOwVCnxYCop0mGjAaVjFYCiv_13ex4mbfZqRoJegSdsIrnTTx9OegDhYIMk1BLxBqfh8frfoxKz9cVTusDK1kBMLnOguby3l80nzTbHJGKfTUOIJhpU0L0.9p72Im8Ur92oD0r9Wp9zOnligGnEaLWwLKiGEbAYqX0&dib_tag=se&keywords=art+of+electronics&qid=1729440722&sprefix=art+of+elec%2Caps%2C97&sr=8-1)
    - Because which electronics book list is complete without this? This has been really useful to troubleshoot some issues with mostly analog circuits. What I like about it is that it contains all the information a designer needs to know in one place.

## Tutorials

- [Playbook: Writing Portable Embedded Software](https://embeddedartistry.com/wp-content/uploads/2020/08/Playbook-Writing-Portable-Software.pdf)
    - The biggest dilemma of embedded software - how do you write reusable code that is robust to changes in hardware, and yet is customized entirely for the hardware you're working on? Seems like a contradiction, but there are ways around it.
- [Introduction to Microcontrollers](https://www.embeddedrelated.com/showarticle/453.php)
    - A comprehensive 14-part intro. The sections on interrupts and timers is worth a read, at least.
- [Important Programming Concepts](https://www.embeddedrelated.com/showarticle/629.php)
    - Some concepts from CS that are relevant to embedded systems
- [You Don't Need an RTOS](https://www.embeddedrelated.com/showarticle/1636.php)
    - When do you need an RTOS?
- [Diving into JTAG](https://interrupt.memfault.com/blog/diving-into-jtag-part1)

## Interview Prep

- [Crushing the Firmware & Embedded Systems Interview | Medium](https://medium.com/@akashagrawal_33749/cracking-the-firmware-embedded-systems-engineer-interview-d73a37da95bd)
- [Cracking the (embedded) Coding Interview - Manasi Rajan](https://www.embeddedrelated.com/showarticle/1503.php)
- [How to use bit manipulation to solve problems easily and efficiently | LeetCode](https://leetcode.com/problems/sum-of-two-integers/solutions/84278/a-summary-how-to-use-bit-manipulation-to-solve-problems-easily-and-efficiently/?orderBy=most_votes)
- [A 'C' Test: The 0x10 Best Questions for Would-be Embedded Programmers | RMB Consulting](https://rmbconsulting.us/publications/a-c-test-the-0x10-best-questions-for-would-be-embedded-programmers/)

## Videos

### Embedded Software

- [Tricky Parts of Embedded given at IEEE-CS (SiliconValley): Elecia White](https://www.youtube.com/watch?v=I-G669hAL2M)
- [Buried Treasure and Map Files: Elecia White](https://www.youtube.com/watch?v=XRXLUcbJIxY)
    - An amazing video by an embedded software legend on how to understand and use map files to debug some tricky embedded bugs.
    - Resources and graphics for the talk are available on the accompanying [Embedded.fm page](https://embedded.fm/blog/mapfiles)
- [Writing better embedded Software - Dan Saks - Keynote Meeting Embedded 2018](https://www.youtube.com/watch?v=3VtGCPIoBfs)
    - This talk focuses a lot on C++. However, the underlying principles are what we need to pay attention to.
- [](https://www.youtube.com/watch?v=JChTishaqQM)

### PCB Design, Circuits

- [How to Achieve Proper Grounding: Rick Hartley](https://www.youtube.com/watch?v=ySuUZEjARPY)
    - An amazing webinar that completely changed the way I see the humble ground.
- [What Every PCB Designer Should Know - Return Current Path: Robert Feranec, Eric Bogatin](https://www.youtube.com/watch?v=icRzEZF3eZo)
- [What Every PCB Designer Should Know - Crosstalk Explained: Robert Feranec, Eric Bogatin](https://www.youtube.com/watch?v=EF7SxgcDfCo)
- [EEVblog #279 - How NOT To Blow Up Your Oscilloscope!](https://www.youtube.com/watch?v=xaELqAo4kkQ)
  - Very important!
- [EEVblog #859 - Bypass Capacitor Tutorial](https://www.youtube.com/watch?v=BcJ6UdDx1vg)

## Miscellaneous

- [The volatile keyword](https://www.embeddedrelated.com/showarticle/1650.php)
- [Implementing State Machines](https://www.embeddedrelated.com/showarticle/543.php)
    - How you implement them in code
    - Here's another nice one: [How to code a state machine on C or C++](https://barrgroup.com/blog/how-code-state-machine-c-or-c)
- [Small or fast?](https://www.embeddedrelated.com/showarticle/1690.php)
    - Conveys a lens through which to look at code that's very important to embedded firmware.
    - For example: [++i and i++ : what's the difference?](https://www.embeddedrelated.com/showarticle/1629.php)
- [A Schematic Review Checklist for Firmware Engineers](https://interrupt.memfault.com/blog/schematic-review-checklist)
