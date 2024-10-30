# IRAM
The new development of Berkeley IRAM project 

The Berkeley IRAM project was a research project (since 1996) in the Computer Science Division of the University of California, Berkeley which explored computer architecture enabled by the wide bandwidth between memory and processor made possible when both are designed on the same integrated circuit (chip). Since it was envisioned that such a chip would consist primarily of random-access memory (RAM), with a smaller part needed for the central processing unit (CPU), the research team used the term "Intelligent RAM" (or IRAM) to describe a chip with this architecture. Like the J–Machine project at MIT, the primary objective of the research was to avoid the Von Neumann bottleneck which occurs when the connection between memory and CPU is a relatively narrow memory bus between separate integrated circuits.

## Project Overview

Today microprocessors and memories are made on distinct manufacturing lines, yielding 10M transistor microprocessors and 256M transistor DRAMs. Plants to manufacture these chips cost billions of dollars.

One of the biggest performance challenges in computer systems today is the speed mismatch between microprocessors and memory. To address this challenge processor designers now typically devote a large fraction of the transistors and area of the chips to large SRAM caches.

IRAM team predict that over the next decade processors and memory will be merged onto a single chip. Not only will this narrow or altogether remove the processor-memory performance gap, it will have the following additional benefits: provide an ideal building-block for parallel processing, amortize the costs of fabrication lines, and better utilize the phenomenal number of transistors that can be placed on a single chip. Let's dub it an "IRAM", for Intelligent RAM, since most of transistors on this merged chip will be devoted to memory.

A single gigabit IRAM should have an internal memory bandwidth of nearly 1000 gigabits per second (32K bits in 50 ns), a hundredfold increase over the fastest computers today. Hence the fastest programs will keep most memory accesses within a single IRAM, rewarding compact representations of code and data.


##History

The initial efforts of the IRAM project were undertaken during the Spring 1996 offerring of CS 294-4 at UC Berkeley. This advanced graduate course, led by Prof. David Patterson, re-examined the design of hardware and software that is based on the traditional separation of the memory and the processor. The course web page contains a considerable amount of useful information, including copies of slides from many guest speakers as well as the results from three sets of projects performed by more than a dozen graduate students.

An earlier discussion that helped lead to the development of this course can be found in the article "Microprocessors in 2020", by Dave Patterson, in the September 1995 issue (pages 48-51), of Scientific American.
