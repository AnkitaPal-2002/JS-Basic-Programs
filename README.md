# JavaScript Utility Functions

## Overview

This project contains a set of JavaScript utility functions for solving common programming problems. The functions can be tested using the provided HTML page that allows user input for each function.

## Functions

### 1. `findMedian(arr)`

- **Description**: Finds the median of an array of numbers.
- **Usage**: The user can enter numbers (comma-separated) into an input box, and the function calculates the median.
- **Example Input**: `1, 2, 3, 4, 5`
- **Example Output**: `Median: 3`
- **How it Works**: Sorts the numbers, and if the count is odd, it returns the middle value. If even, it returns the average of the two middle values.

### 2. `removeDuplicates(arr)`

- **Description**: Removes duplicate elements from an array while preserving the order.
- **Usage**: The user enters numbers (comma-separated), and the function returns a new array without duplicates.
- **Example Input**: `1, 2, 2, 3, 4, 4`
- **Example Output**: `Array without duplicates: [1, 2, 3, 4]`
- **How it Works**: Filters the array, keeping only the first occurrence of each number.

### 3. `insertIntoArray(arr, val, n)`

- **Description**: Inserts a specified value at every nth position in an array.
- **Usage**: The user provides an array, a value to insert, and the interval `n`.
- **Example Input**: Array: `1, 2, 3, 4`, Value: `9`, Interval: `2`
- **Example Output**: `Modified array: [1, 9, 2, 9, 3, 9, 4]`
- **How it Works**: Loops through the array and inserts the value at every `n`th position.

### 4. `replaceMostFrequentChar(str)`

- **Description**: Replaces all occurrences of the most frequent character in a string with `*`.
- **Usage**: The user inputs a string, and the function returns a new string with the most frequent character replaced.
- **Example Input**: `"hello"`
- **Example Output**: `"he**o"`
- **How it Works**: Counts character occurrences, identifies the most frequent character, and replaces it.

### 5. `hoursUntilEndOfDay(dateString)`

- **Description**: Calculates the number of hours until the end of the day from a given date-time.
- **Usage**: The user selects a date and time, and the function calculates the hours remaining until 11:59 PM of that day.
- **Example Input**: `2024-10-20T15:00:00`
- **Example Output**: `Hours until end of day: 8`
- **How it Works**: Sets the time to the end of the day and calculates the difference in hours.

### 6. `daysBetweenDates(date1, date2)`

- **Description**: Computes the number of days between two dates.
- **Usage**: The user selects two dates, and the function calculates the number of days between them.
- **Example Input**: Date 1: `2024-10-20`, Date 2: `2024-11-01`
- **Example Output**: `Days between dates: 12`
- **How it Works**: Converts dates to time values and calculates the absolute difference in days.

## How to Use

1. Copy the provided HTML and JavaScript code into a file named `index.html`.
2. Open `index.html` in a web browser.
3. Input values for each function as required and click the respective buttons to see the output.
4. The results for each function will be displayed on the page.


## Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge).
- Basic knowledge of HTML and JavaScript to modify or test functions if needed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## Author

- **Ankita Pal** - Initial work - (https://github.com/AnkitaPal-2002)

Feel free to reach out if you encounter any issues or have suggestions for improvements.

