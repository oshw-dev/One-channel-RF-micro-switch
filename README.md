# OSHW Developer manual
> rules and development methods for open source hardware

## Table of contents
* [General info](#general-info)
* [How to join](#how-to-join)
* [The workflow](#the-workflow)
* [Inspiration](#inspiration)

## General info
Purpose of the OSHW project is to build opensource electronics.

Build good hardware require to iterate the learn, try and fail pattern. An help would have some good building block to ensure that even big tasks can be completed.

OSHW is the new home of this building blocks.

We want do it following some rules and methods.

The rules:
* The development process should be clear, tracked, public
* Follow state-of-the-art engineering specs
* Products should be human friendly, eco-friendly, repairable and designed to last
* Every module, project or software must be released with an OSHW compliant license
* Develop only with open source software, using the most open and widely accepted file formats

## The workflow

* Every repo (*project* or a *module* or *whatever*) should start with a **REQUEST.md** template (look in /template section)
* Do all this first steps:
  1. copy/paste **REQUEST.md** as **SPECS.md**
  2. copy/paste a basic **README.md** template (look in /template section)
  3. create a new Project called **"SPEC"** with template *Automated KanBan*
  4. create an *issue* called **"SPEC"** and:
    1. assign it to Dev team
    2. assign to Project as the repository
    3. set/create a Milestone with name *review*
  
* **SPEC** issues are the first workflow that should lead the next tasks, but it's not mandatory:
  * any member can update the **SPECS.md** directly
  * (preferred) Dev team update the **SPECS.md** via *issue* using Project **SPEC**, so team can view/collaborate/improve the specific task 
* The **SPEC** tasks should take care for:
  * analyze what is not has been specified in the **REQUEST.md**
  * working on the **SPECS.md** should: reveal flaws, solve preliminary design issue, get feedbacks from Dev team

* The **SPEC** stage is non-blocking, you can start (in some other branch) preliminary design process
* As **SPEC** issues are completed, **SPEC.md** updated and locked, the next stage should be the design process
* No strict rules for the design process workflow, just be collaborative and ask for feedbacks
* As design process is completed OSHW will do manufacture/assembly and hardware tests then send feedbacks to the Dev team
* **README.md** at this stage should be completed


## How to join
We are looking for open source developers and engineers

Get in contact with us by email: info@oshw.it

or join our DISCORD: https://discord.gg/p8jnsDF

## Inspiration
Open source a step forward
