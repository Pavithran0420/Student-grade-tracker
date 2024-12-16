

# Student Grade Tracker

## Overview

The **Student Grade Tracker** is a simple Python application that allows teachers or administrators to manage and track students' grades. Users can add new students, input grades for them, and display student details along with the calculated average grade.

This project is designed to be interactive, running in the command line and providing an easy-to-use menu for tracking and managing student information. It's ideal for small-scale grade management and can be extended for larger use cases with additional features.

## Features

- **Add New Students**: Allows users to input a student's name and create a record.
- **Add Grades**: Users can input multiple grades for each student, one at a time.
- **Calculate Average Grade**: The program automatically calculates and displays the average grade for each student.
- **View Student Information**: Displays a student's name, list of grades, and their average grade.
- **Interactive Menu**: Users can select from a set of options to add students, add grades, or display information.
  
## Requirements

To run the project, you will need:

- Python 3.x (Tested with Python 3.7+)
  
## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/student-grade-tracker.git
   cd student-grade-tracker
   ```

2. **Run the Program**:
   Execute the script in your terminal:
   ```bash
   python grade_tracker.py
   ```

3. **Menu Options**:
   The program will display a simple menu with the following options:
   - `1. Add New Student`: Input a new student's name.
   - `2. Add Grades for a Student`: Add grades for an existing student.
   - `3. Display Student Info`: View details and grades of a student.
   - `4. Exit`: Exit the program.

4. **Add Grades**: When adding grades, you can input numeric values for the grades, or type any non-numeric input to stop adding grades for that student.

## Example Usage

```bash
Student Grade Tracker
1. Add New Student
2. Add Grades for a Student
3. Display Student Info
4. Exit
Enter your choice: 1
Enter student's name: John Doe
Student John Doe added successfully!

Student Grade Tracker
1. Add New Student
2. Add Grades for a Student
3. Display Student Info
4. Exit
Enter your choice: 2
Enter student's name: John Doe
Enter grade for John Doe: 85
Enter grade for John Doe: 90
Enter grade for John Doe: 78
Enter grade for John Doe: done

Student Grade Tracker
1. Add New Student
2. Add Grades for a Student
3. Display Student Info
4. Exit
Enter your choice: 3
Enter student's name to view info: John Doe
Student: John Doe
Grades: [85.0, 90.0, 78.0]
Average Grade: 84.33
```

## Contributing

Feel free to fork the repository and submit pull requests for improvements or bug fixes. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Notes:

- Make sure to replace `your-username` with your actual GitHub username in the clone URL.
- You can expand the "Contributing" section with more guidelines if you want to make the repository collaborative.
- Feel free to adjust the example usage or any other details based on your specific needs.

Let me know if you'd like to add anything else!
