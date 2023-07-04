Python - Test-driven development
alt text

Description
This project's purpose is to practice Test-Driven Development. Every task is composed of one script, and one corresponding test file for this script.

The doctests can be run with python3 -m doctest ./tests/* The unittest can be run with python3 -m unittest tests.6-max_integer_test

Tests ✔️
tests: Folder containing all the interactive tests and unittests for the python scripts of this project
0-add_integer.txt
2-matrix_divided.txt
3-say_my_name.txt
4-print_square.txt
5-text_indentation.txt
6-max_integer_test.py
100-matrix_mul.txt
101-lazy_matrix_mul.txt
Table of contents 💾
Files	Description	Prototype
0-add_integer.py	Python function that adds 2 integers	def add_integer(a, b=98):
2-matrix_divided.py	Python function that divides all elements of a matrix	def matrix_divided(matrix, div):
3-say_my_name.py	Python function that prints "My name is first_name last_name"	def say_my_name(first_name, last_name=""):
4-print_square.py	Python function that prints a square with the character #	def print_square(size):
5-text_indentation.py	Python function that prints a text with 2 new lines after each of these characters: ., ? and :	def text_indentation(text):
100-matrix_mul.py	Python function that multiplies 2 matrices	def matrix_mul(m_a, m_b):
101-lazy_matrix_mul.py	Python function that multiplies 2 matrices by using the module NumPy	def lazy_matrix_mul(m_a, m_b):
102-python.c	C function that prints Python strings	void print_python_string(PyObject *p);
