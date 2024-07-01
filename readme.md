# Lesson Lineup

> A comprehensive timetable management system in Python, facilitating efficient allocation of lectures to batches while adhering to specified constraints.

## Inspiration

From school days, I've seen that scheduling time table for different batches manually has been a very challenging process. In order to streamline that process, I had an idea which took the shape of this project.

## Technology

![Python3](https://img.shields.io/badge/python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)![Jupyter](https://img.shields.io/badge/jupyter-%23F37626.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## Usage

### Requirements

- python 3.10
- jupyter

### Instructions

1. A preprocessing file named preprocessing.ipynb sorts the teachers and batches based on the constraints.

   **Note:** Ensure that your constraint file lies in the same directory, you have updated the name of your file in the code and then preprocess it. It will generate a file named `sorted_constraints.csv` in the same directory.

2. Then the file main.ipynb takes the file `sorted_constraints.csv` as input and provides a time table for every teacher and every batch in a separate file with their respective names in the same directory.

   **Note:** Ensure that you have updated the no. of days and no. of lectures per day as per your requirement while you instantiate ‘time table’ instance of TimeTable class.

> You can find example for the constraint files for the required format in the `examples` directory.
