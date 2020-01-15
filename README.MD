# Adaptive  Sampling  Technique  using  KullbackLeibler  distance

## Contributers

Arun Vignesh Malarkkan
Gowtham Sekkilar
Raghavendran Ramakrishnan
Faisal Alatawi

Arizona State University
Dec 3, 2018

There are two modules present in this project:

## 1. Tracking 
This application is used to demonstrate the ability of the sampling technique to score in game of Ghostbuster.

## 2. Ghostbuster
This is modified version of programming assignment for CS 188 in UC Berkeley.
We altered the dynamic ghost buster game to use the Adaptive sampling.The GUI also provides a visual representation of sample size. We have also added a feature to view the sample size dynamically in the GUI.

## To run the tracking code:

    -To test the code:
     python KLD_run.py

    -To run q4 (from project 4) :
    python KLD_run.py  -q q4
    
    - note add (--no-graphics) to turn off the graphics : python KLD_run.py  -q q4 --no-graphics

    -To run q5 (from project 4):
    python KLD_run.py  -q q5

*To run the ghostbuster app:

## Switch to the ghostbuster project

 -To run the ghostbuster game:

  python ghostbusters.py -w -m center -i approximate -k 1 --fixrandomseed -n 0.3 -l medium -n 0.8


