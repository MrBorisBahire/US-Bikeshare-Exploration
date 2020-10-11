## 11th October 2020

# **US Bikeshare Exploration Project**

## **Description:**
This project was focusing on using Python to explore data related to the US bike share system for three major cities in the United States: Chicago, New York City, and Washington.
- The source code used from the raw input from the user to create an interactive experience.
- And depending of the input the code imports the data and provides information by computing descriptive statistics. Do not hesitate to contribute to it in case you would like to.

## **Files used:**
* bikeshare.py

## **Credits:**
* Kalle Hallden
    - [https://github.com/KalleHallden](https://github.com/KalleHallden)
    - [https://twitter.com/KalleHallden](https://twitter.com/KalleHallden)
* Alexattia
      [https://github.com/alexattia](https://twitter.com/alexattia)

## **Softwares needed:**
* _Python 3, NumPy,_ and _Pandas_ installed using _Anaconda_
* A text editor, such as _Visual Studio Code_ or _Atom_.
* A terminal application (_Terminal_ on _Mac_ and _Linux_ or _Cygwin_ on _Windows_).

## **Installation links for softwares:**
* [Git for windows - for terminal application using Git Bash](https://gitforwindows.org/)
* [Python using Anaconda (latest version for windows)](https://www.anaconda.com/distribution/)
* [Atom Code Editor (for windows)](https://atom.io/)

## **Links for software tutorials used:**
* [Git - Reference](https://git-scm.com/docs)
* [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
* [Visual Studio Code Documentation](https://code.visualstudio.com/docs)

## **Code explained in Detail:**
### **How the program works:**
The code developed takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions change accordingly! There are four questions that act on changing the answers:

* Would you like to see data for _Chicago_, _New York_, or _Washington_?
* Would you like to filter the data by month, day, or not at all?
* (If they chose month) Which month - _January_, _February_, _March_, _April_, _May_, or _June_?
* (If they chose day) Which day - _Monday_, _Tuesday_, _Wednesday_, _Thursday_, _Friday_, _Saturday_, or _Sunday_?

The answers to the questions above determine the city and timeframe on which you do data analysis. After filtering the dataset, users see the statistical result of the data, and choose to start again or exit.

### **The Datasets:**
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

* Start Time (e.g., 2017-01-01 00:07:57)
* End Time (e.g., 2017-01-01 00:20:53)
* Trip Duration (in seconds - e.g., 776)
* Start Station (e.g., Broadway & Barry Ave)
* End Station (e.g., Sedgwick St & North Ave)
* User Type (Subscriber or Customer)

The _Chicago_ and _New York City_ files also have the following two columns:

* Gender
* Birth Year

### **Statistics Computed:**
The code helps user to tell about bike share use in _Chicago_, _New York City_ and _Washington_ by computing a variety of descriptive statistics. In this project, the code output will provide the following information:

* Popular times of travel (i.e., occurs most often in the start time):

  - most common month
  - most common day of week
  - most common hour of day

* Popular stations and trip:

  - most common start station
  - most common end station
  - most common trip from start to end (i.e., most frequent combination of start station and end station)

* Trip duration:

  - total travel time
  - average travel time

* User info:

  - counts of each user type
  - counts of each gender (only available for _NYC_ and _Chicago_)
  - earliest, most recent, most common year of birth (only available for _NYC_ and _Chicago_)
