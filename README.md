# digital-dojo
**An Open Source Martial Arts Training Application**

This project is currently a Work in Progress. Many parts of the intended structure, architecture, and design have not been finalized.

## About Digital Dojo
Digital Dojo is a Martial Arts Training Application designed for use with structured systems of techniques, such as the Tracy System of Kenpo. It is designed to support solo or partner practice by providing the means to review technique descriptions and drill techniques with audio callouts. It was designed with the Tracy System of Kenpo in mind, but should be able to support any system with named techniques and variations.

Digital Dojo runs as a standalone desktop application that should work offline after installation. The Digital Dojo application does not come packaged with any system data, and is designed to allow users to enter their own data or import a dataset from their system of choice. 

A web-hosted version that integrates directly with the Tracy System of Kenpo technique data is planned to be made available for use in coordination with [Tracy's Karate Studios](http://www.tracyskaratestudios.com/). The web-hosted version will provide the Tracy System of Kenpo data after users authenticate. Users are provided an authentication login by Tracy's Karate Studios. Users can also download the data after authentication to use with the standalone desktop application.

The server hosting infrastructure is also provided in this repository, and a brief setup guide will be included to assist studios with setting up their own hosted application versions that use their own technique systems for students to login and have access to.

## About this project
This application is being developed as part of a graduate thesis in accordance with the California State University, Fullerton's Masters in Software Engineering program. This repository, as a result, includes some files and data which are purely for the sake of the graduate thesis presentation, such as early prototypes, formal requirements docs, and so on.

## Open-Source Disclaimer
The Digital Dojo application is developed as an open-source application, with the intention to support community contributions and development. It is licensed under the [GNU GPLv3](LICENSE), which is a copyleft license that requires any distributed derivative works to carry the same license. The application as distributed here is free and open-source, and always will be. 

However, any proprietary system data (such as the technique lists and descriptions in the Tracy System of Kenpo) will **not** be packaged with the application nor released in an open-source manner as the rest of the application. The application will import this data from an external source. 

## Community Request
The system data that drives this application's functionality is understandably owned and retained by whichever studio desires to prepare that data for use with this application. I make no restrictions on how you decide to distribute that data to your students in combination with this program (only that, the program itself can be freely accessed from this repository at any time). Legally, that data may be provided to students at a fee, depending on each studio's own wishes and regulations. 

However, the intention for this application is that it will not cost any additional fee to use beyond a student's regular dues at their studio. As the originator of this project, I ask, but cannot mandate, that anyone setting this application up with their own proprietary data follow through on that intention. 

The goal of this project is to provide more resources to martial arts students that make training easier and more accessible, and blocking the use of proprietary data behind additional subscriptions or fees is antithetical to that goal.

## Features

<!-- TODO, compile a list of features from known requirements and document them, in brief, below -->

## Getting Started

<!-- TODO, create a brief setup guide on how to get started with the download and installation of the application locally and for users wanting to host the application on the web. This depends on the completion of several rounds of prototyping and architecture finalization. -->

## Downloads

<!-- TODO, link to the latest download available for various OS / platforms -->

## Documentation

This project is documented with formal, structured requirements documents, including a Vision and Scope document and Software Requirements Specification using [StrictDoc](https://github.com/strictdoc-project/strictdoc). These are primarily included for the sake of completeness in the presentation of this project to an academic review board in the completion of a graduate thesis in Software Engineering at CSU Fullerton. You can read the provided documentation on the GitHub Pages site [here](https://arcanearboretum.github.io/digital-dojo/).

## Project Management

This project is managed using [Codecks](https://open.codecks.io/digital-dojo). For feature maps, suggested tasks, and other related roadmap information, please read the available content at the Codecks site. 

## Contributions

This is an open-source project, but also part of a graduate thesis. For the sake of the graduate thesis, I must complete the basic implementation of this application myself. For now, please refrain from raising issues or pull requests against this repository. Once the graduate thesis review is completed around May of 2027, the repository will be opened for public contributions. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening any issues or pull requests.

## Project Origin
The Digital Dojo application traces its origins back to an informally produced application called Dragon.exe, which was designed to run on Windows '98 systems. It is a basic application that allows users to read and review the technique descriptions for Tracy System techniques. It also features a playback system that allows users to select a belt and have audio callouts of each technique present in the belt along with the associated attack. This was intended for assisting with solo training and drilling.

The Digital Dojo application is an attempt to modernize this application and provide more features to help with solo training and instructing in any structured karate system. 
