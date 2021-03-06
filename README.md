# Insightful talks and papers
This repository contains a list of links to papers or conference talks.
They are grouped in various categories.

The reader may find various interesting and insightful information here, that may improve the code quality one writes or the tool knowledge one has.

The target audience is basically everyone with interests like myself, i.e. the topics in this list include Rust, C, C++, some Java and other programming languages as well as architecture-talks on x86, ARM, GPUs, etc.
There are design patterns and other design and infrastructure topics as well.

Links written in _italics_ are somewhat different from the others, i.e. are no real talks, but more tutorials, rambling, tutorials or informal sources.

## Software Design
- [GOTO 2016: Small is Beautiful](https://youtu.be/B3b4tremI5o) by Kevlin Henney
- [GOTO 2017: Code as Risk](https://youtu.be/YyhfK-aBo-Y) by Kevlin Henney
- [ITT 2016: Seven Ineffective Coding Habits of Many Programmers](https://youtu.be/ZsHMHukIlJY) by Kevlin Henney
- [NDC London 2017: Clean Coders Hate What Happens to Your Code When You Use These Enterprise Programming Tricks](https://youtu.be/FyCYva9DhsI) by Kevlin Henney, especially the [part on Java imports](https://youtu.be/FyCYva9DhsI?t=1674)
- [NDC London 2018: Refactoring to Immutability](https://youtu.be/APUCMSPiNh4) by Kevlin Henney
- [CppCon 2018: OOP Is Dead, Long Live Data-oriented Design](https://youtu.be/yy8jQgmhbAU) by Stoyan Nikolov
- [Meeting C++ 2018: Data oriented design in practice](https://youtu.be/NWMx1Q66c14) by Stoyan Nikolov
- [CppCon 2014: Data-Oriented Design and C++](https://youtu.be/rX0ItVEVjHc) by Mike Acton
- [Parse, don't validate (the essence of type-driven design)](https://lexi-lambda.github.io/blog/2019/11/05/parse-don-t-validate/) by Alexis King

## Data Structures
- [CppCon 2016: High Performance Code 201: Hybrid Data Structures](https://youtu.be/vElZc6zSIXM) by Chandler Carruth
- [CppCon 2014: Efficiency with Algorithms, Performance with Data Structures](https://youtu.be/fHNmRkzxHWs) by Chandler Carruth
- _[CppCon 2017: Designing a Fast, Efficient, Cache-friendly Hash Table, Step by Step](https://youtu.be/ncHmEUmJZf4) by Matt Kulukundis_

## Concurrency/SIMD/Optimization
- [Rust at speed - building a fast concurrent database](https://youtu.be/s19G6n0UjsM) by Jon Gjengset
- [QCon San Francisco 2019: Parsing JSON Really Quickly: Lessons Learned](https://youtu.be/wlvKAT7SZIQ) (_simdjson_) by Daniel Lemire.
Also see [the paper](https://arxiv.org/pdf/1902.08318.pdf) on that topic.
- CppCon 2014: Lock-Free Programming (or, Juggling Razor Blades), [Part I](https://www.youtube.com/watch?v=c1gO9aB9nbs) and [Part II](https://www.youtube.com/watch?v=CmxkPChOcvw) by Herb Sutter

## Rust
- [Bay Area Rust Meetup: Data Oriented GUI in Rust](https://youtu.be/4YTfxresvS8) by Ralph Levien
- [RustConf 2016: A Modern Editor Built in Rust](https://youtu.be/SKtQgFBRUvQ) and [Recurse Localhost: Xi: an editor for the next 20 years](https://youtu.be/4FbQre9VQLI) by Ralph Levien
- [FOSDEM 2018: Idiomatic Rust](https://youtu.be/P2mooqNMxMs) by Matthias Endler
- [Rust Fest 2017: Writing Idiomatic Libraries in Rust](https://youtu.be/0zOg8_B71gE) by Pascal Hertleif
- [Rust Belt Rust Conference 2017: Rayon: Data Parallelism for Fun and Profit](https://youtu.be/gof_OEv71Aw) by Nicholas Matsakis
- [QCon New York 2019: Rust's Journey to Async/Await](https://youtu.be/lJ3NC-R3gSI) by Steve Klabnik
- [RustConf 2019: Taking Constant Evaluation to the Limit](https://youtu.be/SOfq0aqQZf8) by Oliver Schneider
- [RustConf 2020: Error handling Isn't All About Errors](https://youtu.be/rAF8mLI0naQ) by Jane Lusby

## C/C++
- [CppCon 2017: Curiously Recurring C++ Bugs at Facebook](https://youtu.be/lkgszkPnV8g) by Louis Brandy
- [CppCon 2018: The Bits Between the Bits: How We Get to main()](https://youtu.be/dOfucXtyEsU) by Matt Godbolt
- [CppCon 2017: What Has My Compiler Done for Me Lately? Unbolting the Compiler's Lid](https://youtu.be/bSkpMdDe4g4) by Matt Godbolt
- [CppCon 2016: Rich Code for Tiny Computers: A Simple Commodore 64 Game in C++17](https://youtu.be/zBkNBP00wJE) by Jason Turner
- [CppCon 2015: Tuning C++: Benchmarks, and CPUs, and Compilers! Oh My!](https://youtu.be/nXaxk27zwlk) by Chandler Carruth
- [CppCon 2016: Garbage In, Garbage Out: Arguing about Undefined Behavior](https://youtu.be/yG1OZ69H_-o) by Chandler Carruth
- [Build Stuff 2017 - Functional C++](https://youtu.be/CIg6eyJv4dk) by Kevlin Henney

## GPU programming
- [CppCon 2016: CUDA is a low-level language](https://youtu.be/KHa-OSrZPGo) by Justin Lebar

## Hardware Architecture
- [Black Hat 2017: Breaking the x86 Instruction Set](https://youtu.be/KrksBdWcZgQ) by Christopher Domas
- [DefCon 26: GOD MODE UNLOCKED Hardware Backdoors in redacted x86](https://youtu.be/jmTwlEh8L7g) by Christopher Domas
- [Black Hat 2015: The Memory Sinkhole](https://youtu.be/lR0nh-TdpVg) by Christopher Domas
- [ 2018: Spectre: Secrets, Side-Channels, Sandboxes, and Security](https://youtu.be/_f7O3IfIR2k) by Chandler Carruth
- [CppCon 2017: Going Nowhere Faster](https://youtu.be/2EWejmkKlxs) by Chandler Carruth

## Networking
- [Black Hat 2017: Cracking the Lens: Targeting HTTP's Hidden Attack-Surface](https://youtu.be/zP4b3pw94s0) by James Kettle

## Security
- [Derbycon 2015: The MoVfuscator Turning mov into a soul crushing RE nightmare](https://youtu.be/R7EEoWg6Ekk) by Christopher Domas
- [DEF CON 23: Repsych: Psychological Warfare in Reverse Engineering](https://youtu.be/HlUe0TUHOIc) by Christopher Domas
- [Fuzzing: Hack, Art, and Science](https://patricegodefroid.github.io/public_psfiles/Fuzzing-101-CACM2020.pdf) by Patrice Godefroid
- _[CppCon 2015: Racing the File System](https://raw.githubusercontent.com/CppCon/CppCon2015/master/Tutorials/Racing%20the%20Filesystem/Racing%20the%20Filesystem%20-%20Niall%20Douglas%20-%20CppCon%202015.pdf) by Niall Douglas (slides from a workshop)_

## Text redering/editing
- [Text Redering Hates You](https://gankra.github.io/blah/text-hates-you/)
- [Text Editing Hates You Too](https://lord.io/blog/2019/text-editing-hates-you-too/)

## Miscellaneous
- [Chrome Dev Summit 2019: Faster apps with JSON.parse](https://youtu.be/ff4fgQxPaO0) by Mathias Bynens _(a contra-intuitive fact about JavaScript and JSON parsing)
- [ Shakacon: reductio ad absurdum](https://youtu.be/NmWwRmvjAE8) by Christopher Domas
- [32c3: Traue keinem Scan, den du nicht selbst gefälscht hast](https://youtu.be/7FeqF1-Z1g0) by David Kriesel (_german_)
- [NDC Conference 2017: Abusing C#](https://youtu.be/JIlO_EebEQI) by Jon Skeet
- _[How we fit an NES game into 40 Kilobytes](https://youtu.be/ZWQ0591PAxM) by Morphcat Games_

## Contribution
Feel free to open a PR or issue with links to other talks and papers.
I will view them and possibly include them in this list, if I think, that this is a good fit.
