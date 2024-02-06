# Sorting Algorithms
This project includes implementations of five sorting algorithms (Insertion Sort, Bubble Sort, Merge Sort, Quick Sort, and Radix Sort) and a performance comparison across different dataset sizes.    

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.    

## Prerequisites
You need Python 3.x installed on your system to run the scripts. You can download Python from [here](https://www.python.org/downloads/).    
Also, installed Jupyter notebook, you can do so via pip:    
pip install notebook     

## Installing   
Clone the repository to your local machine:         
git clone git@github.com:rosendo-lugo/data_structure.git         

## Navigate to the cloned directory in your terminal:     
cd /Users/yourname/folder_where_you_clone_the_file/     

## Running the Code    
To run the sorting algorithm performance tests, execute the following command in your terminal:    
jupyter lab    
Navigate to module3 folder and then to soring_algorithms.ipynb file and open it. You can then run the notebook cells directly in the web interface.     

This script will automatically generate datasets of sizes 1,000; 10,000; 100,000; and optionally 1,000,000 integers, and then perform sorting using each of the five algorithms. The execution time for each algorithm and dataset size will be printed to the console.    

## Performing the Tests    
The script is set up to test each sorting algorithm's performance across four different dataset sizes. To modify the dataset sizes or add new ones, edit the dataset_sizes list in the sort_algorithms.ipynb file.    

For a more detailed analysis, you can modify the test_sort_performance function to output additional performance metrics or to save the results to a file for further analysis.   

## Built With    
Python 3 - The programming language used.     

## Authors   
Rosendo Lugo Jr. - Initial work - https://github.com/rosendo-lugo    
