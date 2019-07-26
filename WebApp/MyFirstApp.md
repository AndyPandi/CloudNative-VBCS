# ORACLE Cloud Test Drive: Autonomous Visual Builder Cloud Service

## Building MyFirstApp

### Introduction
Visual Builder Cloud Service 어플리케이션의 기본 컴포넌트는 Mobile Applications, Web Applications, Service Connections, Business Objects, Processes 가 있습니다.

Mobile 또는 Web Application의 기본 구성 요소는 User Interface(UI) 컴포넌트, Variables, Action Chains, Page Flows, Page Navigation, REST endpoints를 통한 Data Access가 있습니다.

블록 생성과 그 상호작용들은 다음과 같이 요약할 수 있습니다.

+ **Variables** 는 클라이언스 상태를 관리하고 저장하는데 사용되는 메커니즘입니다. 모든 변소는 type과 scope가 있습니다.

+ **action chain** 은 하나 이상의 개별 동작으로 구성됩니다. Action chain 은 event에 의해 트리거 됩니다. (예를들어, 버튼클릭시 페이지를 탐색하는 트리거) 각 작용은 단일 비동기 작업단위를 나타냅니다. Action Chain은 context 내에서만 유효한 input 파라메터와 지역변수를 정의할 수 있으며 또한 애플리케이션 범위의 input 파라메터와 지역변수에만 접근할 수 있습니다.

+ **Page flows** and page navigation govern the transmission of information from one page to another. Each individual page has a lifecycle, as does an application. Each lifecycle event (entry or exit from a page, for example) can provide a trigger for an action chain.

+ A **UI component** encapsulates a unit of user interface through a defined contract – specifically, the Oracle JavaScript Extension Toolkit (JET) components contract. Component properties are bound to variables, and component events trigger action chains.

All data entering a mobile or web application is based on REST. This data can come from custom business objects and from business objects provided by service connections. Actions and variables control how data is sent to and from a REST endpoint in a mobile or web application. A developer can create a type that matches the REST payload and pass the data using a variable of that type.

The following figure shows the interactions among these building blocks.

![alt text](../resources/images/bo/bb-interactions.png "Logo Title Text 1")

## What are you going to build
In this hands on lab you will be building a Simple HR application that features Employees, Departments and Locations.
Below a preview of the end result.

![Finished Application](../resources/images/graph/107-new.png "Finished Application")
----
Have fun!

Continue with PART 1

> [`HOME`](../README.md) | [`PART 1`](PART_1.md) | [`PART 2`](PART_2.md) | [`PART 3`](PART_3.md)

