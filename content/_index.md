---
title: "UCSC"
date: 2019-11-19T17:21:20+01:00
page: true
---

# CSE 130 QUIZ PREP - WEEK 1

<!-- A hugo shortcode for writing quizzes with a markdown-like syntax: https://github.com/bonartm/hugo-quiz. -->

<!-- **Try out the live code editor: https://bonartm.github.io/quizdown-live-editor/** -->


{{< quizdown >}}

# Computer System Design
What is a key challenge in modern computer system design?
> Explanation: Modern computer systems are large and complex, which is one of the most significant challenges in designing these systems.

- [ ] Managing memory efficiently
- [x] Managing the complexity of large systems
- [ ] Designing smaller transistors
- [ ] Reducing power consumption

# Complexity
Which of the following is a key question covered in managing complexity in computer system design?
> Explanation: Managing complexity and dealing with the resulting problems is one of the main focuses in computer system design.

- [ ] How to improve battery life?
- [ ] How to reduce the number of components?
- [x] How to manage complexity and the resulting problems?
- [ ] How to scale systems linearly?

# Four Issues of Complexity
Which of the following is not one of the four basic issues of complexity?
> Explanation: The four issues of complexity are emergent properties, propagation of effects, incommensurate scaling, and tradeoffs.

- [ ] Emergent properties
- [ ] Propagation of effects
- [ ] Incommensurate scaling
- [x] Direct scalability

# Emergent Properties
Emergent properties in a system arise when:
> Explanation: Emergent properties are characteristics that arise only when individual components of a system are combined, as seen in real-world examples like bridges.

- [ ] Components fail independently
- [ ] Components work as expected in isolation
- [x] New properties show up when combining individual components
- [ ] Components are isolated from each other

# Propagation of Effects
Propagation of effects occurs when:
> Explanation: Propagation of effects refers to how problems in one part of a system can affect other parts in unexpected ways.

- [ ] Problems in one component stay isolated
- [x] Issues in one component unexpectedly affect others
- [ ] Scaling increases uniformly
- [ ] The system is modular

# Incommensurate Scaling
What does incommensurate scaling imply?
> Explanation: Incommensurate scaling refers to the idea that different parts of a system do not scale proportionally, leading to unexpected challenges as the system grows.

- [ ] All parts of a system scale at the same rate
- [x] Different parts of a system scale at different rates
- [ ] System complexity is reduced with scaling
- [ ] Scaling is directly proportional to efficiency

# Tradeoffs
What is an example of a tradeoff in integrated circuits?
> Explanation: In integrated circuits, tradeoffs involve balancing factors like power consumption and cooling area as transistor dimensions shrink.

- [ ] Smaller transistors lead to increased durability
- [x] Smaller transistors use less power and generate more heat
- [ ] Larger circuits use less power
- [ ] Smaller transistors require fewer interconnections

# Signs of Complexity
Which of the following is not a sign of complexity in a system?
> Explanation: Signs of complexity include a large number of components, interconnections, irregularities, and high information content, not predictable behavior.

- [ ] Large number of components
- [ ] High information content
- [x] Regular, predictable behavior
- [ ] Lots of irregularities

# What is a System?
A system is defined as:
> Explanation: A system is defined as a set of interconnected components that exhibit expected behavior when interacting with their environment.

- [ ] A set of independent components with individual behaviors
- [x] A set of interconnected components with an expected behavior
- [ ] A group of similar components with isolated functions
- [ ] A network of unrelated components

# Large Number of Components
What symptom of complexity does a large number of components indicate?
> Explanation: A large number of components in a system increases the likelihood of bugs and interconnections, which contributes to complexity.

- [ ] Simple system design
- [ ] High system regularity
- [x] Greater likelihood of bugs and interconnections
- [ ] Easy to debug

# Large Number of Interconnections
Why does a large number of interconnections indicate complexity?
> Explanation: A large number of interconnections complicates the relationships between components, which can obscure the underlying complexity of the system.

- [ ] It increases system modularity
- [ ] It reduces debugging time
- [x] It makes relationships between components harder to understand
- [ ] It simplifies system design

# Lots of Irregularities
How do irregularities contribute to system complexity?
> Explanation: Irregularities, or small differences in components, introduce unpredictable behaviors that add to the complexity of the system.

- [ ] They reduce the number of interconnections
- [ ] They simplify system behavior
- [x] They introduce unpredictable behaviors and variations
- [ ] They increase system regularity

