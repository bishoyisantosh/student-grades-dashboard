# Student Grades Dashboard

Simple project that reads `data/students.csv`, computes total, percentage and grade per student, and generates `report.html` styled with `web/styles.css`.

## How to run (on your desktop)
1. Make sure you have Java 8+ installed.
2. From project root:
   - Compile:
     ```
     javac -d out src/GradeProcessor.java
     ```
   - Run:
     ```
     java -cp out GradeProcessor
     ```
3. After successful run, open `report.html` in your browser.

## Files
- `data/students.csv` - input CSV (Name,Roll,Math,Science,English)
- `src/GradeProcessor.java` - Java program that generates `report.html`
- `web/styles.css` - CSS for the report
- `web/template_fallback.html` - optional static example
