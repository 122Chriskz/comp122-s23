# COMP122 Lecture Notes: February 6, 2023

## Announcements:
   1. scheduled.md has been updated
   1. Tidbit: Git Merging and Maintaining your Notes
      - tidbit-git-merge.md
      - will review of W/R

## Today's Agenda:
   1. Instruction Set Architecture 


## Questions from Last Lecture/Lab, etc.:
   * M/W @ 9:00 am:
     - various good questions on git and such
   * M/W @ 2:00 pm:
     - no questions:
   * T/R @ 9:00 am
   * T/R @ 2:00 pm


## Review from Last-time:
   1. In General, how the high-level languages is converted into binary
      - how this binary is then executed on the physical hardware directly.
   1. Abstract Arch:
      - von Neuemann
      - Harvard:  
        - control unit in the middle serving as a traffic cop
        - two memories: one for instructions and one for data

   1. ISO/OSI model, which had 7 layers
      - what each layer does (layer 1-4) to send a message
        - physical (1): mechanics of sending a series of symbols from A to B
        - data link (2): interpreting the symbols to get a message from A to B
        - network (3): sending a message from A to Z, going through B..Y
        - transport(4): ensure the message got through and efficiently.
      - each layer calls what they send different
        1. layer 1: symbols
        1. layer 2: frames
        1. layer 3: packet
        1. layer 4: segment
        1. layer N: data
   1. Brief overview of IP packet: binary bits that chopped into fields
   1. 4 theoretical machines:  turning machine, linear bound automate, pushdown automate, finite state machine
      - from the bottom-up we added: 4. state, 3. stack, 2. bounded tape, 1. infinite tape
   1. 4 types of langues: recursively enumerable, context-sensitive, context-free , regular
   1. Boolean Algebra: 
      - 3 primary operations:  and, or , not
      - with these we can build more interesting operations: xor, half-adder,   
   1. MIPS is different than say ARM, and example of a physical architecture
   1. Universal Computer
      - tape/memory that is large enough
      - control <-> firmware
      - OS is on the tape/memory
      - Program is on the tap/memory
      - input/output from outside device
      

---
# Today's Material
  1. Instruction Set Architecture
     - See slides

---
## Resources
  - tidbit-git-merge.md
  - documents/\*.png

---
## Notes
<!-- This section is for students to place their notes -->


