# Awesome PLC Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of free and low-cost resources for learning PLC programming and industrial automation: software you can install, simulators you can practise on, courses, books and communities.

PLCs run most of the machines in factories, water plants and warehouses, but the vendor software is expensive and hard to get hold of outside work. This list focuses on ways to learn without a hardware budget. Entries marked 🆓 are free or have a free tier; 💵 means paid (often with a trial).

## Contents

- [Standards and References](#standards-and-references)
- [Programming Software With Free or Learning Editions](#programming-software-with-free-or-learning-editions)
- [Simulators and Virtual Plants](#simulators-and-virtual-plants)
- [Tutorials and Courses](#tutorials-and-courses)
- [Books](#books)
- [Open-Source Runtimes and Libraries](#open-source-runtimes-and-libraries)
- [Communities](#communities)
- [Related Lists](#related-lists)

## Standards and References

- [IEC 61131-3](https://en.wikipedia.org/wiki/IEC_61131-3) - The standard behind the five PLC languages (Ladder Diagram, Function Block Diagram, Structured Text, Instruction List, Sequential Function Chart).
- [PLCopen](https://www.plcopen.org/) - Industry body publishing IEC 61131-3 guidelines, including motion-control and safety function blocks and coding guidelines. 🆓

## Programming Software With Free or Learning Editions

- [CODESYS](https://www.codesys.com/) - Vendor-neutral IEC 61131-3 development system used by many PLC brands; free to download, with a Windows soft PLC for testing in demo mode. 🆓
- [Connected Components Workbench](https://compatibility.rockwellautomation.com/Pages/MultiProductFindDownloads.aspx?crumb=112&mode=3&refSoft=1&versions=57681) - Rockwell's software for Micro800 controllers; the Standard Edition is free (Rockwell account required) and includes the Micro800 Simulator. 🆓
- [Do-more Designer](https://www.automationdirect.com/do-more) - AutomationDirect's free programming software with a built-in simulator, so you can run ladder logic without a PLC. 🆓
- [CLICK PLC software](https://www.automationdirect.com/clickplcs) - Free programming software for AutomationDirect's low-cost CLICK PLCs, a common first hardware PLC. 🆓
- [TwinCAT 3](https://www.beckhoff.com/en-en/products/automation/twincat/) - Beckhoff's PC-based control platform; the engineering environment is a free download and runtimes use renewable trial licences. 🆓
- [Ignition Maker Edition](https://inductiveautomation.com/ignition/maker-edition) - Free, non-commercial edition of the Ignition SCADA/HMI platform for building HMIs around your practice projects. 🆓

## Simulators and Virtual Plants

- [Factory I/O](https://factoryio.com/) - 3D factory scenes (conveyors, sorters, elevators) that you drive from a real or soft PLC; widely used in schools. 💵 Free trial.
- [PLC Fiddle](https://www.plcfiddle.com/) - Minimal ladder logic editor and simulator that runs in the browser. 🆓
- [PLC Simulator](https://plcsimulationsoftware.com/) - Browser-based ladder logic practice against simulated machines with automatic grading, plus wiring and HMI exercises; free tier and a no-install first exercise. 🆓/💵 (Disclosure: maintained by the author of this list.)
- [OpenPLC Editor](https://github.com/thiagoralves/OpenPLC_Editor) - Open-source IEC 61131-3 editor with a built-in simulation mode. 🆓
- [The Work Gym PLC course](https://theworkgym.com/plc/) - Browser ladder logic simulator with contacts, timers and counters on fictional machines, traced scan by scan, with each exercise checked. 🆓/💵

## Tutorials and Courses

- [Siemens SCE](https://www.siemens.com/sce) - Siemens Automation Cooperates with Education: free learning and training documents for TIA Portal, aimed at teachers and students. 🆓
- [PLC Academy](https://www.plcacademy.com/) - Free written tutorials covering ladder logic, Structured Text and PLC basics. 🆓
- [RealPars](https://www.realpars.com/) - Video courses on PLCs, SCADA and industrial networks; a large free library on the [RealPars YouTube channel](https://www.youtube.com/@RealPars). 🆓/💵
- [SolisPLC](https://www.solisplc.com/) - Tutorials and guides focused on Allen-Bradley/Rockwell and Siemens platforms. 🆓/💵
- [Ladder Logic World](https://www.ladderlogicworld.com/) - Beginner-friendly articles on ladder logic instructions and patterns. 🆓

## Books

- [Programmable Logic Controllers](https://openlibrary.org/search?q=Programmable+Logic+Controllers+Petruzella) by Frank D. Petruzella - Widely used textbook in technical colleges; hardware, ladder logic and troubleshooting. 💵
- [Programmable Logic Controllers](https://openlibrary.org/search?q=Programmable+Logic+Controllers+Bolton) by W. Bolton - Concise introduction covering IEC 61131-3 languages with worked examples. 💵
- [Programmable Logic Controllers: Programming Methods and Applications](https://openlibrary.org/search?q=Programmable+Logic+Controllers+Programming+Methods+and+Applications+Hackworth) by John R. Hackworth and Frederick D. Hackworth - Structured design methods for sequential ladder programs. 💵

## Open-Source Runtimes and Libraries

- [OpenPLC Runtime](https://github.com/thiagoralves/OpenPLC_v3) - Open-source PLC runtime that runs on Linux, Raspberry Pi and microcontrollers; pairs with the OpenPLC Editor. 🆓
- [OpenPLC project site](https://autonomylogic.com/) - Documentation and downloads for the OpenPLC toolchain. 🆓
- [Beremiz](https://beremiz.org/) - Open-source IEC 61131-3 IDE and runtime. 🆓
- [Eclipse 4diac](https://eclipse.dev/4diac/) - Open-source implementation of IEC 61499, the event-driven distributed-control standard. 🆓
- [OSCAT](https://www.oscat.de/) - Open-source library of IEC 61131-3 function blocks (maths, time, networking, building automation). 🆓

## Communities

- [r/PLC](https://www.reddit.com/r/PLC/) - Large, active community of controls engineers and technicians; good for career and troubleshooting questions.
- [PLCTalk](https://www.plctalk.net/) - Long-running forum with a deep archive of vendor-specific answers.

## Related Lists

- [Awesome Mechatronics](https://github.com/engyasin/awesome-mechatronics) - Mechatronics books, courses and software, including an industrial automation section.
- [Awesome Industrial Control System Security](https://github.com/hslatman/awesome-industrial-control-system-security) - ICS security resources.
- [Awesome Industrial Protocols](https://github.com/Orange-Cyberdefense/awesome-industrial-protocols) - Security-oriented resources on industrial network protocols.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