# Long Description
A system with high information content indicates:
> Explanation: High information content is a sign of complexity, as it indicates that the system requires detailed descriptions to explain its behavior.

- [ ] It has fewer interconnections
- [ ] It is simpler to design
- [x] It requires long descriptions due to complexity
- [ ] It is easier to maintain

# What Are Sources of System Complexity?
Which of the following is a source of system complexity?
> Explanation: System complexity increases due to interactions between multiple requirements, even if they don’t apply at the same time.

- [ ] Fewer requirements
- [ ] Limited functionality
- [x] Interactions of requirements
- [ ] Reducing the number of jobs

# Principle of Escalating Complexity
What happens when a new requirement is added to a system?
> Explanation: According to the principle of escalating complexity, adding a new requirement increases complexity more than proportionally.

- [ ] Complexity increases proportionally
- [ ] Complexity decreases
- [x] Complexity increases out of proportion
- [ ] The system simplifies

# Modularity
Modularity helps manage complexity by:
> Explanation: Modularity reduces complexity by dividing large systems into smaller, more manageable components.

- [ ] Reducing the number of interconnections
- [ ] Simplifying the black box approach
- [x] Breaking systems into smaller, manageable pieces
- [ ] Increasing the size of each component

# Large Team of Designers, Implementers, or Maintainers
A large team of designers, implementers, or maintainers is:
> Explanation: Having a large team of designers, implementers, or maintainers is considered one of the weakest signs of complexity because many complex systems may not require a large team.

- [ ] Always a strong indication of complexity
- [ ] Rarely seen in complex systems
- [x] One of the weakest signs of system complexity
- [ ] A clear sign of a simple system

# Increasing Efficiency, Utilization, or Other Measures of "Goodness"
What happens as a system continues to increase its efficiency or utilization?
> Explanation: As efficiency or other measures of "goodness" improve, additional gains become more challenging, requiring more complexity to achieve further improvements.

- [ ] Complexity decreases with each improvement
- [ ] Additional gains require less complexity
- [x] Complexity increases as gains become harder to achieve
- [ ] Efficiency continues to increase indefinitely

# Principle of Excessive Generality
What does the principle of excessive generality state?
> Explanation: The principle of excessive generality indicates that trying to design a system that does everything well often leads to it performing poorly across the board, adding complexity without benefiting the system.

- [x] If it’s good for everything, it’s good for nothing
- [ ] A system that is more general performs better
- [ ] Specific solutions lead to higher complexity
- [ ] General solutions reduce system complexity

# Law of Diminishing Returns
According to the law of diminishing returns, as one measure of goodness improves:
> Explanation: The law of diminishing returns states that as one aspect of a system is improved, making the next improvement becomes progressively harder, often increasing complexity.

- [ ] Improvements become easier to achieve
- [x] Further improvements become increasingly difficult
- [ ] Complexity decreases as performance increases
- [ ] The next improvement is just as easy as the previous one

# Modularity
What is one benefit of modularity in system design?
> Explanation: Modularity allows for interchangeable modules, meaning individual modules can be replaced or improved without having to redesign the entire system, thus reducing complexity.

- [ ] It eliminates the need for debugging
- [x] It allows replacing or upgrading individual modules without affecting the whole system
- [ ] It increases the number of bugs in the system
- [ ] It removes the need for testing individual components

# Abstraction
In abstraction, treating an individual component as a black box means:
> Explanation: Abstraction allows you to treat components as black boxes, meaning you can rely on their expected behavior without needing to know the details of how they are implemented internally.

- [ ] Knowing every detail about its internal implementation
- [x] Interacting with its inputs and outputs without worrying about its internal workings
- [ ] Avoiding interactions with other components
- [ ] Reducing the number of interconnections

# Benefit from the Robustness Principle
According to the Robustness principle, a system should:
> Explanation: The Robustness principle advises being tolerant of inputs to handle various conditions but being strict with outputs to ensure reliable system behavior.

- [ ] Be strict on inputs and tolerant of outputs
- [x] Be tolerant of inputs and strict on outputs
- [ ] Ignore input variations
- [ ] Minimize interactions with other components

# Layering
Layering in system design is beneficial because:
> Explanation: Layering simplifies system design by presenting a new abstraction for layers above, reducing the complexity of interactions between components and layers.

- [ ] It reduces the overhead of additional components
- [x] It presents a new abstraction for higher layers, simplifying interactions
- [ ] It eliminates the need for modularity
- [ ] It removes all interconnections between components

