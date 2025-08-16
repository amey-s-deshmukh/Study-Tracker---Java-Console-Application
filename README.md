# Study Tracker

A simple and efficient Java console application to track your study sessions and generate reports.

## Features

- **Add Study Logs**: Record study sessions with date, subject, duration, and description
- **View All Logs**: Display all recorded study sessions in a formatted table
- **Summary Reports**: Generate summaries by date or subject
- **CSV Export**: Export all study data to a CSV file for external analysis
- **User-Friendly Interface**: Simple menu-driven console interface

## Project Structure

```
Study Tracker/
├── src/
│   └── main/
│       └── java/
│           └── StudyTracker.java
├── docs/
│   └── README.md
├── output/
│   └── .gitkeep
├── .gitignore
├── README.md
└── LICENSE
```

## How to Run

### Prerequisites
- Java 8 or higher
- Any text editor or IDE

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/study-tracker.git
   cd study-tracker
   ```

2. Compile the Java file:
   ```bash
   javac src/main/java/StudyTracker.java
   ```

3. Run the application:
   ```bash
   java -cp src/main/java StudyTracker
   ```

## Usage

1. **Insert Study Log**: Choose option 1 to add a new study session
   - Enter subject name (e.g., Java, C++, Data Structures)
   - Enter study duration in hours
   - Provide a description of what you studied

2. **View All Logs**: Choose option 2 to see all recorded study sessions

3. **Summary by Date**: Choose option 3 to see total study time grouped by date

4. **Summary by Subject**: Choose option 4 to see total study time grouped by subject

5. **Export to CSV**: Choose option 5 to save all data to a CSV file

6. **Exit**: Choose option 6 to close the application

## Sample Output

```
----------------------------------------------------
--Welcome to Study Tracker Application --
----------------------------------------------------
Please select the appropriate option
1 : Insert new Study Log into Database
2 : View All Study Logs
3 : Summary of Study Log by Date
4 : Summary of Study Log by Subject
5 : Export Study Log to CSV file
6 : Exit the application
```

## Data Storage

- Study logs are stored in memory during the application session
- Data can be exported to CSV format for permanent storage
- CSV files are saved as `StudyTracker.csv` in the project directory

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Your Name** - *Initial work* - [YourGitHub](https://github.com/yourusername)

## Acknowledgments

- Built as a learning project for Java programming
- Simple and beginner-friendly code structure
- Easy to understand and modify 