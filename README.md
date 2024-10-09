<div align="center">
  <img src="https://img.icons8.com/?size=512&id=13441&format=png" alt="Python Logo" />
</div>

# 👨🏽‍🏫 Python Basics for Data Science:

This notebook introduces essential Python concepts for Data Science, covering control flow structures, data manipulation using lists and dictionaries, and providing practical examples that prepare students for data analysis tasks.

## 📜 Overview

- ## Working with Libraries

  In this course, we learned how to work with libraries, covering how to install and import them, as well as how to utilize their packages. We practiced these skills with Matplotlib, a powerful library for data visualization.

- ## Functions

  We explored Python's built-in functions, understanding what they are and how to use them effectively. Additionally, we created our own functions, with and without parameters, including anonymous functions and those with return values, while also mapping some of their outputs.

- ## Complex Data Structures

  We worked with compound data structures, such as lists of lists and lists of tuples, understanding their differences and the best use cases for each. At this point, we covered list comprehensions as a way to create lists with specific patterns or conditions, and applied similar concepts to dictionaries using dictionary comprehensions.

- ## Exception Handling
  We learned how to identify and handle exceptions, utilizing try...except, else, and finally clauses. This section also covered creating custom exceptions to manage unwanted behaviors, like invalid user input.

## 📜 Other Key Concepts

- ## Conditional Structures

  Conditional structures (if, elif, else) are fundamental tools for decision-making in Python. In the context of Data Science, they are used to apply different treatments to data based on its characteristics. Examples in this notebook include classifying grades based on specified ranges.

- ## Loops

  Loops (while and for) are useful for automating repetitive tasks, such as processing data and iterating over large data sets:

  - `while`: Ideal for scenarios where the exact number of iterations is unknown and we want to repeat until a condition is met.
  - `for`: Used to iterate over lists, dictionaries, or ranges of values, allowing systematic analysis of elements, such as data stored in collections.

- ## Data Structures for Manipulation:

  Data Science involves intensive data manipulation. This notebook introduces basic structures for these tasks:

  - `Lists`: Store ordered sets of data and allow easy manipulation, such as adding and removing elements. Examples include storing lists of numbers and calculating averages.
  - `Dictionaries`: Store data in key-value pairs, useful for representing relational data. In this notebook, dictionaries are used to represent student information, allowing easy access and modification of specific attributes.

- ## Data Manipulation Methods:

  With lists and dictionaries, the notebook explores various manipulation methods such as:

  - `Lists`: append(), extend(), remove(), and slicing with indices. These methods are useful for organizing and filtering data.
  - `Dictionaries`: pop(), items(), keys(), and values() for accessing and updating information, a fundamental concept when working with data that has multiple characteristics.

- ## Applications in Data Science:

  These basic concepts form the foundation of many operations in Data Science, such as:

  - Data Preprocessing: Conditional structures and loops are used for data cleaning and preparation.
  - Data Exploration: for loops and lists help iterate over columns and records for descriptive analysis.
  - Data Transformation: List and dictionary methods enable organizing and transforming data sets, essential for subsequent analysis.

- ## Learning Objectives

  - Understand the use of conditionals to apply business logic in data analysis.
  - Use loops to iterate over large data sets.
  - Manipulate lists and dictionaries to organize, access, and modify data.
  - Familiarize with basic Python methods to organize and transform data into a format suitable for analysis.

- ## Requirements

  **[Jupyter Notebook](https://jupyter.org/try) or [Google Colab](https://colab.research.google.com)**: Recommended for running the code. Google Colab is a free, online notebook environment with no local setup required. (Visit the link for more details.)

- ## Running on Venv

  To run the notebook locally using a virtual environment:

  1. Create and Activate the Virtual Environment:

     ```
         python -m venv <name of your virtual environment>
     ```

  2. Activate the Virtual Environment:

     - **Windows**:
       ```bash
           <name of your virtual environment>\Scripts\activate
       ```
     - **Linux/macOS**:
       ```bash
           source <name of your virtual environment>/bin/activate
       ```

  3. Install Dependencies:
     ```bash
         pip install -r requirements.txt
     ```
  4. Open the Notebook in VSCode:

  - With the Jupyter extension installed, open the .ipynb file directly in VSCode.
  - When you open the notebook, choose the kernel associated with your virtual environment:

    - Click on the kernel name at the top right of the notebook (where something like “Python 3.x” usually appears).

    - Select the virtual environment you have just created, ensuring that the notebook uses that environment.

  5.  Run the Cells:

      - Use the execute buttons on the VSCode or Shift + Enter to execute each cell in the notebook.

  6.  Deactivate the Virtual Environment when done:
      - Close the notebook and deactivate the environment in the terminal, if necessary:
        ```bash
            deactivate
        ```

---

This material is an ideal starting point for those who want to build a solid foundation of Python for Data Science, providing essential tools for initial data manipulation and analysis.