# Hierarchy
How does hierarchy reduce system complexity?
> Explanation: Hierarchy reduces complexity by organizing small groups of modules into subsystems, and then combining subsystems into larger systems, limiting the visibility of each level to minimize complexity.

- [ ] It removes the need for subsystems
- [x] It combines small groups of modules into subsystems, limiting visibility between levels
- [ ] It reduces the number of components in the system
- [ ] It eliminates the need for abstraction

# Naming
In system design, what is the role of naming?
> Explanation: Naming allows components to be identified independently of their implementation, making it easier to replace or upgrade modules while maintaining consistency in the system.

- [ ] It reduces the need for abstraction and modularity
- [x] It helps identify components independently and allows for replacing modules while keeping the same name
- [ ] It increases the complexity of system interconnections
- [ ] It eliminates the need for component replacement


<!-- Slide 2 -->
# Fundamental Abstractions
Which of the following are the three essential tasks a system performs?
> Explanation: A system typically performs three core tasks: storing, computing, and communicating information, which correspond to memory, interpreters, and communication channels.

- [ ] Store (remember) things, Compute (analyze) things, Transfer (move) things
- [ ] Store (remember) things, Compute (transform) things, Modify things
- [x] Store (remember) things, Compute (interpret) things, Communicate things
- [ ] Store (store) things, Compute (compute) things, Transfer (deliver) things

# Store Task
Which module is primarily responsible for storing data in a system?
> Explanation: The storage task in systems is handled by memory modules, such as SRAM or Flash memory.

- [x] SRAM
- [ ] ARM Processor
- [ ] PIO
- [ ] JTAG Scan

# Compute Task
Which module is responsible for performing computations in a system?
> Explanation: The computation task in systems is handled by interpreters such as processors, including ARM processors.

- [ ] Flash Programmer
- [ ] JTAG Scan
- [x] ARM Processor
- [ ] EBI

# Communicate Task
Which module is responsible for communication in a system?
> Explanation: The communication task in systems is handled by channels such as JTAG Scan or PIO.

- [ ] Flash Memory
- [ ] SRAM
- [x] JTAG Scan
- [ ] DRAM

# Memory Interface
How is memory modeled in a computer system?
> Explanation: Memory is modeled as a map between a space of names (address) and a space of values (data).

- [x] A map between a space of names and a space of values
- [ ] A direct connection between storage blocks
- [ ] A list of values without names
- [ ] A map between addresses and functions

# Memory Performance
Which metric measures how many units of memory can be transferred per unit of time?
> Explanation: Bandwidth measures the amount of data that can be read or written from memory per second.

- [ ] Latency
- [ ] Read time
- [x] Bandwidth
- [ ] Write delay

# Memory Performance
What does memory latency represent?
> Explanation: Latency refers to the time taken to retrieve a single value from memory.

- [x] The time to retrieve a single value from memory
- [ ] The speed of the memory interface
- [ ] The maximum amount of data read per second
- [ ] The delay between data requests

# Low Read Latency vs. Low Write Latency
Why is low read latency more important than low write latency in many systems?
> Explanation: Low read latency is prioritized because writes can often be made asynchronous, whereas reads tend to be synchronous.

- [x] Reads are synchronous, but writes can be asynchronous
- [ ] Writes are more complex to manage than reads
- [ ] Reads take longer than writes in most systems
- [ ] Writes have higher throughput than reads

# Memory Properties – Volatility
Which type of memory is non-volatile?
> Explanation: Non-volatile memory retains data even without power, such as SSDs and HDDs.

- [ ] DRAM
- [ ] Registers
- [ ] Cache
- [x] SSDs

# Asynchronous Writes
How fast is a program if it is bound by asynchronous writes?
> Explanation: Programs bound by asynchronous writes operate at the speed of write bandwidth, allowing multiple writes to be issued before the previous ones complete.

- [x] As fast as the write bandwidth allows
- [ ] As fast as the read latency allows
- [ ] Slower than programs bound by synchronous writes
- [ ] Slower than the read bandwidth allows

# Memory Granularity
How is data addressed in block-addressable memories such as SSDs and HDDs?
> Explanation: Block-addressable memories allow software to address blocks of bytes, usually 1024 bytes per block.

- [ ] Data is addressed by individual bytes
- [ ] Data is addressed by names and values
- [x] Data is addressed by blocks of bytes (e.g., 1024 bytes)
- [ ] Data is addressed by individual bits

