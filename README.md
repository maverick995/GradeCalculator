# **Grade Calculator**

A simple JavaScript program to calculate class averages, determine letter grades, and assess whether a student has passed or failed a course based on their score. This project demonstrates core JavaScript concepts such as loops, functions, and conditional statements.

---

## **Features**
- **Calculate Class Average**: Computes the average score of a given list of scores.
- **Letter Grade Conversion**: Converts numerical scores into letter grades (A++, A, B, C, D, or F).
- **Passing Grade Check**: Evaluates if a score is passing (grade not "F").
- **Personalized Messages**: Outputs a detailed message indicating the class average, the student's grade, and their pass/fail status.

---

## **How to Use**

### Prerequisites
- Install [Node.js](https://nodejs.org/) to run the program locally.

### Steps to Run
1. Clone or download this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/GradeCalculator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd GradeCalculator
   ```
3. Run the JavaScript file using Node.js:
   ```bash
   node grades.js
   ```
4. Modify the input arrays and scores in the `console.log` statements to test different cases.

---

## **Example Usage**

### Code
```javascript
console.log(studentMsg([92, 88, 12, 77, 57, 100, 67, 38, 97, 89], 37));
// Output: "Class average: 71.7. Your grade: F. You failed the course."

console.log(studentMsg([56, 23, 89, 42, 75, 11, 68, 34, 91, 19], 100));
// Output: "Class average: 50.8. Your grade: A++. You passed the course."
```

### Output
```
Class average: 71.7. Your grade: F. You failed the course.
Class average: 50.8. Your grade: A++. You passed the course.
```

---

## **Technologies Used**
- JavaScript (ES6+)
- Node.js (for running the program locally)

---

## **Applications**
This code can be utilized in various ways, including:
- As a backend utility for a gradebook application.
- As a simple grading tool for educational purposes.
- As a portfolio project to demonstrate JavaScript programming skills.

---

## **Future Enhancements**
- Add support for dynamic user input (e.g., through a command-line prompt or a web interface).
- Extend grading criteria for more complex systems.
- Integrate into a full-fledged gradebook app with a database.

---

## **License**
This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to contribute to this repository by submitting issues or pull requests!

