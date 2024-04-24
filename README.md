# RomanNumeral Converter

The RomanNumeral Converter is a Java program that provides functionality to convert a string representing a Roman numeral into its equivalent integer value. The implementation follows the standard Roman numeral system where the letters I, V, X, L, C, D, and M represent 1, 5, 10, 50, 100, 500, and 1000, respectively.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The project is managed with Maven and requires:

- Java 1.8 or higher
- Maven 3.6.0 or higher

### Installing

Clone the repository to your local machine:

```bash
git clone [repository-url]
```

Navigate to the project directory:

```bash
cd romantoint
```

Build the project with Maven:

```bash
mvn clean install
```

### Running the tests

The unit tests can be run with the following command:

```bash
mvn test
```

This command will execute the tests defined in `RomanNumeralTest.java`.

## Usage

To use the `RomanNumeral` class in your code, simply create an instance of it and call the `romanToInt` method with a Roman numeral string as the argument.

Example:

```java
RomanNumeral rn = new RomanNumeral();
int number = rn.romanToInt("IX");
System.out.println(number); // Outputs 9
```

