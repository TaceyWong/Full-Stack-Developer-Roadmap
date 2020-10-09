*From: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/ *

The 6.02 course notes are courtesy of Hari Balakrishnan, Christopher Terman, and George Verghese, and are used with permission.

The [tutorial problems](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials) should be done before attempting the problems found at the end of these chapters. Solutions to the end-of-chapter problems are not available on MIT OpenCourseWare.

## Bits, Signals, and Packets: An Introduction to Digital Communications and Networks | 比特，信号和数据包：数字通信和网络简介

| CHAPTER/章节 # | TOPICS/话题                                                       |
| :-------- | :----------------------------------------------------------- |
| 1         | [Introduction (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap01.pdf) |
| 2         | [Information, Entropy, and the Motivation for Source Codes (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap02.pdf) |
| 3         | [Compression Algorithms: Huffman and Lempel-Ziv-Welch (LZW) (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap03.pdf) |
| 4         | [Why Digital? Communication Abstractions and Digital Signaling (PDF - 1.2MB)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap04.pdf) |
| 5         | [Coping with Bit Errors using Error Correction Codes (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap05.pdf) |
| 6         | [Linear Block Codes: Encoding and Syndrome Decoding (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap06.pdf) |
| 7         | [Convolutional Codes: Construction and Encoding (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap07.pdf) |
| 8         | [Viterbi Decoding of Convolutional Codes (PDF - 1.4MB)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap08.pdf) |
| 9         | [Noise (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap09.pdf) |
| 10        | [Models for Physical Communication Channels (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap10.pdf) |
| 11        | [LTI Models and Convolution (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap11.pdf) |
| 12        | [Frequency Response of LTI Systems (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap12.pdf) |
| 13        | [Fourier Analysis and Spectral Representation of Signals (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap13.pdf) |
| 14        | [Modulation and Demodulation (PDF - 1.4MB)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap14.pdf) |
| 15        | [Sharing a Channel: Media Access (MAC) Protocols (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap15.pdf) |
| 16        | [Communication Networks: Sharing and Switches (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap16.pdf) |
| 17        | [Network Routing I: Without Any Failures (PDF - 1.5MB)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap17.pdf) |
| 18        | [Network Routing II: Routing Around Failures (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap18.pdf) |
| 19        | [Reliable Data Transport Protocols (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings/MIT6_02F12_chap19.pdf) |

---

| PROBLEM SETS                                                 | SUPPORTING FILES                                             |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| **Unit 1: Bits**                                             |                                                              |
| [Problem set 1 (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/MIT6_02F12_ps1.pdf) | [Files for Python tasks 1–3 (ZIP)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/ps1.zip) (This ZIP file contains: 2 .zl files, 5 .py files and 1 .png file.)[Files for Python task 4: LZW compression (ZIP)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/ps1_lzw.zip) (This ZIP file contains: 3 .zl files.) |
| [Problem set 2 (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/MIT6_02F12_ps2.pdf) | [Files for problem set 2 (ZIP)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/ps2.zip) (This ZIP file contains: 3 .py files.) |
| [Problem set 3 (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/MIT6_02F12_ps3.pdf) | [Files for problem set 3 (ZIP)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/ps3.zip) (This ZIP file contains: 3 .py files.) |
| **Unit 2: Signals**                                          |                                                              |
| [Problem set 4 (PDF - 1.5MB)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/MIT6_02F12_ps4.pdf) | [Audiocom (ZIP)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/audiocom.zip) (This ZIP file contains: 17 .py files and 4 .pyc files.)[6.02 Audiocom documentation](http://audiocom602.blogspot.com/) |
| [Problem set 5 (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/MIT6_02F12_ps5.pdf) |                                                              |
| [Problem set 6 (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/MIT6_02F12_ps6.pdf) |                                                              |
| **Unit 3: Packets**                                          |                                                              |
| [Problem set 7 (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/MIT6_02F12_ps7.pdf) | [Files for problem set 7 (ZIP)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/ps7.zip) (This ZIP file contains: 5 .py files.) |
| [Problem set 8 (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/MIT6_02F12_ps8.pdf) | [Files for problem set 8 (ZIP)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/ps8.zip) (This ZIP file contains: 4 .py files.) |
| [Problem set 9 (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/MIT6_02F12_ps9.pdf) | [Files for problem set 9 (ZIP)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments/ps9.zip) (This ZIP file contains: 5 .py files and 1 .sh file.) |


---

hese problems should be done before attempting the [end-of-chapter problems](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/readings) or the [problem sets](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/assignments).

| PROBLEMS                                                     | SOLUTIONS                                                    |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [Tutorial 1: Information, entropy, and source coding (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor01.pdf) | [Tutorial 1 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor01_sol.pdf) |
| [Tutorial 2: Error correcting codes (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor02.pdf) | [Tutorial 2 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor02_sol.pdf) |
| [Tutorial 3: Noise and bit errors (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor03.pdf) | [Tutorial 3 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor03_sol.pdf) |
| [Tutorial 4: Digital signaling (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor04.pdf) | [Tutorial 4 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor04_sol.pdf) |
| [Tutorial 5: LTI channels and intersymbol interference (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor05.pdf) | [Tutorial 5 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor05_sol.pdf) |
| [Tutorial 6: Frequency response of LTI systems and filters (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor06.pdf) | [Tutorial 6 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor06_sol.pdf) |
| [Tutorial 7: Modulation and demodulation (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor07.pdf) | [Tutorial 7 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor07_sol.pdf) |
| [Tutorial 8: Packet and circuit switching, and Little's law (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor08.pdf) | [Tutorial 8 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor08_sol.pdf) |
| [Tutorial 9: MAC protocols (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor09.pdf) | [Tutorial 9 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor09_sol.pdf) |
| [Tutorial 10: Routing (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor10.pdf) | [Tutorial 10 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor10_sol.pdf) |
| [Tutorial 11: Reliable data transport protocols (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor11.pdf) | [Tutorial 11 solutions (PDF)](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-02-introduction-to-eecs-ii-digital-communication-systems-fall-2012/tutorials/MIT6_02F12_tutor11_sol.pdf) |