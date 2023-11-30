# Rowhammer Revisited: From Exploration to Exploitation and Mitigation
 A list of resources for the topics covered in the m0leCon 2023 talk **Rowhammer Revisited: From Exploration to Exploitation and Mitigation**.
 
# Papers
- [Flipping bits in memory without accessing them: an experimental study of DRAM disturbance errors](https://dl.acm.org/doi/abs/10.1145/2678373.2665726) first Rowhammer paper also introduces PARA
- [RowHammer: A Retrospective](https://ieeexplore.ieee.org/abstract/document/8708249) overview of the last years of Rowhammer research
- [Drammer: Deterministic Rowhammer Attacks on Mobile Platforms](https://dl.acm.org/doi/abs/10.1145/2976749.2978406) exploits Rowhammer on phones
- [Rowhammer.js: A Remote Software-Induced Fault Attack in JavaScript](https://link.springer.com/chapter/10.1007/978-3-319-40667-1_15) shows that Rowhammer is possible for a javascript envoirement in the browser
- [Throwhammer: Rowhammer Attacks over the Network and Defenses](https://www.usenix.org/conference/atc18/presentation/tatar) Rowhammer attacks by sending packets to network controllers
- [Another Flip in the Wall of Rowhammer Defenses](https://ieeexplore.ieee.org/abstract/document/8418607) 
- [Uncovering In-DRAM RowHammer Protection Mechanisms: A New Methodology, Custom RowHammer Patterns, and Implications](https://dl.acm.org/doi/abs/10.1145/3466752.3480110)
- [BLACKSMITH: Scalable Rowhammering in the Frequency Domain](https://ieeexplore.ieee.org/abstract/document/9833772)
- [TRRespass: Exploiting the Many Sides of Target Row Refresh](https://ieeexplore.ieee.org/abstract/document/9152631)
- [REGA: Scalable Rowhammer Mitigation with Refresh-Generating Activations](https://www.research-collection.ethz.ch/handle/20.500.11850/587835)
- [CSI:Rowhammer – Cryptographic Security and Integrity against Rowhammer](https://ieeexplore.ieee.org/abstract/document/10179390)
  
# Code
- [Google Rowhammer Tester](https://github.com/google/rowhammer-test) Rowhammer tester
- [CMU-SAFARI Rowhammer Tester](https://github.com/CMU-SAFARI/rowhammer) Rowhammer tester
- [rowhammer.js](https://github.com/IAIK/rowhammerjs) Rowhammer from the browser
- [drammer](https://github.com/vusec/drammer) Rowhammer on mobile phones
- [Blacksmith](https://github.com/comsec-group/blacksmith) Rowhammer fuzzer
- [Trrespass](https://github.com/vusec/trrespass) Rowhammer fuzzer to break TRR
- [DRAMA](https://github.com/IAIK/drama) Reverse engineering for DRAM functions
- [Hammulator](https://github.com/cispa/hammulator) simulating Rowhammer exploits for rapid prototyping

# Our papers
- []()
- []()
