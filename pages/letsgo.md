---
layout: page
title: LETSGO
---

A promise of public cloud computing is the significant reduction of the energy footprint that is enabled by economies of scale. Cloud services typically decrease energy consumption compared to on-premise data centers, due to less overheads, frequent technology updates, and more efficiency in scalability. Between 80% and 90% of the businesses have already migrated to the cloud. However, little research is available on how organizations can further reduce their energy footprint when running software applications in the public cloud. When re-engineering and re-architecting applications for the cloud engineers do not yet include the software tactics to manage data and/or computation more efficiently and to decrease the necessary resources and thus energy to store data, to compute resources for processing, and to transfer data between cloud, edge and customer devices. Moreover, cloud consumers do not have information on their cloud infrastructure usage, so an understanding of the impact of design decisions on energy usage is lacking. This problem increases when software is part of a corporate or public system of multiple and distributed services. Previous research of VU and Surf demonstrates the possibility to orchestrate cloud workloads towards more energy efficiency through reasoning and resource optimizations. However, these processes are proven at academic and at scientific High Performance Computing (HPC) levels and are not (yet) straightforward enough for live cloud environments, due to a lack of:

- Available live cloud environments that would allow for energy efficiency experiments in day-to-day dynamics. Such experiments enable scientific energy research in cloud practice, and can therefore not be done in isolation within the scientific Green Lab of VU or within the HPC lab of Surf. Academic set-ups cannot include all kinds of scalability, privacy, and security issues. And common live cloud environments are not fit with energy metrics in hardware and software, and can be influenced by other processes that run in a cloud facility.

- Applicable software attributes on “Energy Consumption” next to the common software development and operation attributes like cyber security, scalability, reliability, performance.
    
- Transparency about the energy consumption of hardware at cloud providers, that is inflicted by the software applications that run on that hardware.

Furthermore, the current generation of developers doesn’t master the sustainability aspects in the software creation process (architecture tactics), in contrast to e.g. security and performance. Some sustainable architecture tactics seem already available at hyperscalers of the large US ‘big tech’ cloud systems of Google, Amazon and Microsoft. However, such hyperscale tactics are mainly to be limited to CO2-footprinting and distribution of compute power to locations where green energy resources are available, and such solutions do not reduce the actual energy footprint of software systems.

The LETSGO project began in May 2023 with the goal of:

1. Identify and mitigate energy hotpots in code bases in popular applications, and establish relationships between memory usage versus CPU use profiles and GPU use profiles of these hotspots.

2. Design and assess software energy tactics based on our Green Software taxonomy on pilot cloud hardware.

3. Evaluate the energy consumption reduction of the applications in its context, and the validation of its performance on its regular software attributes.
ads.
4. Publication and dissemination of open-sourced tools in order to guide a wider stakeholder group to use green software tactics and tools. Among them, the tactics and related measures resulting from the project will be disseminated in our open-source open-access Archive of Tactics (https://s2group.cs.vu.nl/AwesomeAndDarkTactics/)


The project involves different partners from industry and academia:

- S2Group@VU and SURF (https://www.surf.nl/en) : developing energy tactics and measurement and prediction tools in the cloud environment

- Schuberg Philis (https://schubergphilis.com/en): providing a representative pilot testbed, order to do practical experiments in live cloud application layers with software applications from industrial, scientific/educational and governmental tenants of colocations.

- SIG - Software Improvement Group (https://www.linkedin.com/company/software-improvement-group) research department in the implementation of the software assurance model and prototype

- Imuno Therapeutics (https://www.imunotx.com/) and BonvinLab@Utrecht University (https://www.bonvinlab.org/) for providing scientific software applications to test our tactics.

- Sustainable Digital Infrastructure Alliance (https://sdialliance.org/) and Innofunding (https://www.innofunding.nl/en/) for bringing us together.