# Memory Coherency
What does read/write coherency ensure in a system?
> Explanation: Read/write coherency guarantees that the result of a read operation reflects the most recent write.

- [ ] Reads and writes happen simultaneously
- [x] The result of a read is the same as the most recent write
- [ ] Data is always read from the nearest memory location
- [ ] Memory can be read or written without delays

# Interpreter (CPU)
Which part of the CPU is responsible for fetching the next instruction?
> Explanation: The Program Counter (PC) is responsible for fetching the next instruction in the CPU.

- [x] Program Counter (PC)
- [ ] Instruction Set
- [ ] Repertoire
- [ ] Environment Reference

# Communication Links
Why don’t we just use memory’s READ/WRITE interface for communication links?
> Explanation: Communication links handle more complex challenges like data corruption and broken connections, which the simple memory READ/WRITE interface cannot manage.

- [ ] It is slower than using a communication link
- [x] Data corruption, duplication, and broken connections could occur
- [ ] It requires more memory bandwidth
- [ ] It increases system complexity

# Memory Volatility
Which of the following memory types is volatile?
> Explanation: Volatile memory requires power to maintain the stored information. DRAM is an example of volatile memory.

- [x] DRAM
- [ ] SSD
- [ ] HDD
- [ ] Tape

# Memory Abundance
How does memory abundance change as you move upwards in the hierarchy?
> Explanation: Memory abundance decreases as you move upwards in the memory hierarchy, from registers to tape storage.

- [x] Memory becomes less abundant
- [ ] Memory becomes more abundant
- [ ] Memory availability remains the same
- [ ] Memory size increases

# Memory Cost
How does the cost of memory change as you move upwards in the hierarchy?
> Explanation: The cost per byte increases as you move upwards in the memory hierarchy, making registers more expensive compared to tape storage.

- [x] Cost increases
- [ ] Cost decreases
- [ ] Cost remains constant
- [ ] Cost fluctuates randomly

# Memory Performance – Bandwidth
What is an example of memory bandwidth?
> Explanation: Memory bandwidth refers to how many units of memory can be transferred per unit of time, such as megabits per second.

- [x] Megabits per second
- [ ] Nanoseconds per read
- [ ] Bits per cycle
- [ ] Cycles per instruction

# Lamport "Space-Time Diagrams"
What does a Lamport space-time diagram represent?
> Explanation: A Lamport space-time diagram shows how events are ordered in time across different processes, highlighting relationships like causality.

- [ ] The specific timing of each event
- [x] The relative ordering of events across processes
- [ ] The performance of memory over time
- [ ] The memory latency for each process

# TCP Connection Termination
Which concept is demonstrated by a TCP connection termination example in system design?
> Explanation: TCP connection termination is an example of how events in communication can propagate through a system, impacting performance and behavior.

- [ ] Latency optimization
- [x] Propagation of effects
- [ ] Memory coherency
- [ ] Memory atomicity

# Asynchronous Writes
What is the benefit of asynchronous writes in system performance?
> Explanation: Asynchronous writes improve performance by allowing subsequent writes to be issued without waiting for the previous ones to complete, maximizing write bandwidth.

- [x] It allows subsequent writes before the prior one is complete
- [ ] It ensures all writes happen simultaneously
- [ ] It reduces the overall latency of writes
- [ ] It synchronizes the write process with the read process

# Synchronous Writes
What limits the speed of a program bound by synchronous writes?
> Explanation: Programs bound by synchronous writes operate at the speed of write latency, as each write must complete before the next one can begin.

- [x] Write latency
- [ ] Write bandwidth
- [ ] Read bandwidth
- [ ] Cache size

<!-- # Memory Granularity – Block-Addressable
How is memory addressed in block-addressable storage?
> Explanation: Block-addressable memories, such as SSDs and HDDs, allow software to address blocks of bytes, typically with sizes like 1024 bytes.

- [ ] Memory is addressed byte by byte
- [x] Memory is addressed in blocks of bytes (e.g., 1024 bytes)
- [ ] Memory is addressed in bits
- [ ] Memory is addressed in kilobytes -->

# Memory Granularity – File Systems
What is the purpose of a file system in relation to block-addressable storage?
> Explanation: File systems provide a stream interface from block-addressable storage, improving the utilization of slower block devices like SSDs and HDDs.

- [x] It provides a stream interface from block-addressable storage
- [ ] It allows memory to be accessed byte by byte
- [ ] It replaces the need for block-addressable storage
- [ ] It increases the speed of read and write operations

