![Module_Three_Documentation](https://github.com/hannab8/Module_Three_Documentation/assets/83167499/20fb736b-afa4-4816-af68-38825f1d4e57)
# Module Three: Documentation

## Introduction
In this third module, you will be introduced to maintaining proper documentation within your code and on GitHub. This is important in the lab and in any situation where you will be tasked with coding. The team leads will be reviewing code before it gets pushed, but it must be properly documented before this is done. The reason we want to emphasize the importance of this is so that other students, including yourself, can always go back and understand what your code does and why it does it.

Our team uses C++ and/or Python for our projects. If you are not familiar with these, some references on each will be provided below. We suggest that you follow a tutorial on either one to get more comfortable with coding using one of those languages.

## Module Readings

Please read through the following articles and complete the assignment below.

1. [Documentation 1](https://www.codium.ai/blog/how-to-write-great-code-documentation-best-practices-and-tools/)
2. [Documentation 2](https://herothemes.com/blog/how-to-write-documentation/)
3. [Commenting Code](https://stackoverflow.blog/2021/12/23/best-practices-for-writing-code-comments/)

This is a simple example of how the Readme file on your project should look. Diagrams and charts are highly encouraged to be included, as this will provide the reader a better understanding of what you are explaining.

<img width="1229" alt="Screen Shot 2023-08-04 at 4 26 06 PM" src="https://github.com/hannab8/Module_Three_Documentation/assets/83167499/41a6be41-5ec8-4e2a-ae5e-f4e427c496b7">

The takeaway from this is that good documentation is an ongoing effort, and it's crucial to invest time and effort into maintaining and updating it as you progress. Well documented code can improve your productivity and effectiveness, and contribute to the long-term success of your projects.

**Note**: If you ever need help with documentation, please feel free to ask a team lead or faculty member.

## Assignment

```
1.  Sign into your GitHub Account.

2.  Go to your repository: <YourName>_Training_Modules

3.  Edit your Readme file and format it using the following:
      - Please use a 5 line gap after the previous assignment
      - The first line: "<YourName> Module Three" using H1 (header one)
      - The third line: "Answers:" using H2 (header two)
      - The fifth line: Start an ordered List (1.)

4.  Copy and paste the code below into your repository. Use the proper markup for code in your Readme. (Hint: ```code```). Review and add comments to the code that tells the reader what it does.

PYTHON:

if __name__ == "__main__":
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))
    num3 = float(input("Enter the third number: "))
    num4 = float(input("Enter the fourth number: "))

    average = (num1 + num2 + num3 + num4) / 4

    print(f"The average of {num1}, {num2}, {num3}, and {num4} is: {average:.2f}")

C++:

#include <iostream>

int main() {
    float num1, num2, num3, num4;

    std::cout << "Enter the first number: ";
    std::cin >> num1;
    std::cout << "Enter the second number: ";
    std::cin >> num2;
    std::cout << "Enter the third number: ";
    std::cin >> num3;
    std::cout << "Enter the fourth number: ";
    std::cin >> num4;

    float average = (num1 + num2 + num3 + num4) / 4;

    std::cout << "The average of " << num1 << ", " << num2 << ", " << num3 << ", and " << num4 << " is: " << std::fixed << std::setprecision(2) << average << std::endl;

    return 0;
}

5.  Create a simple program in python or C++ where you add the sum of two numbers and determine if the sum is odd or even.
      - Remember to use appropriate naming conventions for your functions and variables.
      - You can type the code in your own IDE and paste it into your Readme.
      - Comment the code (preferrably before pasting it into your Readme).
      - See example below for how it should look.

6.  Commit your changes by clicking the 'Commit changes...' button and set the commit message to "Completed Task Three"
```
**Example for Question 5**
<img width="1071" alt="Screen Shot 2023-08-04 at 5 24 50 PM" src="https://github.com/hannab8/Module_Three_Documentation/assets/83167499/56b38ed2-bbb2-4200-ba7e-3076f0e9d163">


## References

### C++
1. [Style Guide | Google](https://google.github.io/styleguide/cppguide.html#Comments)
2. [Other References](https://en.cppreference.com/w/)

### Python
1. [Python Documenting | Real Python](https://realpython.com/documenting-python-code/)
2. [Style Guide | PEP 8](https://peps.python.org/pep-0008/)
3. [Style Guide | Google](https://google.github.io/styleguide/pyguide.html)
4. [Docstrings | PEP 257](https://peps.python.org/pep-0257/)

### Other
1. [FreeCodeCamp | Good Documentation](https://www.freecodecamp.org/news/how-to-write-good-documentation/)
