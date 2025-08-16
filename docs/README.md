# Study Tracker - Technical Documentation

## Overview

Study Tracker is a Java console application designed to help students and learners track their study sessions. The application provides a simple interface for logging study activities and generating various reports.

## Architecture

### Classes

#### 1. StudyLog
- **Purpose**: Represents a single study session
- **Attributes**:
  - `Date`: LocalDate - The date of the study session
  - `Subject`: String - The subject being studied
  - `Duration`: double - Study duration in hours
  - `Description`: String - Description of what was studied

#### 2. StudyTracker
- **Purpose**: Main business logic class that manages study logs
- **Key Methods**:
  - `InsertLog()`: Adds a new study log
  - `DisplayLog()`: Shows all study logs
  - `SummaryByDate()`: Groups study time by date
  - `SummaryBySubject()`: Groups study time by subject
  - `ExportCSV()`: Exports data to CSV format

#### 3. StudyTracker (Main Class)
- **Purpose**: Entry point and user interface
- **Features**: Menu-driven console interface

## Data Structures Used

1. **ArrayList<StudyLog>**: Stores all study logs in memory
2. **TreeMap<LocalDate, Double>**: For date-wise summaries
3. **TreeMap<String, Double>**: For subject-wise summaries

## File Operations

- **CSV Export**: Creates `StudyTracker.csv` file
- **Data Format**: Date, Subject, Duration, Description
- **CSV Handling**: Automatically escapes commas in text fields

## Error Handling

- Empty database checks before operations
- Try-catch blocks for file operations
- User-friendly error messages

## Future Enhancements

1. **Database Integration**: Replace in-memory storage with database
2. **GUI Interface**: Create graphical user interface
3. **Data Persistence**: Save data between sessions
4. **Advanced Analytics**: Charts and graphs
5. **Goal Setting**: Set study goals and track progress
6. **Reminders**: Study schedule reminders

## Code Quality

- Simple and readable code structure
- Beginner-friendly implementation
- Well-commented code
- Consistent naming conventions
- Modular design

## Performance Considerations

- In-memory storage for small datasets
- Efficient TreeMap usage for summaries
- Minimal file I/O operations 