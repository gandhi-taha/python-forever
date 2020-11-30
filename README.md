# Python-Forever
<table>

<tr><td>

|   Modules  | Topics                                                    |
|-----------|:------------------------------------------------------------------------------------------------------------- |
|  01  | [Introduction](./readme.md)
|  02   |  [Data Types](./02_Day_Data_types/02_day_data_types.md)  |
|  03   |  [Booleans, Operators, Date](./03_Day_Booleans_operators_date/03_booleans_operators_date.md)  |
|  04   |  [Conditionals](./04_Day_Conditionals/04_day_conditionals.md)  |
|  05   |  [Arrays](./05_Day_Arrays/05_day_arrays.md)  |
|  06   |  [Loops](./06_Day_Loops/06_day_loops.md) |
|  07   |  [Functions](./07_Day_Functions/07_day_functions.md)  |
|  08   |  [Objects](./08_Day_Objects/08_day_objects.md)     |
|  09   |  [Higher Order Functions](./09_Day_Higher_order_functions/09_day_higher_order_functions.md)   |
|  10   |  [Sets and Maps](./10_Day_Sets_and_Maps/10_day_Sets_and_Maps.md)  |
|  11   |  [Destructuring and Spreading](./11_Day_Destructuring_and_spreading/11_day_destructuring_and_spreading.md)    |
|  12   |  [Regular Expressions](./12_Day_Regular_expressions/12_day_regular_expressions.md)   |
|  13   |  [Console Object Methods](./13_Day_Console_object_methods/13_day_console_object_methods.md)|
|  14   |  [Error Handling](./14_Day_Error_handling/14_day_error_handling.md) |
|  15   |  [Classes](./15_Day_Classes/15_day_classes.md)  | 

</td><td>

|   Modules  | Topics                                                    |
|-----------|:------------------------------------------------------------------------------------------------------------- |
|  16   |  [Python Date time](./16_module_Python_date_time/16_python_datetime.md)      |     
|  17   |  [Exception Handling](./17_module_Exception_handling/17_exception_handling.md)|    
|  18   |  [Regular Expressions](./18_module_Regular_expressions/18_regular_expressions.md)|    
|  19   |  [File Handling](./19_module_File_handling/19_file_handling.md)   |
|  20   |  [Python Package Manager](./20_module_Python_package_manager/20_python_package_manager.md)    |
|  21   |  [Classes & Objects](./21_module_Classes_and_objects/21_classes_and_objects.md)      |
|  22   |  [Web Scraping](./22_module_Web_scraping/22_web_scraping.md)      |
|  23   |  [Virtual Environment](./23_module_Virtual_environment/23_virtual_environment.md)|
|  24   |  [Statistics](./24_module_Statistics/24_statistics.md)      |
|  25   |  [Pandas](./25_module_Pandas/25_pandas.md)     |
|  26   |  [Python web](./26_module_Python_web/26_python_web.md)    |
|  27   |  [Python with MongoDB](./27_module_Python_with_mongodb/27_python_with_mongodb.md)     |
|  28   |  [API](./28_module_API/28_API.md)     |
|  29   |  [Building API](./29_module_Building_API/29_building_API.md)     |
|  30   |  [Conclusions](./30_module_Conclusions/30_conclusions.md)      |

</td></tr> </table>

<center>Enjoy Coding 😇️ </center>
<div align="center">
<h1> Python Forever: Module 01 - Introduction </h1>
 <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/taha-gandhi-5525b1160">
  <img alt="Linkedin Follow" src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/gandhi_taha">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/gandhi_taha?style=social">
  </a>
  </div>
<br>

## Module 01

- [ Python Forever](#Python-Forever)
  - [Welcome](#Hello-and-Welcome-Guys)
  - [Introduction](#introduction)
  - [Why Python ?](#why-python-)
  - [Environment Setup](#environment-setup)
    - [Installing Python](#installing-python)
    - [Python Shell](#python-shell)
    - [Installing Visual Studio Code](#installing-visual-studio-code)
      - [How to use visual studio code](#how-to-use-visual-studio-code)
  - [Basic Python](#basic-python)
    - [Python Syntax](#python-syntax)
    - [Python Indentation](#python-indentation)
    - [Comments](#comments)
    - [Data types](#data-types)
      - [Number](#number)
      - [String](#string)
      - [Booleans](#booleans)
      - [List](#list)
      - [Dictionary](#dictionary)
      - [Tuple](#tuple)
      - [Set](#set)
    - [Checking Data types](#checking-data-types)
    - [Python File](#python-file)
  - [ Practice - 01](#-exercises---day-1)
    - [Practice: Level 1](#exercise-level-1)
    - [Practice: Level 2](#exercise-level-2)
## Hello and Welcome Guys

**Cheers** for opting to this course _Python Forever_. In this module you will learn from scratch about in and out of python with challenges to solve at end.

**You can even join us our online  Python Course training that will help you gain in-depth knowledge on all the essential concepts**  <br>[Join Now](Whatsapp link to add)

## Introduction
 Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.
 Python is a high-level programming language for general-purpose programming. It is open source.This python course will help you learn the latest version of Python 3, in a step by step fashion.

 It is used for:

- web development (server-side),
- software development,
- mathematics,
- system scripting.

## Why Python? 

The python language is one of the most accessible programming languages available because it has simplified syntax and not complicated, which gives more emphasis on natural language. Due to its ease of learning and usage, python codes can be easily written and executed much faster than other programming languages. Python is highly embraced language in the data science and machine learning community. I hope this is enough to convince you to start learning python.

## Environment Setup

### Installing Python
To work with python we need to install python. So let's [download](https://www.python.org/downloads/)
python click appropriate flavour of script to your O.S.
[![Installing of Pc](./images/download.png)](https://www.python.org/downloads/)
If you are on a linux machine. Follow these commands on Debian:
```shell
sudo apt-get update
```
```shell
sudo apt install build-essential zlib1g-dev \
libncurses5-dev libgdbm-dev libnss3-dev \
libssl-dev libreadline-dev libffi-dev curl
```
```shell
sudo apt-get install python3 -y
```
Verify the installation
```shell
python3 --version
```
![Python Version](./images/python_version.png)

We can see on terminal, It shows us we are using _python 3.8.5_, If you mange to see the python version, well done. Python has been installed on your machine.
<br>

### Python Shell

Python is an interpreted scripting language, so it doesn't got to be compiled. It means it executes the code line by line. Python comes with a _Python Shell (Python Interactive Shell)_. It's wont to execute one python command and obtain the result.

Python Shell waits for the python code from the user. Once you enter the code, It interprets the code and shows the end in subsequent line.
Open your terminal or command prompt(cmd) and write:
```shell
python3
```
![Python Scripting Shell](./images/python3.png)

Python has two basic modes: script and interactive. The normal mode is the mode where the scripted and finished . py files are run in the Python interpreter. Interactive mode is a command line shell which gives immediate feedback for each statement, while running previously fed statements in active memory.

Let write our very first script on this interactive python shell.

![Python Interactive shell](./images/interactive_shell.png)

Well done, you wrote your first python script on python interactive shell. How do we close this shell ? To exit write **exit()** on shell.

![Exit on shell python](./images/exit_shell.png)
