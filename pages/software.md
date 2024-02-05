---
layout: page
title: Our software
---

<!-- subtitle: X  -->

In the following you can find the main software (open-source) projects implemented and maintained by us. Refer to our [GitHub profile](https://github.com/S2-group/) for a complete overview of all our projects/tools.

## Experiment Runner
Experiment Runner is a generic framework to automatically execute measurement-based experiments on any platform. The experiments are user-defined, can be completely customized, and expressed in python code!

GitHub: [https://github.com/S2-group/experiment-runner](https://github.com/S2-group/experiment-runner)


## Robot Runner
A tool for streamlining the execution of measurement-based experiments involving robotics software. The tool is able to automatically setup, start, resume, and fully replicate user-defined experiments. Thanks to its plugin-based architecture, the tool is fully independent of the number, type, and complexity of the used robots (both real and simulated).

GitHub: [https://github.com/S2-group/robot-runner](https://github.com/S2-group/robot-runner)

## Android Runner
There are many experiments performed on Android devices through a laptop, and many of them have a custom test suite. At the VU we developed an Android Runner, an open-source tool to generalise the process, reducing boilerplate code and speeding up development. Android Runner is currently used in the Green Lab course at the VU and by other researchers in the software engineering community.

GitHub: [https://github.com/S2-group/android-runner](https://github.com/S2-group/android-runner)

## Lacuna
A technique for JavaScript dead code elimination, where existing JavaScript analysis techniques are applied in combination. Lacuna supports both static and dynamic analyses, it is extensible, and independent of the specificities of the used JavaScript analysis techniques. Lacuna can be applied to any JavaScript code base, without imposing any constraints to the developer, e.g., on coding style or on the use of some specific JavaScript feature (e.g., modules).

GitHub: [https://github.com/S2-group/Lacuna](https://github.com/S2-group/Lacuna)

## ATDx
ATDx is an approach designed to provide a data-driven, intuitive, and actionable overview of the Architectural Technical Debt present in a portfolio of software projects. ATDx is based on third-party source code analysis tools, architectural issue severity calculation via clustering, and aggregation of measurements into different architectural technical debt dimensions. The ATDx tool allows users to automatically run the ATDx analysis, generate reports containing the ATDx analysis results, and is integrated with GitHub. 

GitHub: [https://github.com/S2-group/ATDx](https://github.com/S2-group/ATDx)

## Android Architectural Guidelines
To efficiently develop and mantain Android apps, a paramount factor is how well apps are architected. Based on a mixed-method empirical study, we derived 42 guidelines for architecting Android apps. The guidelines cover SOLID principles, design patterns, dependency injection tools like Dagger, and many more. The guidelines are organized around 4 themes: [MVVM](https://androidarchitectureguidelines.github.io/#MVVM), [MVP](https://androidarchitectureguidelines.github.io/#MPV), [Clean](https://androidarchitectureguidelines.github.io/#Clean), and [Generic](https://androidarchitectureguidelines.github.io/#Generic) guidelines.

Website: [https://androidarchitectureguidelines.github.io/](https://androidarchitectureguidelines.github.io/)

## NAPPA
A navigation-aware technique for personalized prefetching of network requests of Android apps. NAPPA is fully automated (with the possibility of custom behavior provided by developers), transparent w.r.t. the back-end of the app (i.e., it is independent of the data types provided by the back-end and it does not require any modifications in the business logic of the back-end), and adapts its prefetching behavior according to the navigation patterns of the user.

GitHub: [https://github.com/S2-group/NAPPA](https://github.com/S2-group/NAPPA)

## Android Time Machine
Android Time Machine provides a dataset (and mining infrastructure) including 8,431 real-world open-source Android apps. It combines source and commit history information available on GitHub with the metadata from Google Play store. The graph representation used for structuring the data eases the analysis of the relationships between source code and metadata. The dataset is provided as Docker containers to improve its accessibility and extensibility.

GitHub: [http://androidtimemachine.github.io](http://androidtimemachine.github.io/)





