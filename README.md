# Stefan Problem: Theory and Numerical Methods

## Overview

This project presents a mathematical and numerical study of the **Stefan Problem**, which is used to describe heat transfer during phase changes such as melting and solidification.

The main focus of the project is the one-dimensional melting problem, where the position of the boundary between the liquid and solid phases is unknown and changes with time. This moving boundary makes the Stefan Problem a **free boundary problem**.

The project combines theoretical analysis with numerical techniques to study the temperature distribution and movement of the phase-change boundary.

## Objectives

* Study the mathematical formulation of the Stefan Problem.
* Understand the Stefan condition and its physical meaning.
* Formulate the one-dimensional melting problem.
* Derive the analytical similarity solution.
* Study the maximum principle for the heat equation.
* Apply numerical methods to approximate the solution.
* Compare different numerical approaches.
* Analyze the accuracy and error of the numerical solutions.

## Topics Covered

### 1. Introduction

* Background of the Stefan Problem
* Physical interpretation of phase change
* Historical development
* Mathematical formulation

### 2. One-Dimensional Stefan Problem

* Stefan condition
* One-dimensional melting problem
* Heat equation in the liquid phase
* Boundary and initial conditions
* Dimensionless formulation
* Similarity solution
* Free boundary
* Non-linearity
* Maximum principle

### 3. Numerical Methods

The project uses the **Finite Difference Method** to obtain numerical approximations.

The following schemes are studied:

* Forward Euler Scheme
* Crank-Nicolson Scheme

### 4. Numerical Analysis

The numerical part investigates the Stefan problem under different boundary conditions, including:

* Constant boundary condition
* Time-dependent boundary condition
* Numerical approximation of the moving boundary
* Comparison of numerical results
* Error analysis

## Methodology

The study begins with the physical description of heat transfer and phase change. The governing heat equation and Stefan condition are then formulated for a one-dimensional melting problem.

A similarity transformation is used to obtain an analytical solution. The problem is subsequently discretized using finite difference techniques, and numerical approximations are obtained using Forward Euler and Crank-Nicolson schemes.

The numerical results are analyzed to understand the behavior of the temperature distribution and moving phase boundary, followed by an analysis of the approximation error.

## Project Structure

```text
Stefan-Problem-Theory-and-Numerical-Methods/
│
├── README.md
├── Report/
│   └── Stefan_Problem_Project_Report.pdf
│
├── Numerical_Methods/
│   ├── Forward_Euler/
│   └── Crank_Nicolson/
│
├── Results/
│   ├── Figures/
│   └── Numerical_Results/
│
└── References/
```

*The folder structure can be adjusted according to the files uploaded to the repository.*

## Key Concepts

* Heat Equation
* Phase Change
* Free Boundary Problem
* Stefan Condition
* Similarity Solution
* Error Function
* Finite Difference Method
* Forward Euler Method
* Crank-Nicolson Method
* Maximum Principle
* Numerical Error Analysis

## Project Outcome

The project provides a combined theoretical and numerical understanding of the Stefan Problem. The analytical formulation helps explain the behavior of the temperature field and moving boundary, while numerical methods provide approximations for cases where obtaining an explicit solution is difficult.

Bachelor of Science in Mathematics
Farook College (Autonomous), Kozhikode
