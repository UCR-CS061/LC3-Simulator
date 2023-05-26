# LC3-Simulator

## Introduction

This repo facilitates simulating the LC-3 processor in Designer for student of CS 061 at UC Riverside. This simulator shows the 
entire datapath and allows students to observe how processors execute instructions at a very fine grained level. 

The LC-3 processor was created as a teaching tool for the book ["Introduction to Computers Systems: From bits and gates to C++ & 
beyond"](https://www.mheducation.com/highered/product/introduction-computing-systems-bits-gates-c-c-beyond-patt-patel/M9781260150537.html) 
by Yale N. Patt and Sanjay J. Patel. The goal of this book is to teach beginning students how to program by teaching them first 
how a computer works, then teaching them assembly programming and finally introducing a high level compiled language, C++. This 
book is meant to be taught over two semesters, or three quarters. 

![](./assets/intro_to_computing_systems.jpeg)

At UC Riverside, however, this book is used to teach CS 061 - Machine Organization & Assembly Language Programming. This course 
one quarter course is required for all computer science, computer engineering, and electrical engineering students. Unlike the 
original intention of the book's authors, this course is taught after the students have taken the introductory programming courses that use C++.

Towards the end of the quarter, this course concentrates on the datapath to teach students how an instruction is executed in a 
modern processor. In the past, instructors used the figures from the book and drew on them to illustrate this datapath. Later,
animated slides were created to better and more accurately summarize all the steps and control signals necessary to execute 
instructions. These slides are were a big improvement, but some students were still left wanting a better and deeper understanding
of everything that happens in the datapath. This desire let the instructors to create the LC-3 processor in schematic capture
in [Digital](https://github.com/hneemann/Digital), a free and open source digital logic designer and circuit simulator by Helmut
Neemann.

Appendix C of the book provides a complete description of the microarchitecture of the LC-3 processor, upon which this simulation
is designed. Everything except interrupt driven IO works in this simulator with only a few variations from the provided 
microarchitecture.

The rest of this page describes how to get all the tools necessary to run this simulation. It also provides basic instructions for
running the simulator and getting examples as well as custom programs, written in LC-3 Assembly, running in it.

## Getting the simulator

The LC-3 Microarchitecture Simulator is an aggregation of three components, the Digital program, a GitHub repo with the LC-3 
architecture module files for Digital, and an open source HDL synthesizer, [Icarus Verilog](https://github.com/steveicarus/iverilog). 
You must install all three of these components to run the simulator on your local machine. Addtionally, instructions are provided 
below to run the simulator in a Codespace using this GitHub repository.

### Running Digital in a GitHub Codespace

This GitHub repository has all the configuration necessary to run as a [Codespace](https://github.com/features/codespaces) on
GitHub. Any free GitHub user can start a codespace and run this simulation entirely in a browser. Free GitHub accounts come with
upto 120 hours of free Codespace usage per month.

### Installing Digital on your local computer

## Running the Simulator

### Running "Hello, World!"

### Running other examples


### Getting your own LC-3 assembly runnin