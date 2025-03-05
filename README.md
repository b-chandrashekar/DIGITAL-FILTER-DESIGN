# DIGITAL-FILTER-DESIGN

COMPANY: CODTECH IT SOLUTIONS

NAME: BANAVATH CHANDRA SHEKAR

INTERN ID: CT12POB

DOMAIN : VLSI

DURATION: 8 weeks

MENTOR: NEELA SANTOSH

overview of this project:

This project designs and simulates a Digital Finite Impulse Response (FIR) Filter using Verilog, a widely used hardware description language. FIR filters are essential in digital signal processing (DSP) for applications like noise reduction, signal smoothing, and feature extraction. Let’s break down the project step by step.

Project Objective: The goal of this project is to implement a simple FIR filter, which performs weighted summation of input samples using fixed coefficients. This design ensures the system remains stable and responsive to digital signals.

FIR Filter Concept: An FIR filter processes an input signal by applying a set of weighted coefficients to a finite number of previous input samples. The mathematical equation for an FIR filter is: y[n]=∑k=0N−1h[k]⋅x[n−k] y[n]=k=0∑N−1​h[k]⋅x[n−k] Where:

y[n]y[n] is the filter output x[n−k]x[n−k] represents the current and past input samples h[k]h[k] are the filter’s coefficients (weights) NN is the number of filter taps (stages)

Design Implementation: The FIR filter is implemented using Verilog and consists of the following key components:

Shift Register: Stores the most recent input samples. Coefficient Register: Holds the filter coefficients. Convolution Operation: Computes the weighted sum of the input samples using the coefficients. Clock and Reset: Synchronizes the filter and resets state when needed.

Testbench: The testbench simulates real-world behavior by:

Generating a clock and reset signal. Providing test input data. Capturing and displaying the filter’s output. Validating the design’s correctness by monitoring the expected response.

Applications: FIR filters are widely used in:

Audio and video processing. Communication systems. Image enhancement. Biomedical signal analysis.

#output

![Image](https://github.com/user-attachments/assets/e3a77645-f2b7-4631-8798-ea4dadf58c28)
