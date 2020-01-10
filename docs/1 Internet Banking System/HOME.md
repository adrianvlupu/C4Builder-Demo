# 1 Internet Banking System

![diagram](https://www.plantuml.com/plantuml/svg/0/fLHDJnin4BqZyH-cELH12icbfvuA8IeW0X4R2Zr5izv9ujOVAzkRWAh-zuwzsML3Kt5e3Xjv_3ppvlcDl_Y0BbHQ7Hzza4QegY1OXr3wpwEHm-rm9SEwoYjFJbWJo8IXi7g4XPDeDgeggz7uq-bCeGaFqvkHma0-S6WnPZHAGsvOfkJ7HpTdt-yUvel7g_dbucRoTN9xqJ-9yHavRqs_pCK0UlK25PoZ-IdD2iQL3rQJw_7c6OZT2kmImfeWPzG0jimHokPaZ04AOIiJ_B37DR8N7qWl9i-XJvxpJ4urIWK-XMFYEQUIt9sBvwTIEEljCi3aMQpHh0YeU-1jIft7d5DkTkbGKyiyQzDdmJhoW4erl0K74j48v8FMQGpI6i3SLg5janCtZGmWE3GUHOJnYeBe4ZbdK87kfIyJcwlK38M6JEy4VXqV0V_QU-blaO6FbCDPMIefKlt8zWTk4D0Ka9Kkqfj-6yVm1IcvOKg9FvicI04xIoHqQ3NaiarhdZ-Ae4GM4L_B9ERxR7mPwMGrVXRn1sXvuMHPb-DxgHGcMyoStSXY9_116ilA9DrGoV02mRuA31k9yOnqi6KfScUtRFK3_7IaDxMvL8bPhFk46bcXVGgWf9Q12l1Lxfc23Vz1ITVrTdy5RQIW0zoAFDuF1ipHKwHpJmhhvD248HDhqjYnOvnfSBIIdfsLpDSnuW3MwDVS1bPCnOJTHO1mLCGbgjgRv3qek-eOSfyQbZ8ExkpgtouBNPUrGhuZMDG8uJgxknrTpkSpu0gfUbsV-wyhft7Fo1H-DyC-2J2TpnggBRGUumTF2VB4ZrbCdFs5IsBV4tBAZx1rVDSy4ZQUkRuu7tVXSS1gMpUpqzrDExKyJT6sdRsg-XtSxzXr1AOND4rr0smnxNRD9-rtm_fjD0fNlyXxwiLE6V65O-bL_mC0)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.