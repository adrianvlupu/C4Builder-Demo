# 2 Deployment

![diagram](https://www.plantuml.com/plantuml/svg/0/rLPHJnin37v7uZzuVHcWqaA59hGdIikWYDAAAsEJ9bM-96qpSiafoHNOn7-VasifxOequ6dtK2MkFyV-RCSvSXwjBpArkV51QgOABc3YVUu-r-iMxsfZwIT5MZXXcT5UQ5zZ9giZjnBrL1LvKMyTxFOLQd_TlQWhzC9v4WtR8bVc8Gk0F5hVtBXeVkzT3uOtdS7PyEBazEIolRKTv0lLuQNXOYjNh0gLOpc6OzItGDlAoXuuUWH6264hsxytDu2-LJDS4ogLuvH0kvZBdPsT7_x-CDYwJWlj2zZ_LDixW8j1ycHZdHtCaKq4ePfn0GEJCVILLG4SrkwNx8IlHPoXrCAI5HaG_Guqyrn90aYZWv5pd2AWvf3aLkenTB-sWhXlpLHouQ0JWjJ2n-23mgZGB81HIVy0KqbeE4zwb_MpmQ2V01rHgsmlt7Wibu_hIPhnmzEz_MTiXUshUJ8McGeyzU82Tg5lPORseRAGxJVOonorqosUacwRafkY4m5t9HIMmS9S30cHdc7uD_764aMXEi6AiNJUHcsGUcHi5jTLcA2R20vO-0avEwCUc1KyR56vAY1ZmZbGPamRuTcR66miCzXu8uEDvnGcWjgElvR4nl_7OlgSlJkHbjrwyCPkRRotNSa3Gjo8z1_RjIsKd0hhWDW1kbA989XTc54xYF_gP4S_bCySnm9mSSmBj3skkoip4_ni5SwRJDYF3aWWoIONKyb46NLE-qul0MEXgRaraZy5lWYun95-jpH0i83-XjJ1KY_TI0XAPj9JCRWYTHIF6QsFR_ccyWROp4yNhot2IBliS0nzRQ0qTVBbI8Ea20CWE2rfF3apyd0ZDJTtBlXKHfuXwoKl3edKahAmirmVbxjWyTIOa9lMnD9nLUYQNr8fX2_IYf5Phfm5YIx7q4zbMliXhMkg9s5MvcLLDFMuK6YNsLNgVOHIwS8ihATAcfSFNGHFcIudKXTlwT0mbnYTJFLhWZS_dT7bF0aM0Yg6zZf8xA6IaaLxc1WPMwJncRjpO3mcZe8hWTp1Y78G-RgpL7Rp0y_RnwqLHECLa61_ZYXpH6hnNK6wyLro93IdfyiV)

**Deployment diagram**

A deployment diagram allows you to illustrate how containers in the static model are mapped to infrastructure. This deployment diagram is based upon a UML deployment diagram, although simplified slightly to show the mapping between containers and deployment nodes. A deployment node is something like physical infrastructure (e.g. a physical server or device), virtualised infrastructure (e.g. IaaS, PaaS, a virtual machine), containerised infrastructure (e.g. a Docker container), an execution environment (e.g. a database server, Java EE web/application server, Microsoft IIS), etc. Deployment nodes can be nested.

**Scope**: A single software system.

**Primary elements**: Deployment nodes and containers within the software system in scope.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.