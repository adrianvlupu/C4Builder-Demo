# C4Builder-Demo

* [Overview](#Overview)
  * [1 Internet Banking System](#1-Internet-Banking-System)
    * [API Application](#API-Application)
    * [Single Page Application](#Single-Page-Application)
      * [Dynamic Diagram](#Dynamic-Diagram)
      * [Extended Docs](#Extended-Docs)
  * [2 Deployment](#2-Deployment)

---

## Overview

![diagram](https://www.plantuml.com/plantuml/png/0/RL9BRnen4BuZyH-cdAX4s4jFEIMXgpOIj2Y0efpGh1d0YXyhppYGVr_R6r2sxN5cllaUOz-nO91epN3mHJjbuexWADBoRLK5F4qFMewnYKn1UIVaPAgyhN0NDBet4zjOpRxTB0qwsIpcbK4XbjJQpZBwBDEsK0y7y_kNtvlrzlbn_NCxht_KlxwFl-R-aW9xDsuRDO5HLw211tIlsXrW5bcyfJ1AmtjG7nNuFSYHe4ce2PoIGsWlcxa7g9IFJdWwIXghTnQoOzrm8dbChe8ZkIfqqy9lZ3_nLOH1FBnfEe5sUnyiYlOEiF5HihWEVQa9eDk1nLU25jyjzTMtzLd6b0tKDnQr0RxAhbCGNLmbzmkjWcU_5wZFweZkG42V5_wcj2NK0fF5W9R-asebFX036dEvcagDuZq3_yrspJ_vb4q2EaQLOQaYKSN8SF14fdkwxheR9iw3tCvfkrTTaTlnHuvyrGkYx9IZz135zMAzxC5iZ_ykuSk_-WC0)

**Level 1: System Context diagram**

A System Context diagram is a good starting point for diagramming and documenting a software system, allowing you to step back and see the big picture. Draw a diagram showing your system as a box in the centre, surrounded by its users and the other systems that it interacts with.

Detail isn't important here as this is your zoomed out view showing a big picture of the system landscape. The focus should be on people (actors, roles, personas, etc) and software systems rather than technologies, protocols and other low-level details. It's the sort of diagram that you could show to non-technical people.

**Scope**: A single software system.

**Primary elements**: The software system in scope.
Supporting elements: People (e.g. users, actors, roles, or personas) and software systems (external dependencies) that are directly connected to the software system in scope. Typically these other software systems sit outside the scope or boundary of your own software system, and you don’t have responsibility or ownership of them.

**Intended audience**: Everybody, both technical and non-technical people, inside and outside of the software development team.

## 1 Internet Banking System

[Overview](#C4Builder-Demo)

![diagram](https://www.plantuml.com/plantuml/png/0/fLHDJnin4BqZyH-cELH12icbfvuA8IeW0X4R2Zr5izv9ujOVAzkRWAh-zuwzsML3Kt5e3Xjv_3ppvlcDl_Y0BbHQ7Hzza4QegY1OXr3wpwEHm-rm9SEwoYjFJbWJo8IXi7g4XPDeDgeggz7uq-bCeGaFqvkHma0-S6WnPZHAGsvOfkJ7HpTdt-yUvel7g_dbucRoTN9xqJ-9yHavRqs_pCK0UlK25PoZ-IdD2iQL3rQJw_7c6OZT2kmImfeWPzG0jimHokPaZ04AOIiJ_B37DR8N7qWl9i-XJvxpJ4urIWK-XMFYEQUIt9sBvwTIEEljCi3aMQpHh0YeU-1jIft7d5DkTkbGKyiyQzDdmJhoW4erl0K74j48v8FMQGpI6i3SLg5janCtZGmWE3GUHOJnYeBe4ZbdK87kfIyJcwlK38M6JEy4VXqV0V_QU-blaO6FbCDPMIefKlt8zWTk4D0Ka9Kkqfj-6yVm1IcvOKg9FvicI04xIoHqQ3NaiarhdZ-Ae4GM4L_B9ERxR7mPwMGrVXRn1sXvuMHPb-DxgHGcMyoStSXY9_116ilA9DrGoV02mRuA31k9yOnqi6KfScUtRFK3_7IaDxMvL8bPhFk46bcXVGgWf9Q12l1Lxfc23Vz1ITVrTdy5RQIW0zoAFDuF1ipHKwHpJmhhvD248HDhqjYnOvnfSBIIdfsLpDSnuW3MwDVS1bPCnOJTHO1mLCGbgjgRv3qek-eOSfyQbZ8ExkpgtouBNPUrGhuZMDG8uJgxknrTpkSpu0gfUbsV-wyhft7Fo1H-DyC-2J2TpnggBRGUumTF2VB4ZrbCdFs5IsBV4tBAZx1rVDSy4ZQUkRuu7tVXSS1gMpUpqzrDExKyJT6sdRsg-XtSxzXr1AOND4rr0smnxNRD9-rtm_fjD0fNlyXxwiLE6V65O-bL_mC0)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.

## API Application

[Overview](#C4Builder-Demo)

![diagram](https://www.plantuml.com/plantuml/png/0/fLJBRjim4Bm7o3ziVIXim8qlFVKKsqcR17aOiTt7oLXHQvaj7m99sJMA_dkNb6B9QL04g2-cLgFPuUoGvpwW2vLMfoTlf16goWas8PJ-msZaS7TMoB2fiigJ4zO4Ck5CM3t2t4aqMrMLrMZw_jrCeGdBkzkHma0-S6arjRgq9kBBH7vwSZl-zh1ShBvSBwvMjvUVBkyl-eDOdp8lIaEkxqiSGcykJQ48PbWGZCjIIO51MjFZLzznYruuMGP0auCZ527MPyvkPKuUK2a86mB9KfsX01cQ7ym7wyg8o89AXZq42wBomMfo7hOIupVImOuoo9pTyMRFUeEkCXs5tTbCggGfzloA6fqqn-r1IIq3vU2hp7Dx6_v3ZgxxDNyvRQMWPxhoZDjVOC0CFKKfZwIm9eQdCip5XZJ6j_DW7SkCqsJp2kc3IsWMkBPEf_KGDkWtl0MiM8O9ZVqW7ENn4PKV0Wf1teEo1JzG44dMVEy3wTNbpz3NcO-6iSYrGqqmQVPTGpfIui3iEfaak70mg2C8CBDLQ1rAtMrb0gzOl_6OhEm8wJYqcZ0oHxVlOocvxNXsVHIg0VmwFG7-7VBQzx8mAOQ5WMi3aSfPfSX5sNUVf_384M_BiJfMYbEJVFLncf62jn2NBuxVrpOCdhTkDzORDqkOLvg3jd-LZaCGspZj-FnoBZspM6QflUPmHIa78_zMuabKZhCPZMYMxTiqlzB5dKm8Zu_0SR9TZ2DdANbYYdgoGn0Rh1zAz7vdNTuPth4E3j8Q1URqZpZ1nuHuGTKOwe-1JQf7eGySnxDeSXERyn5gCj0nOUdfu584j9FgAdoEQWdIGNqapE4jxBX4R4bKU7CncNQ_wB3LPoXHnkk6RzUhnM8sZ-ZVKMjg46_C9h1Fo9lvmtqBFQ0wsNePMMFrQmZrQ_ZEoUJfwly3)

**Level 3: Component diagram**

Next you can zoom in and decompose each container further to identify the major structural building blocks and their interactions.

The Component diagram shows how a container is made up of a number of "components", what each of those components are, their responsibilities and the technology/implementation details.

**Scope**: A single container.

**Primary elements**: Components within the container in scope.
Supporting elements: Containers (within the software system in scope) plus people and software systems directly connected to the components.

**Intended audience**: Software architects and developers.

## Single Page Application

[Overview](#C4Builder-Demo)

![diagram](https://www.plantuml.com/plantuml/png/0/TLB1Rjim3BqRy3zmEIL05rzssYxDt6BfaBP1ucpeAM1iDbQdI88a9nk6_Vj8EKrRPCl1aSX7yhr7NOQ8FdOxdMVlbAbrrn2qCRhmiIWy7iPR5TjkqmNojJMHJ1pNTbTWunMQlUvSLvGVtiyrchYwdHKQ8uN8eNLfTyuQmRlKFCzcauVxLRN-VbDDrxFhBzTtLyEHn4lkYygG7w9J5p2Op6zWufnMDKPbpO13JxX7GDF0qdbbjd3xhPJm5Mcr9nyWjWIi8weQZYmJMiAAhzvGX0sQ7r8R-AC976u9y6NCUF2MpFgpxKo3_jSmEEHPoxviBcMlsOtWTvu1_qw2XzvsaT5SjEXFmdL1M4UG57cvJvcW9Wz1Aw4R5Fj-B1GcRpk6Q3s9O8m8IxdqBPlkfnmgrbappgC6ktaY7jHQtOXQiU2LokGIdG_GTgiCTvh9FpnQltlXN6eCuNbC0YRppfiuRn-L5fxp_fJS-a-ZvF-X9K-98_VTKiFR0dbgKAE1lQ93MYCrYWMfK32Q4SBkw7sU_P6bBKZtM-eVq2fG6lDrUNzNJAjglkntAx2Zq6T34tJqgS-TzlRFx4dTMJRFBiaqwPN_1G00)

**Level 3: Component diagram**

Next you can zoom in and decompose each container further to identify the major structural building blocks and their interactions.

The Component diagram shows how a container is made up of a number of "components", what each of those components are, their responsibilities and the technology/implementation details.

**Scope**: A single container.

**Primary elements**: Components within the container in scope.
Supporting elements: Containers (within the software system in scope) plus people and software systems directly connected to the components.

**Intended audience**: Software architects and developers.

> Example of included local image

![](2020-01-10-16-21-41.png)

## Dynamic Diagram

[Overview](#C4Builder-Demo)

![diagram](https://www.plantuml.com/plantuml/png/0/NLF1Rjim3Bq7o3zmEQL3brns6Z2iYNDOXtKDwdRNWfOPMvjC6HIL81ZsxvDSTqdg4oNwFJu-KZT1KJHsRZfvPzcuM1Eqgdtuj5mA7XQDrJPMCP0Opqgi2-Ex9TPYaVSkzd5PVFomTSZwTFTzwL0fQBfwtXmPEsiM_K0zdHG9ZPP9vg77QvYLbXj7iCM6ODNtpXfKwtcMKhzmZy68xHMGQrXn4nrApcp5xsrD0T0vq9R09ad2f50X_qwCi8jiCWywgqTG3oO6zHr9WBt5XB4aSA0AAl67rDHYTdMcRLFDwohLsQ1YXO5opNj1auI-Na5fMkemPqhrahHaRq2eiK5bw26fsddfNk8MGqirO4noMSSkmGZL-OWkN0CQGo60yqqwa9fBJSzh7xb6ESuhaugkjhSNVbtzcKuWVONlUi-9SnvimvO7Ynk6MuPC9Tuv6ZmiUyb6tVqiu27DwarsvLpoPUWfPFioMUedXnT-hqU_osDGwhBWDoB8H4aZo0N7y9Gzax4cv8l9NWvGA6zK_Qea8t9hfaLkyg7740vUwZFZ_kPjUo3ticSdCsBLMGtdpYVMNFfRUVzZ-VNnSLjc-80SGMTD56dZ0jYmEisHwlaLv0cCeFy_3oiKo95HU0yxyTtevw4beI5ERuFWCtmPwc_MHIQPJcw8w-6v_0C0)

**Dynamic diagram**

A simple dynamic diagram can be useful when you want to show how elements in a static model collaborate at runtime to implement a user story, use case, feature, etc. This dynamic diagram is based upon a UML communication diagram (previously known as a "UML collaboration diagram"). It is similar to a UML sequence diagram although it allows a free-form arrangement of diagram elements with numbered interactions to indicate ordering.

**Scope**: An enterprise, software system or container.

**Primary and supporting elements**: Depends on the diagram scope; enterprise (see System Landscape diagram), software system (see System Context or Container diagrams), container (see Component diagram).

**Intended audience**: Technical and non-technical people, inside and outside of the software development team.

## Extended Docs

[Overview](#C4Builder-Demo)

![diagram](https://www.plantuml.com/plantuml/png/0/TOvDQm8n48RF3UG_lE2X9vTMUkn1j3qAXVw2SNUw19F9aic2elvtpLhxiRQvJ9ZtuvcvPagv3zwQUxnttcKuoH5FwAXbjQOCpBOpQtJZfAD4OP1Mb5edU7mO2w_Rp4d8BwEF2MsYtTYnYAdXTD7NdkgDDTRKdbIn8ELb-PMLK63jg6O8vwhfGzXXyZ8yxAsvgxxSU3vCftZZf57EmeevEsaHVovl0lYq5TJnblSHOw7W6rvTkZ24hxt0VsVyplvrqq0TfKkYbrwvgQwsESkvmvy0)

![diagram](https://www.plantuml.com/plantuml/png/0/ROz12iCW44NtWdUO2-G28OIeEK6XT2qw2schgKu2lNqTxQA1hXpyR_x_inIocVRdGugj3i65pKQ2Qy4iXHJymZ236c5DjvJlKbX7uR24e1XGhEeHfWbSnlfzmTUEXM2UVr3Dg6RK_34oKXWOkWzBQueeXQykERrPRRkznTVUj2pFr3cazU7MdDDjpeKNZBwU-m40)

Multiple markdowns can be ordered using `<name>.1.md, <name>.2.md .. <name>.<n>.md`

Feel free to add any additional details necesary.

## 2 Deployment

[Overview](#C4Builder-Demo)

![diagram](https://www.plantuml.com/plantuml/png/0/rLPHJnin37v7uZzuVHcWqaA59hGdIikWYDAAAsEJ9bM-96qpSiafoHNOn7-VasifxOequ6dtK2MkFyV-RCSvSXwjBpArkV51QgOABc3YVUu-r-iMxsfZwIT5MZXXcT5UQ5zZ9giZjnBrL1LvKMyTxFOLQd_TlQWhzC9v4WtR8bVc8Gk0F5hVtBXeVkzT3uOtdS7PyEBazEIolRKTv0lLuQNXOYjNh0gLOpc6OzItGDlAoXuuUWH6264hsxytDu2-LJDS4ogLuvH0kvZBdPsT7_x-CDYwJWlj2zZ_LDixW8j1ycHZdHtCaKq4ePfn0GEJCVILLG4SrkwNx8IlHPoXrCAI5HaG_Guqyrn90aYZWv5pd2AWvf3aLkenTB-sWhXlpLHouQ0JWjJ2n-23mgZGB81HIVy0KqbeE4zwb_MpmQ2V01rHgsmlt7Wibu_hIPhnmzEz_MTiXUshUJ8McGeyzU82Tg5lPORseRAGxJVOonorqosUacwRafkY4m5t9HIMmS9S30cHdc7uD_764aMXEi6AiNJUHcsGUcHi5jTLcA2R20vO-0avEwCUc1KyR56vAY1ZmZbGPamRuTcR66miCzXu8uEDvnGcWjgElvR4nl_7OlgSlJkHbjrwyCPkRRotNSa3Gjo8z1_RjIsKd0hhWDW1kbA989XTc54xYF_gP4S_bCySnm9mSSmBj3skkoip4_ni5SwRJDYF3aWWoIONKyb46NLE-qul0MEXgRaraZy5lWYun95-jpH0i83-XjJ1KY_TI0XAPj9JCRWYTHIF6QsFR_ccyWROp4yNhot2IBliS0nzRQ0qTVBbI8Ea20CWE2rfF3apyd0ZDJTtBlXKHfuXwoKl3edKahAmirmVbxjWyTIOa9lMnD9nLUYQNr8fX2_IYf5Phfm5YIx7q4zbMliXhMkg9s5MvcLLDFMuK6YNsLNgVOHIwS8ihATAcfSFNGHFcIudKXTlwT0mbnYTJFLhWZS_dT7bF0aM0Yg6zZf8xA6IaaLxc1WPMwJncRjpO3mcZe8hWTp1Y78G-RgpL7Rp0y_RnwqLHECLa61_ZYXpH6hnNK6wyLro93IdfyiV)

**Deployment diagram**

A deployment diagram allows you to illustrate how containers in the static model are mapped to infrastructure. This deployment diagram is based upon a UML deployment diagram, although simplified slightly to show the mapping between containers and deployment nodes. A deployment node is something like physical infrastructure (e.g. a physical server or device), virtualised infrastructure (e.g. IaaS, PaaS, a virtual machine), containerised infrastructure (e.g. a Docker container), an execution environment (e.g. a database server, Java EE web/application server, Microsoft IIS), etc. Deployment nodes can be nested.

**Scope**: A single software system.

**Primary elements**: Deployment nodes and containers within the software system in scope.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.