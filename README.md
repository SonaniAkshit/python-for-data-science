# Python for Data Science (Core Python Foundations)

This repository contains my structured Python learning path focused on building a **strong core foundation** before moving into **data science and machine learning**.

The goal of this repo is simple:
> Master core Python concepts with clean, organized notebooks that are easy to revise and reuse.

---

## 📂 Repository Structure
```
python-for-data-science/
├─ README.md
├─ 01_basics/
│  ├─ 01_introduction.ipynb
│  ├─ 02_variables_input_output.ipynb
│  ├─ 03_operators_keywords_datatypes.ipynb
│  ├─ 04_control_flow_and_loops.ipynb
│  └─ 05_quiz_basics_io_control_flow.ipynb
│
├─ 02_functions/
│  ├─ 01_function_basics_and_syntax.ipynb
│  ├─ 02_args_kwargs_and_scope.ipynb
│  ├─ 03_recursion_and_pass_statement.ipynb
│  ├─ 04_first_class_and_lambda_functions.ipynb
│  ├─ 05_map_filter_reduce_and_inner_functions.ipynb
│  ├─ 06_decorators.ipynb
│  └─ 07_quiz_functions.ipynb
│
├─ 03_data_structures/
│  ├─ 01_strings_and_lists.ipynb
│  ├─ 02_tuples_and_dictionaries.ipynb
│  ├─ 03_sets_arrays_and_comprehensions.ipynb
│  ├─ 04_collections_module_counters_heapq_deque.ipynb
│  ├─ 05_collections_module_ordered_default_dict.ipynb
│  └─ 06_quiz_core_data_structures.ipynb
│
├─ 04_oops/
│  ├─ 01_oop_introduction_classes_objects.ipynb
│  ├─ 02_inheritance_polymorphism_encapsulation.ipynb
│  ├─ 03_abstraction_and_iterators.ipynb
│  └─ 04_quiz_oop.ipynb
│
├─ 05_exception_and_file_handling/
│  ├─ 01_exceptions_and_error_types.ipynb
│  ├─ 02_built_in_and_user_defined_exceptions.ipynb
│  ├─ 03_file_handling_read_write.ipynb
│  ├─ 04_os_and_pathlib_and_directory_management.ipynb
│  └─ 05_quiz_exceptions_and_files.ipynb
│
├─ 06_database_handling/
│  ├─ 01_mysql_with_python.ipynb
│  ├─ 02_mongodb_with_python.ipynb
│  └─ 03_quiz_databases.ipynb
│
├─ 07_packages_and_libraries/
│  ├─ 01_working_with_packages_and_virtualenv.ipynb
│  ├─ 02_built_in_modules_overview.ipynb
│  ├─ 03_dsa_libraries_intro.ipynb
│  ├─ 04_gui_libraries_overview.ipynb
│  └─ 05_quiz_packages_and_modules.ipynb
│
└─ 08_python_packages_and_modules/
   ├─ example_package/
   │   ├─ __init__.py
   │   ├─ math_utils.py
   │   ├─ string_utils.py
   │   └─ helper/
   │        ├─ __init__.py
   │        └─ file_ops.py
   │
   ├─ using_imports_examples/
   │   ├─ import_basic.py
   │   ├─ import_from_package.py
   │   ├─ import_as_alias.py
   │   ├─ import_specific_functions.py
   │   └─ package_folder_structure.md
   │
   └─ README.md

```

### `01_basics/`
Core Python basics: installation, first script, input/output, variables, operators, data types and control flow.

Notebooks include:
- `01_introduction_and_setup.ipynb` — What is Python, where it is used, installing Python, running your first program.
- `02_variables_input_output.ipynb` — Variables, input(), print(), basic formatting.
- `03_operators_keywords_datatypes.ipynb` — Operators, keywords, core data types (int, float, bool, str, list, tuple, dict, set).
- `04_control_flow_and_loops.ipynb` — if/elif/else, for loops, while loops, break, continue.
- `05_quiz_basics_io_control_flow.ipynb` — Quiz notebook to test basics, I/O and control flow.

---

### `02_functions/`
Focus on writing reusable code with functions and understanding how Python handles arguments and scope.

Topics covered:
- Function syntax and definitions
- Parameters, return values
- Global vs local variables
- Recursion
- `*args` and `**kwargs`
- First class functions and `lambda`
- `map`, `filter`, `reduce`
- Inner functions and decorators
- Quiz on functions

---

### `03_data_structures/`
Covers Python’s built-in data structures and the `collections` module.j 

Topics covered:
- Strings and lists
- Tuples and dictionaries
- Sets and arrays
- List comprehensions
- `collections` module: `Counter`, `heapq`, `deque`, `OrderedDict`, `defaultdict`
- Quizzes for each group of structures

---

### `04_oops/`
Object-Oriented Programming in Python.

Topics covered:
- Classes and objects
- Encapsulation
- Inheritance
- Polymorphism
- Abstraction
- Iterators
- Quiz on OOP concepts

---

### `05_exception_and_file_handling/`
Error handling and working with the file system.

Topics covered:
- Exception handling (`try`, `except`, `else`, `finally`)
- Built-in exceptions
- User-defined exceptions
- File reading and writing
- Working with `os` and `pathlib`
- Directory management
- Quiz on exceptions & file handling

---

### `06_database_handling/`
Connecting Python with databases.

Topics covered:
- Working with MySQL from Python
- Working with MongoDB from Python
- Basic CRUD operations
- Quiz on database handling

---

### `07_packages_and_libraries/`
Overview of Python’s package ecosystem.

Topics covered:
- Installing and managing packages (`pip`, virtual environments)
- Built-in modules overview
- DSA-related libraries
- GUI libraries (high-level overview)
- Quiz on modules and packages

---

### `08_python_packages_and_modules/`

This section contains **real Python packages and modules**, not notebooks.
Since packages must be imported directly, `.ipynb` files are not suitable.

Included:

* A sample Python package (`example_package`) with:

  * `__init__.py`
  * utility modules (`math_utils.py`, `string_utils.py`)
  * a subpackage (`helper/file_ops.py`)

* Practical examples showing different import styles:

  * `import module`
  * `from module import function`
  * `import package.module as alias`
  * package folder structure explanations

Use these files to practice:

* creating your own packages
* writing reusable modules
* understanding how imports really work
* structuring Python projects professionally

---

## 🔧 How to Use This Repo

1. Clone the repository:
```bash
git clone https://github.com/SonaniAkshit/python-for-data-science.git
cd python-for-data-science
```