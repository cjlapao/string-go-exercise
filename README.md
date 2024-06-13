# Problem Statement: CSV String to Array Conversion

## Objective

This task involves writing a program that can read a CSV (Comma Separated Values) string, convert it into an array, and display its contents with a summary. 
You will need to implement this solution in the requested language.

## Instructions

1. Input:
    * A single CSV string will be provided as input. The CSV string will contain multiple rows of data, with each row separated by a newline character (\n) and each column in a row separated by a comma (,)
2. Output:
    * The output should be an array of arrays, where each inner array represents a row of the CSV data. Display this array in a readable format.
    * You should have a count of how many rows you were able to import
3. Steps to Follow:
    * Read the CSV string.
    * Split the string by newline characters to get individual rows.
    * Split each row by commas to get individual columns.
    * Store the rows and columns in an array of a structure that contains the data imported.
    * Display the nested array.

## Example

### Input

```
	"name,age,city\nJohn,23,New York\n\n\nJane,29,Los Angeles\nDoe,22,Chicago\nYan”,” tar,24,Seattle”
```

### Output:

```
Name | Age | City
John |23 | New York
Jane | 29 | Los Angeles
Doe | 22 | Chicago
Yan, Tar | 24 | Seattle
—
Imported 4 rows
```

## Requirements

* Language: Implement the solution in Go.
* Edge Cases: Consider edge cases such as empty rows, different number of columns, and improper formatting. Handle these cases gracefully.

## Tips

* Use string manipulation functions to split and process the input CSV string.
* Ensure your code is clean and well-commented to help others understand your logic.
* Test your code with different CSV strings to ensure it works as expected.

## Submission

Push your solution to this repository, try to use a separate folder for your solution.

## Materials

You can use the following resources to help you with this task:

[Go Documentation](https://go.dev/doc/tutorial/getting-started)

or any other open source documentation you can find online.

Happy coding!