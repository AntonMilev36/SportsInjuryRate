## Idea
The project goal is to analyze which are the sports with higher injuries risk. The idea is not to tell there is 1 sport that is the worst, but to see trends in injuries.


## Implementation
To achieve the goal we will use 2 datasets.
1. Information about the total sport related injuries
2. Information about number of people practicing a specific sport

By using this 2, we could get injury rate of a sport not just the total number or injuries


## Limitations
The datasets we use are both representing only US citizens, which is byes we have to keep in mind when working with this data


## How to work with the code
It highly recommended to execute the files in this order
1. Prerequisite files
* [base.ipynb](app/base.ipynb)
* [table_operations.ipynb](app/table_operations.ipynb)

2. Data clearing
* [product_codes.ipynb](app/product_codes.ipynb)
* [clear_injury_data.ipynb](app/clear_injury_data.ipynb)
* [clear_participation_data.ipynb](app/clear_participation_data.ipynb)

3. Dependency_checks
* [dependency_checks.ipynb](app/dependency_checks.ipynb)

4. Data
* [injury_rate.ipynb](app/injury_rate.ipynb)

In the `extracted_data` folder are all modified files that were made. The creation steps are skipped by default, so if you want to check the tables created, delete this folder. Then the order described above *is required*. Because there are some dependencies.


## Codes tables
An important note is that all code tables that we have in `data/original_data/codes` are manually created by the author by reading the NEISS documentation. There is no source for them that could be provided, even tho this file [put file here] tries to describe this.

The idea behind this approach is that in a lot of columns in the NEISS datasets a specific value is represented by a number and we need some way to determine this numbers meaning. The CSV give us both readability and easy way to work with this data

