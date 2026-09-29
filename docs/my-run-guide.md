# Run Guide

## Prerequisites
- Python 3
- JDK 17 or newer, with `java` and `javac` on PATH
- Git, to clone this repository

## Run the demo
From the repository root, run:

    python3 run.py demo

## What the demo does
The demo runs the library loan system on a fixed date (2026-09-01).
It prints the borrowing limits for students and faculty, searches the
catalog for a title, borrows the book "Git Essentials" for a member
(Alex) with a 14-day due date, returns it, and shows the return fee
and the number of active loans afterwards.
