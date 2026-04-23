# Study Programme Hours and Funding Band Tracker
## Overview

This project recreates a timetable-based tool I originally built to calculate planned annual learning hours and assign students to the correct funding band.

The original problem was that staff needed to work out how many hours each student was scheduled to study over the academic year, because funding depended on those planned hours. This was being done manually, which was slow, confusing, and difficult to check. Teachers were finding it hard to total the hours accurately, especially when students had different subjects, session lengths, and timetables.

To make the process easier, I created an interactive spreadsheet where staff could select a student’s subjects and sessions from a weekly timetable using drop-down lists. The spreadsheet then automatically calculated the weekly hours, multiplied them across the academic year, and gave a total planned hours figure. This made the process much quicker, reduced confusion, and gave management a clearer view of which funding band each student fell into.

I am using this project to show both:

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
