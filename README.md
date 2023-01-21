# Welcome to DSI-Africa Machine Learning Short Course: UKZN Hub

This will be a two-week short course taught by several experts both locally and internationally. The aim of the course is to
enhance capacity in machine learning methods for health data science to address global health problems in Africa.
Software required: R & RStudio.

* Course materials can be found here. 
* Official course webpage here: [http://mlcourseukzn.github.io](http://mlcourseukzn.github.io)

# Instructor
* Dr. Gabreil Kallah-Dagadu
* Postdoc Fellow
* kallahdagadug@ukzn.ac.za
* Dr. Mohanad Mohammed
* Postdoc Fellow
* mohammedm1@ukzn.ac.za

# Dates
Monday, 23 January 2023 – Friday, 3rd February 2023

# Time
09h00 – 16h00 SAST daily

# Venue
KRITH building, K1 and K2 seminar rooms (Ground floor), University of KwaZulu-Natal Medical School, Umbilo Road, Durban

# Schedule

Note: all lectures will be held in-person AND online via Zoom links. For online attendance please use the following link: https://tinyurl.com/2yxd7pwk

## Week 1:

| Time      | Monday 23/01 | Tuesday 24/01  | Wednesday 25/01 | Thursday 26/01 | Friday 27/01 |
| :---     |    :----   |    :--- | :--- | :--- | :--- |
| 9:00-10:30 am | Introduction to machine learning  | Naïve Bayes, KNN | Regression and classification trees | Regularization, Ridge Regression, LASSO | Dealing with a multiclass classification problem |
| 10:30-10:45 am | Break  | Break | Break | Break | Break |
| 10:45-12:00 pm | Logistic regression  | LDA and QDA | Random forests and boosting | Support vector machines | Multinomial regression |
| 12:00-1:00 pm | Lunch | Lunch | Lunch | Lunch | Lunch |
| 1:00-2:15 pm | Performance metrics, ROC, AUROC | Tuning of parameters, avoid over fitting | Feature selection and feature importance | Tuning of machines, comparison of machines | The validation of machines problem |
| 2:15-2:30 pm | Break | Break | Break | Break | Break |
| 2:30-3:45 pm | Lab | Lab | Lab | Lab | Lab |


## Week 2:

| Time      | Monday 23/01 | Tuesday 24/01  | Wednesday 25/01 | Thursday 26/01 | Friday 27/01 |
| :---     |    :----   |    :--- | :--- | :--- | :--- |
| 9:00-10:30 am | Introduction to Cross Validation; Types of Cross Validation  | Application: Individual Data inspection and Preparation for modelling | Application: kNN, LDA and QDA | Application: Random forests: Regression and classification trees | Report writing based on the cases (Dataset) the participant(s) work on. |
| 10:30-10:45 am | Break  | Break | Break | Break | Break |
| 10:45-12:00 pm | Practical Dataset partitioning  | Application: Logistic Regression Model | Application: kNN, LDA and QDA | Interpretation of the random forest results using variable importance. | Report writing based on the cases (Dataset) the participant |
| 12:00-1:00 pm | Lunch | Lunch | Lunch | Lunch | Lunch |
| 1:00-2:15 pm | Dealing with imbalanced datasets | Application: Naïve Bayes model | Application: Evaluation of the models’ performance and Interpretations | Application: Ridge Regression, LASSO | Report writing based on the cases (Dataset) the participant |
| 2:15-2:30 pm | Break | Break | Break | Break | Break |
| 2:30-3:45 pm | Practical evaluation of model performance through cross validation | Interpretations of the models results and performance evaluation. | Application: Evaluation of the models’ performance and Interpretations | Application: Evaluation of the models’ performance and Interpretations | Course Evaluation and Closing Remarks |


# Downloading course materials using Git with RStudio

You can use Git within RStudio to download the course materials. If you
haven't cloned the repository before, follow these instructions:

1. Click on the green "Clone or Download" on Github and copy the link.
2. Open RStudio, and go to File > New Project > Version Control > Git,
and paste in the link you just copied. Under "Create Project as
Subdirectory of", browse and select a folder where you want the course
materials to go.
3. Press "Create Project". This will create a folder called `DSI_Africa_ML_ShortCourse`
in the folder you selected in step 2.
4. Now, you can open this project using the projects tab in the upper
right of RStudio, or going to File > Open Project and then navigating
to the `DSI_Africa_ML_ShortCourse` folder and opening the `.Rproj` file.

If you already cloned the repository outside of RStudio (e.g. using
Git Bash), you can associate the directory that was created in that
step with RStudio. In RStudio, go to File > New Project > Existing Directory, and then navigate / click on the BST219_2022 folder. Then click
"Create Project". Then you can follow step 4 above to open the project
when you launch RStudio. You can read more about RStudio projects here:
https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects

# Updating Course Repo

Once you cloned the course repository and want to get updates, you must
use `git pull` to get updates.

In RStudio, if you followed the instructions above, simply navigate
to the Git tab and press the Pull button. In terminal / Git bash, use
`cd` to navigate to the `BST219_2022` folder, then run `git pull`.


# Taking Notes on Course Materials

If you wish to take notes and write in the course materials, you can
save a copy of the file you want to take notes on with the filename
containing `personal`. For example, if you want to take notes on the
file `00-motivation.Rmd`, save it as `00-motivation_personal.Rmd`. Then,
you can edit the `00-motivation_personal.Rmd` file. We have configured
Git to ignore any files that contain `personal` in the filename, so any changes you make won't show up in Git. This will
allow you to update the course repo without any issues.
