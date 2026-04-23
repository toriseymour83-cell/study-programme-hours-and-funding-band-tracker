# Study Programme Hours and Funding Band Tracker
## Overview

This project recreates a timetable-based calculator I originally built to help staff work out students’ planned learning hours and assign them to the correct funding band.

The original process was manual and time-consuming. Staff needed to total the number of hours each student would study across the academic year, but this was difficult to calculate consistently when students had different subjects, different session combinations, and different timetable patterns.

To solve this, I created an interactive timetable spreadsheet. Staff selected sessions from drop-down lists in a weekly timetable, and formulas in the background counted the number of taught sessions, applied the correct session lengths, and calculated the student’s total planned hours across the year. This made the process quicker, easier to check, and more consistent, while giving management a clearer overview of student hours, funding bands, and expected income.

This project shows both:

- the original Excel-based operational tool
- how I would redesign the process now using more structured data and reporting methods

## Project aims
- recreate the original timetable and hours calculator
- calculate weekly and annual planned hours
- assign funding bands based on total hours
- create a summary view for management reporting
- show how the same process could be modernised using data analysis tools

## Project structure
- excel/ for the recreated timetable calculator
- data/ for sample input and output files
- sql/ for any SQL logic used in the modern version
- src/ for Python scripts
- docs/ for screenshots or supporting notes

## Planned features

### Original version
- weekly timetable input
- drop-down subject selection
- automatic session hour calculations
- annual hours total
- funding band assignment
- student summary sheet

### Modern version
structured source data
automated transformation logic
cleaner summary outputs
reporting by student, band, and cohort
dashboard or visual summary


## Notes

### This project uses sample data only and does not contain any real student records.

## Status

In progress
