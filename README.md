# levTools

current Version is 1.3.1

1. Abstract

The levTools are a set of abstractions for Pure Data. They are primarily designed for teaching electronic music. Moreover they have a huge potential for experienced pd-users or computer musicians in general. The levTools are optimized for purr data (or pd-l2ork), but can be used in pure data vanilla as well, given the needed externals are installed. The levTools are free and open source. They were first developed by Marten Seedorf in the context of the Berlin based lev–project, an educational project focussing on electronic music culture.


  1.2. To Do

- translation to english (so far all the texts are in german)
- integrate the new modules to the levTools by adding help-patches to these modules
- create new modules



2. Description

The levTools basically are a compilation of abstractions for pure data that form a modular toolset for generating and editing electronic sounds, building software instruments like synthesizers and drum-machines, etc..

There are
- modules for sound input and output
- a variety of modules for generating tonal or percussive sounds (common oscillators, additive synthesis, wavetable synthesis, kick- and snaredrums, hihats, toms, etc.)
- two sequencer modules (tonal and drum sequencer)
- sampling modules
- looping tools (midi and audio)
- a variety of effect modules (filter, delay and room-effects, phaser, flanger, chorus, granular pitch effect, distortion, ring modulation, downsampling, bitcrush, etc.)
- sync modules for tempo control (Ableton LINK)
- control modules (to connect midi devices, use the keyboard as a piano, etc.)
- modulation modules
- a record module

These modules can be combined in various ways, opening up a lot of creative room for experiments and creating unique instruments. Moreover, experienced users can combine the modules with pd-code, further expanding the possibilities. One of the main design characteristics is the mantra ‘low threshold, high ceiling’. Each module itself is easy to use with a simple GUI and few control parameters. The low threshold makes the levTools suitable for education. On the other hand you can create complex structures and sounds by combining the modules into a larger whole. In our opinion the levTools have reached a level of functionality that leads to a new way of using Pure Data. They could be described as a simpler version of blocks from Native Instruments Reaktor or similar software or even better, as a simpler version of Max for Cats’ OSCiLLOT for Max for Live.

It is important to mention that while a lot of code for the Tools was originally written, a similar amount was collected from the Pure Data community.

The levTools can be downloaded for free from the homepage of the lev-Project, www.lev-berlin.de. They will regularly be expanded by new modules and functions, which will be published under ‘news’ on the homepage. Video tutorials can be found on the lev-project’s Youtube channel.



3. The levTools and Purr Data

The levTools are optimized for Purr Data, the most recent pd-version. The big advantage of this version is that it can be used with all common OS, an absolute necessity when designing software for educational purposes. They also work with pd-extended and the linux-centered pd-l2ork. A list of the necessary libraries to run the levTools in pd vanilla can be found on www.lev-berlin.de.



4. Functions and Features

This is a list of remarkable functions and features

- simple and user-friendly GUI
- help-patch for every module 
- easy-understandable modules with a manageable amount of control parameters
- saving and loading presets
- easy integration of hardware midi controllers
- simple record function
- Ableton Link-enabled via the [levlink]-module
- comes with an introduction (in german), a list of modules, some example-patches
- published under GNU GPLv3



5. Artistic and educational Potential

From an artistic point of view, the most interesting aspect of the levTools is that they allow the design of unique instruments by implementing the modular structure in unusual ways. While this is undoubtedly possible with other software as well, it is remarkably easy when using the levTools. You can easily combine simple modules to very complex, unusual instruments. From an educational point of view, the modular structure of the tools brings many advantages. The vast field of electronic sound synthesis can be segregated into understandable portions, explained or discovered step by step. By using the separated modules in building whole instruments learners can discover the function of every module in a creative way. The simple character of each module offers young as well as old beginners an easy start into the field of electronic sounds and computer music. Obviously, the free licence of the levTools is a big advantage for educational institutions, which are normally underfinanced. 
