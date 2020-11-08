---
layout: page
title: Syasya Azman's Project Portfolio Page
---

## Project: LogOnce

LogOnce is a one-stop logistics tracker app for clerks to monitor shipping statuses of all clients and perform common 
logistics operations. It is optimized for use via a Command Line Interface (CLI) while still having the benefits of a 
Graphical User Interface (GUI).

Given below are my contributions to the project.

* **New Feature**: Delete Client
  [\#155](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/155)
  [\#79](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/79)
  [\#71](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/71)
  [\#43](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/43)
  * What it does: allows the user to delete a client from the client list along with all orders in the order list that
  are linked to that client
  * Justification: This feature enhances the delete function as users will not need to manually delete orders made by a
  certain client when the company wishes to cease collaborations or connections with the client.
  * Highlights: This affects commands to be added in the future. The delete client functionality is tailored to 
  complement a unique client ID system instead of ID detection via displayed index of the client list.

* **New Feature**: Delete Order
  [\#155](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/155)
  [\#43](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/43)
  * What it does: Similar to delete client, it allows the user to delete an order from the order list.
  * Justification: This feature helps to differentiate deletion of orders from deletion of clients. Users can delete 
  individual orders without having to delete the client who made the order or any other important orders linked to that 
  client.
  * Highlights: This enhancement follows a unique order ID system which is different from the unique client ID system so
  that the Client and Order deletion will not have unexpected dependencies in future command implementations.

* **Code contributed**: 
[RepoSense link](https://nus-cs2103-ay2021s1.github.io/tp-dashboard/#breakdown=true&search=syasyazman)

* **Project management**:
  * Helped out with label indicators and linking of pull requests to issues on GitHub
  * Helped out with milestone indicators for pull requests on GitHub
  * Helped out with `v1.2` JAR release
  * Helped out with the management of LogOnce's landing page and About Us page

* **Enhancements to existing features**:
  * Updated the GUI color scheme : (Credits: changes were made using SceneBuilder)
  [\#87](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/87)
  * Wrote additional tests for `UniqueOrderList` to increase its method test coverage from 90% to 100%
  [\#184](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/184)
  * Wrote additional tests for `UniquePersonList` to increase its method test coverage from 81% to 100%
  [\#184](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/184)
  * Wrote additional tests for delete commands
  [\#165](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/165)
  

* **Documentation**:
  * User Guide:
    * Added LogOnce logo as header for the user guide (Credit: used Wix to make logo)
    [\#85](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/85)
    * Added documentation for the features `delete client` and `delete order`
    [\#171](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/171)
    [\#85](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/85)
    [\#55](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/55)
    * Did cosmetic tweaks to documentation of features `clear`, `exit` and `help`
    [\#162](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/162)
  * Developer Guide:
    * Added Non-Functional Requirements for LogOnce
    [\#21](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/21)
    * Added Glossary for LogOnce
    [\#21](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/21)
    * Added implementation details of the `delete client` feature.
    [\#169](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/169)
    * Added implementation details of the `delete order` feature.
    [\#169](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/169)
    * Added UML diagrams for `delete client` and `delete order`
    [\#169](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/169)
    * Helped with usage of PlantUML to make UML diagrams for LogOnce's commands
    [\#182](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/182)    

* **Testing**:
  * Added tests for `delete-client` and `delete-order`
  [\#165](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/165)
  [\#43](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/43)
  * Added tests for `UniqueOrderList` and `UniquePersonList`
  [\#184](https://github.com/AY2021S1-CS2103-F09-4/tp/pull/184)