# Flash Memory Writing
What is one challenge of writing to flash memory?
> Explanation: Writing to flash memory is complicated because erasing a 1 must happen on an entire bank, whereas writing a 0 can occur at the bit level.

- [ ] Writing a 1 requires more power
- [x] Erasing a 1 must happen on an entire bank
- [ ] Writing a 0 requires erasing the entire memory
- [ ] Writing a 1 happens at the bit level

# Memory Properties – Failure Rates
Which type of memory is most likely to fail?
> Explanation: Block devices like SSDs and HDDs have higher failure rates, so techniques like checksums or redundancy are often used to mitigate these failures.

- [ ] Registers
- [ ] DRAM
- [x] Block devices (e.g., SSDs, HDDs)
- [ ] Caches

# Memory Coherency
What does read/write coherency ensure?
> Explanation: Read/write coherency ensures that the result of a read is the same as the most recent write, maintaining data consistency across multiple locations in the memory hierarchy.

- [x] The result of a read is the same as the most recent write
- [ ] Reads and writes happen in parallel
- [ ] Data is consistently written to multiple locations
- [ ] Writes happen before any read operation

# Memory Atomicity
What does read/write atomicity ensure?
> Explanation: Read/write atomicity guarantees that a read operation occurs either entirely before or after every other write, ensuring the consistency of memory operations.

- [x] A read occurs either entirely before or after every other write
- [ ] Writes happen instantly before reads
- [ ] Reads are always synchronized with writes
- [ ] Reads and writes happen simultaneously

# CPU – Instruction Reference
What is the function of the instruction reference in a CPU?
> Explanation: The instruction reference (typically the Program Counter) in a CPU determines the location of the next instruction to be fetched and executed.

- [x] It determines where the next instruction is located
- [ ] It determines what actions can be performed
- [ ] It provides the environment for the instruction
- [ ] It stores the results of the instruction

# CPU – Repertoire
What is the repertoire of a CPU?
> Explanation: The repertoire of a CPU refers to the set of actions or instructions that the processor is capable of executing.

- [ ] The environment in which the CPU operates
- [x] The set of actions the CPU can perform
- [ ] The memory reference for the CPU
- [ ] The sequence of instructions executed by the CPU

# CPU – Environment Reference
What does the environment reference in a CPU refer to?
> Explanation: The environment reference in a CPU points to the set of registers and memory that the processor interacts with while executing instructions.

- [ ] The next instruction to be fetched
- [x] The set of registers and memory that the processor interacts with
- [ ] The available instruction set
- [ ] The CPU’s internal clock

# Communication Links
Which of the following is an example of a communication link in a computer system?
> Explanation: Communication links enable data exchange between components. Examples include Ethernet, USB, and higher-level protocols such as the Internet.

- [ ] DRAM
- [ ] Instruction Register
- [x] Ethernet
- [ ] Program Counter

# Abstraction of Communication Link
Why is memory’s READ/WRITE interface insufficient for communication links?
> Explanation: Communication links face challenges such as data corruption, duplication, and broken connections, which memory’s simple READ/WRITE interface cannot handle effectively.

- [ ] It is slower than communication links
- [x] It cannot handle data corruption, duplication, or broken connections
- [ ] It uses more bandwidth than communication links
- [ ] It introduces unnecessary complexity

# Speed of a Program – Synchronous Writes
How fast is a program if it is bound by synchronous writes?
> Explanation: Programs bound by synchronous writes operate at the speed of write latency, meaning each write must complete before the next can begin, limiting the program’s speed to the write latency.

- [x] As fast as the write latency allows
- [ ] As fast as the write bandwidth allows
- [ ] As fast as the read bandwidth allows
- [ ] As fast as the cache latency allows

# Synchronous Writes – Write Latency
What does it mean when synchronous writes are bound by latency?
> Explanation: Synchronous writes are bound by latency because each write operation must complete fully before the next one can begin, meaning the speed of the program is limited by the time it takes to perform each write.

- [x] Each write must complete before the next can begin, limiting speed to the write latency
- [ ] Write operations can occur in parallel, unaffected by latency
- [ ] Writes can begin asynchronously, improving speed
- [ ] Read operations are prioritized over writes, making latency irrelevant

# Speed of a Program – Asynchronous Writes
How fast is a program if it is bound by asynchronous writes?
> Explanation: Programs bound by asynchronous writes operate at the speed of write bandwidth, meaning multiple writes can be issued before the previous ones complete, allowing the program to run faster based on the total data transferred per time unit.

