

## Overview 

Security testing detects vulnerabilities in software systems and verifies that their data and resources are protected from attackers. However, it suffers from the well-known oracle problem, which refers to the challenge, given an input for a system, of distinguishing correct from incorrect behavior. In many situations where potential vulnerabilities are tested, a test oracle may not exist, or it might be impractical due to the many inputs for which specific oracles have to be defined.

We propose a metamorphic testing approach that alleviates the oracle problem in security testing. It enables engineers to specify a workable number of metamorphic relations that capture security properties of the system and automatically test the system to detect vulnerabilities based on those relations. In addition, we provide a catalog of 22 system-agnostic, metamorphic relations to automate security testing in Web systems. The approach automatically detected 100% and 75% of the targeted vulnerabilities affecting an industrial system and a leading open source system (Jenkins), respectively.

The approach will be presented at IEEE International Conference on Software Testing, Verification and Validation (ICST) 2020. Our replicability package and the toolset are available at https://bit.ly/MT2020.


