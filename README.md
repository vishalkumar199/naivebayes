# Naive Bayes
**Objective**: The primary objective is to implement the Naive Bayes Algo on the DonorChoose Dataset and measure the accuracy on the Test dataset.

The DonorsChoose Data Set contains train.csv and resources.csv files

**train.csv** contains
* project_id (A unique identifier for the proposed project)
* project_title (Title of the project)
* project_grade_category (Grade level of students for which the project is targeted)
* project_subject_categories (One or more (comma-separated) subject categories for the project from enumerated list of values)
* school_state (State where school is located (Two-letter U.S. postal code))
* project_subject_subcategories (One or more (comma-separated) subject subcategories for the project)
* project-resource_summary (An explanation of the resources needed for the project.)
* project_essay_1 (First application essay)
* project_essay_2 (second application essay)
* project_essay_3 (third application essay)
* project_essay_4 (fourth application essay)
* project_submitted_datetime (Datetime when project application was submitted)
* teacher_id (A unique identifier for the teacher of the proposed project)
* teacher_prefix (Teacher's title)
* teacher_number_of_previously_posted_projects (Number of project applications previously submitted by the same teacher)
* project_is_approved (A binary flag indicating whether DonorsChoose approved the project. A value of 0 indicates the project was not approved, and a value of 1 indicates the project was approved)

**Additionally, the resources.csv data set provides more data about the resources required for each project**

Each line in this file represents a resource required by a project:

* id (A project_id value from the train.csv)
* description (Desciption of the resource)
* quantity (Quantity of the resource required)
* price (Price of the resource required)

**Sampling Techniques (Stratified Sampling)**
If the number of values belonging to each class are unbalanced, using stratified sampling is a good thing. We are basically asking the model to take the training and test set such that the class proportion is same as of the whole dataset, which is the right thing to do.

**vectorizing Method (used)**
* Bow
  * We convert text to a numerical representation called a feature vector.
  * A feature vector can be as simple as a list of numbers.
* TFIDF