- [ ] As fast as the read latency allows
- [x] As fast as the write bandwidth allows
- [ ] As fast as the write latency allows
- [ ] As fast as the cache speed allows

# Asynchronous Writes – Write Bandwidth
What does it mean when asynchronous writes are bound by bandwidth?
> Explanation: Asynchronous writes are bound by bandwidth because multiple writes can be issued without waiting for the previous ones to complete, meaning the program’s speed is determined by how much data can be written per time unit.

- [x] The program’s speed is determined by the amount of data written per time unit
- [ ] Writes must wait for the previous ones to complete before issuing new writes
- [ ] Bandwidth is irrelevant as the program is bound by latency
- [ ] Reads are prioritized, so writes do not affect speed

# Synchronous vs. Asynchronous Reads
How does the speed of a program differ between synchronous and asynchronous reads?
> Explanation: In synchronous reads, each read must complete before the next begins, meaning the program is bound by read latency. In asynchronous reads, multiple reads can be issued simultaneously, so the program is bound by read bandwidth.

- [x] Synchronous reads are bound by latency, while asynchronous reads are bound by bandwidth
- [ ] Both synchronous and asynchronous reads are bound by latency
- [ ] Both synchronous and asynchronous reads are bound by bandwidth
- [ ] Synchronous reads are faster than asynchronous reads

# Large Number of Writes – Latency Importance
Why is latency not important with a large number of writes?
> Explanation: With a large number of writes, latency becomes less important because the program is limited by write bandwidth rather than the time it takes for individual writes to complete, allowing multiple writes to occur concurrently.

- [x] Latency is less important because the program is bound by write bandwidth
- [ ] Latency is still important because each write must complete before the next begins
- [ ] Writes are always synchronous, so latency is crucial
- [ ] Writes happen in sequence, making latency the limiting factor

# Synchronous vs. Asynchronous Writes
Does it matter if the writes are synchronous or asynchronous when considering latency with a large number of writes?
> Explanation: It does matter. Synchronous writes are bound by latency, meaning each write must complete before the next begins, while asynchronous writes are bound by bandwidth, allowing multiple writes to be issued simultaneously, minimizing the impact of latency.

- [x] Yes, because synchronous writes are bound by latency, while asynchronous writes are bound by bandwidth
- [ ] No, because latency affects both synchronous and asynchronous writes equally
- [ ] Yes, but only for small numbers of writes
- [ ] No, because writes happen at the same speed regardless of synchronization





<!-- # What function is typically used to create a socket in a C program for network communication?

- [ ] bind()
- [ ] listen()
- [x] socket()
- [ ] connect()

# Which C function is used to bind a socket to a specific local port number for listening?

- [ ] socket()
- [x] bind()
- [ ] connect()
- [ ] accept()

# To test a server application locally, which tool can you use to send requests to your server?

- [x] curl
- [ ] gcc
- [ ] make
- [ ] vim

# In a C program, which function call is responsible for setting a socket to listen for incoming connections?

- [ ] socket()
- [ ] connect()
- [x] listen()
- [ ] bind()

# What is the typical function used to accept a new connection on a socket in a C server program?

- [ ] connect()
- [ ] bind()
- [ ] listen()
- [x] accept()

# When dealing with file input/output operations in C, which function would you use to write formatted output to a stream?

- [x] fprintf()
- [ ] fwrite()
- [ ] fputc()
- [ ] fputs() -->


<!-- ---
primary_color: steelblue
---

# The sound of dog

---
shuffle_answers: false
---

What do dogs sound like?

> ![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Dog_-_%E0%B4%A8%E0%B4%BE%E0%B4%AF-6.JPG/150px-Dog_-_%E0%B4%A8%E0%B4%BE%E0%B4%AF-6.JPG)

```python
class Dog(Animal):
    def __init__(self, name):
        self.name = name
```

- [ ] yes
- [ ] no
- [ ] `self.sound = "meow"`
- [x] wuff

# Put the [days](https://en.wikipedia.org/wiki/Day) in order!

> Monday is the *first* day of the week.

1. Monday
2. Tuesday
3. Wednesday
4. Friday
5. Saturday  


# Optional Math formula rendering

$$
x = \frac{2+2}{\sqrt{a^2+b^2}}
$$


- [ ] yes
- [ ] no -->

{{< /quizdown >}}
