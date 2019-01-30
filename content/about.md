---
title: "Course Description"
date: 2019-01-30T18:40:32+08:00
---

# Overview

Unlike most 101 courses, this course is designed soley for the purpose of getting someone pplying Python to their line of work. Key learning objectives include

- Working with Tabular Data (Pandas)
- Manipulating Excel Files (xlwings)
-

As such, it skimps on the fundamentals and teaches the bare minimum needed for one to get "dangerous with python"

For those more interested in understanding more about python, do enroll in this [free course](https://www.edx.org/course/introduction-to-computer-science-and-programming-using-python-0) on edX (money is needed for certification however.)

# Lesson 1 - Basics

> Numbers, Text and Variables
>
> Lists, Indexing

**Why learn this**

In programming, you will be manipulating real world objects (files, data in spreadsheet).

This data is represented via primitive data types such as

- numbers
- text

which are often bundled in collections like

- lists
- dictionaries.

Learning how to manipulate these will equip you with the skills to deal with real world data (which will be given to you in these forms)

# Lesson 2 - Decisions and Simple Functions

> Booleans and Decisions

**Why learn this**

People often liken programming to writing a recipe, where you are writing instructions for people to follow.

In recipes, you often note that there is some room for discetion. For example, you are allowed to vary

- the amount of ingredients depending on the number of people
- substitute ingredients that you don't have or don't like

Similarly, in programs you want to vary what code gets executed. A very simple example is if you're doing resume filtering

```
if gpa < 3.0:
    print("reject)
else:
    print("consider") 
```

> Functions

**Why learn this**

A lot of code has been written by other programmers. Instead of "re-inventing the wheel", I'll teach you how to use this code to

- do simple calculations
- open files
- manipulate files

I'll also teach you how to write your own functions.

# Lesson 3 - Iterations

> for loops, range(n), nested for loops

**Why learn this**

So far, what you've learnt is how to do something once. Very often, we turn to code because we want to repeat something, multiple times.

Lessons in this week will cover the ways in which iteration can be used to repeat the same piece of code, multiple times.

# Lesson 4 - Pandas

> Pandas
> 
> Series, DataFrames,
>
> Simple plotting 

**Why learn this**
A lot of data in the finance world in stuck in Excel. A lot of work in finance also involves manipulating this data, saving it (to the same file or another file).

Pandas is a library (set of functions) that makes dealing with tabular data easy.

# Lesson 5 - Replacing Excel with Python

> xlwings
>
> UDFS

**Why learn this**

Sometimes, the data that we are dealing with isn't tabular in data. Pandas, while able to handle Excel files, works best with data in tabular form.

In this week's lessons, I will teach you how to use `xlwings` to manipulate excel files, and how to write custom functions for excel, but in python

# Lesson 6 - Automation with Python

> apscheduler

**Why learn this**

One advantage that computers have over us is that they are capable of staying awake 24/7, and that they never forget to do something.

As such, it is useful to have a computer run something on a schedule.

> watchdog

It is also sometimes useful for computer to run s

> selenium

A lot of our work involves dealing with internal and external systems. Very often, these systems are accessed via websites. Selenium allows one to automate interactions with these systems.



