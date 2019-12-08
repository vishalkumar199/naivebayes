# Naivebayes
Implemention of the Naive bayes Algo on the DonorChoose Dataset and measure the accuracy on the Test dataset.

The DonorsChoose Data Set contains train.csv and resources.csv files

### train.csv contains
1. project_id (A unique identifier for the proposed project)
2. project_title (Title of the project)
3. project_grade_category (Grade level of students for which the project is targeted)
4. project_subject_categories (One or more (comma-separated) subject categories for the project from enumerated list of values)
5. school_state (State where school is located (Two-letter U.S. postal code))
6. project_subject_subcategories (One or more (comma-separated) subject subcategories for the project)
7. project-resource_summary (An explanation of the resources needed for the project.)
8. project_essay_1 (First application essay)
9. project_essay_2 (second application essay)
10. project_essay_3 (third application essay)
11. project_essay_4 (fourth application essay)
12. project_submitted_datetime (Datetime when project application was submitted)
13. teacher_id (A unique identifier for the teacher of the proposed project)
14. teacher_prefix (Teacher's title)
15. teacher_number_of_previously_posted_projects (Number of project applications previously submitted by the same teacher)
16. project_is_approved (A binary flag indicating whether DonorsChoose approved the project. A value of 0 indicates the project was not approved, and a value of 1 indicates the project was approved)

# Additionally, the resources.csv data set provides more data about the resources required for each project. Each line in this file represents a resource required by a project:

1. id (A project_id value from the train.csv)
2. description (Desciption of the resource)
3. quantity (Quantity of the resource required)
4. price (Price of the resource required)


# Objective: The primary objective is to implement the Naive Bayes Algo on the DonorChoose Dataset and measure the accuracy on the Test dataset.
