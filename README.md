# nyc16_ids1
Intro to Data Science - NYC - April 2016 - Cohort 1

Course materials for [Metis' Introduction to Data Science Course](http://www.thisismetis.com/introduction-to-data-science) in New York, NY (4/19/16 - 5/26/15).

**Instructor:** [Sergey Fogelson](https://www.linkedin.com/in/sergey-fogelson-ph-d-8b3a4a4)

### [Course Project](project/README.md)

###Schedule:
Tuesday | Thursday
--- | ---
4/19: [Introduction to Python and Version Control](#class-1-introduction-to-python-and-version-control) | 4/21: [Introduction to Linear Algebra and Statistics in Python](#class-2-introduction-to-linear-algebra-and-statistics-in-python)
4/26: [Pandas and Exploratory Data Analysis](#class-3-pandas-and-exploratory-data-analysis) | 4/28: [Pandas and Data Visualization](#class-4-pandas-and-data-visualization)
5/3: [Supervised Machine Learning and Basic Model Evaluation](#class-5-supervised-machine-learning-and-basic-model-evaluation) | 5/5: [Unsupervised Machine Learning and Basic Model Evaluation](#class-6-unsupervised-machine-learning-and-basic-model-evaluation)
5/10: [Advanced Supervised Learning](#class-7-advanced-supervised-learning) | 5/12: [Data Modeling: Feature Engineering and Basic Cross Validation](#class-8-feature-engineering-and-basic-cross-validation)

### Before the Course Begins (Prework):
* Install [Git](http://git-scm.com/downloads).
* Create an account on [GitHub](https://github.com/).
    * It is not necessary to download "GitHub for Windows" or "GitHub for Mac"
* Install [SourceTree](https://www.sourcetreeapp.com) and sign into your github account through it.
* Install [slack](https://slack.com) and get the necessary credentials to communicate on the metis slack channels.
* Install the [Anaconda distribution](http://continuum.io/downloads) of Python 2.7x.
    * If you choose not to use Anaconda, here is a list of the [Python packages](utils/python_packages.md) you will need to install prior to starting the course.
* Complete exercises 1-7, 13, 18-21, 27-35, 38, 39 of [Learn Python The Hard Way](http://learnpythonthehardway.org/book/)
* Watch the [linear algebra review videos](https://class.coursera.org/ml-005/lecture/preview) from Andrew Ng’s excellent Coursera ML course. They are labeled III. Linear Algebra Review (Week 1).
* Complete the exercises in chapters 2 and 3 of [this open textbook](https://www.openintro.org/stat/textbook.php).
)
* Practice Python using the resources below if you get through everything else.
* I would like to check the setup of your laptop before the course begins:
    * We need to figure out the logistics behind this, but it absolutely must happen before the course starts. If I cannot check it, someone else at Metis will, who will then sign off on you being able to start the course. YOU CANNOT START THE COURSE UNTIL EITHER I OR SOMEONE ELSE AT METIS CONFIRMS YOU HAVE A WORKING DEVELOPMENT ENVIRONMENT AS WE DO NOT WANT TO SPEND THE FIRST HOUR OF THE FIRST CLASS DEBUGGING ENVIRONMENTS.

### Python Resources
* [Codecademy's Python course](http://www.codecademy.com/en/tracks/python): Good beginner material, including tons of in-browser exercises.
* [DataQuest](https://dataquest.io/): Similar interface to Codecademy, but focused on teaching Python in the context of data science.
* [Google's Python Class](https://developers.google.com/edu/python/): Slightly more advanced, including hours of useful lecture videos and downloadable exercises (with solutions).
* [A Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/rpmuller/5920182): Read through the Overview section for a quick introduction to Python.
* [Python for Informatics](http://www.pythonlearn.com/book.php): A very beginner-oriented book, with associated [slides](https://drive.google.com/folderview?id=0B7X1ycQalUnyal9yeUx3VW81VDg&usp=sharing) and [videos](https://www.youtube.com/playlist?list=PLlRFEj9H3Oj4JXIwMwN1_ss1Tk8wZShEJ).
* [Python Tutor](http://pythontutor.com/): Allows you to visualize the execution of Python code.

### [Additional resources](#bonus-resources)

-----
### Class 1: Introduction to Python and Version Control
* Welcome
* Briefly discuss the [course project](project/README.md) and [public data sources](project/public_data.md)
* Intro to [SourceTree](https://www.sourcetreeapp.com)
* Intro to IPython Notebooks ([notebook](notebooks/01_intro_to_ipython_notebook.ipynb))
* Intro to Python ([notebook](notebooks/01_intro_to_python.ipynb))
* Wrap up: Getting help, course schedule, office hours

**Homework:**
* Finish whatever exercises from [LPTHW](http://learnpythonthehardway.org/book/) you couldn't finish. I assigned a lot of exercises as prework, so I suspect you have some things to work on. Focus on those concepts in the lecture that you didn't quite get.
* If your laptop has any setup issues, please work with me or someone else at Metis to resolve them by Thursday.

**Git Resources (IF YOU DON'T WANT TO USE SOURCETREE):**
* [Pro Git](http://git-scm.com/book/en/v2) is an excellent book for learning Git if you don't want to use SourceTree. Read the first two chapters if you want to gain a deeper understanding of version control.
* If you want to really practice a lot of Git (and learn many more commands), try [Git Immersion](http://gitimmersion.com/).
* [GitRef](http://gitref.org/) is an excellent reference guide for Git commands.

-----

### Class 2: Introduction to Linear Algebra and Statistics in Python
* Introduction to Linear Algebra in Python ([notebook](notebooks/02_intro_linalg.ipynb))
* Introduction to Statistics in Python ([notebook](notebooks/02_intro_stats.ipynb))

**Homework:**
* Work through as much of the [NumPy quickstart guide](https://docs.scipy.org/doc/numpy-dev/user/quickstart.html) as you can.
* Work through the remainder of the statistics exercises in the prework.

-----

### Class 3: Pandas and Exploratory Data Analysis
* Using Pandas for Exploratory Data Analysis [notebook](notebooks/03_pandas_and_eda.ipynb)
* Using Pandas for More Exploratory Data Analysis [notebook](notebooks/03_pandas_and_more_eda.ipynb) 

**Homework:**
* HW 1 [notebook](notebooks/03_hw1.ipynb)
* HW 2 [notebook](notebooks/03_hw2.ipynb)

**Resources:**
* The Pandas [API Reference](http://pandas.pydata.org/pandas-docs/stable/api.html) is fantastically documented.
* To learn more Pandas, review this [three-part tutorial](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/).
* Here are two excellent (but extremely long) notebooks on Pandas: 
    * [Introduction to Pandas](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_5-Introduction-to-Pandas.ipynb)
    * [Data wrangling with Pandas](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_6-Data-Wrangling-with-Pandas.ipynb).
* If you want to go all in on Pandas (and NumPy), the book [Python for Data Analysis](http://shop.oreilly.com/product/0636920023784.do) was written by the creator of Pandas. It is really great.
* Here are examples of different types of [joins in Pandas](http://www.gregreda.com/2013/10/26/working-with-pandas-dataframes/#joining), for when you need to figure out how to merge two DataFrames.

-----

### Class 4: Pandas and Data Visualization
* Visualization with Pandas and Matplotlib [notebook](notebooks/04_pandas_visualization.ipynb)

**Homework:**
* Finish the exercises you were not able to complete from the classwork for the day.
* [notebook](notebooks/04_hw.ipynb)

**Visualization Resources:**
* Watch [Look at Your Data](https://www.youtube.com/watch?v=coNDCIMH8bk) (18 minutes) for an excellent example of why visualization is useful for understanding your data.
* [Plotting in Pandas notebook](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_7-Plotting-with-Pandas.ipynb) 
* The [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) from the official Pandas documentation is fantastic.
*  [This notebook on matplotlib](http://nbviewer.ipython.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_4-Matplotlib.ipynb) or this [similar notebook](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb) are both very good for showing you how to use matplotlib effectively.
* To explore different types of visualizations and when to use them:
    * [Choosing a Good Chart](http://extremepresentation.typepad.com/files/choosing-a-good-chart-09.pdf)
    * [The Graphic Continuum](http://www.coolinfographics.com/storage/post-images/The-Graphic-Continuum-POSTER.jpg)
* This [PowerPoint presentation](http://www2.research.att.com/~volinsky/DataMining/Columbia2011/Slides/Topic2-EDAViz.ppt) from Columbia's Data Mining class contains lots of good advice for properly using different types of visualizations.

-----

### Class 5: Supervised Machine Learning and Basic Model Evaluation
* Introduction to supervised machine learning - linear regression ([notebook](notebooks/05_supervised_machine_learning_linear_regression.ipynb))
* Introduction to supervised machine learning - logistic regression ([notebook](notebooks/05_supervised_machine_learning_logistic_regression.ipynb))
* Course project:
    * The deadline for choosing your course project is today.

**Homework:**
* Read [this excellent blog post on understanding bias and variance](http://scott.fortmann-roe.com/docs/BiasVariance.html). It explains the basic tradeoff that all machine learning algorithms attempt to address in one way or another. This is also known as the "No Free Lunch" theorem.

**Machine Learning Resources:**
* For an in-depth introduction to machine learning, read section 2.1 (14 pages) of Hastie and Tibshirani's excellent book, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/).
* For a preview of some of the machine learning content we will cover during the course, read Sebastian Raschka's [overview of the supervised learning process](https://github.com/rasbt/pattern_classification/blob/master/machine_learning/supervised_intro/introduction_to_supervised_machine_learning.md).
* For fun, look up the [characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/), and then read about the [67 distinct segments](http://doc.arcgis.com/en/esri-demographics/data/tapestry-segmentation.htm) in detail.

**Model Evaluation Resources:**
* For another explanation of training error versus testing error, the bias-variance tradeoff, and train/test split (also known as the "validation set approach"), watch Hastie and Tibshirani's video on [estimating prediction error](https://www.youtube.com/watch?v=_2ij6eaaSl0&t=2m34s) (12 minutes, starting at 2:34).
* Caltech's Learning From Data course includes a fantastic video on [visualizing bias and variance](http://work.caltech.edu/library/081.html) (15 minutes).
* [Random Test/Train Split is Not Always Enough](http://www.win-vector.com/blog/2015/01/random-testtrain-split-is-not-always-enough/) explains why random train/test split may not be a suitable model evaluation procedure if your data is time-based.

-----

### Class 6: Unsupervised Machine Learning and Basic Model Evaluation
* Clustering ([notebook](notebooks/06_unsupervised_machine_learning_clustering.ipynb))
    * K-means: [visualization](http://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
    * DBSCAN: [visualization](http://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)

**Clustering Resources:**
* scikit-learn's documentation on [clustering](http://scikit-learn.org/stable/modules/clustering.html) compares many different types of clustering.
* For a very thorough introduction to clustering, read chapter 8 (69 pages) of [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php) (available as a free download), or browse through the chapter 8 slides.
* An Introduction to Statistical Learning has useful videos on [K-means clustering](https://www.youtube.com/watch?v=aIybuNt9ps4&list=PL5-da3qGB5IBC-MneTc9oBZz0C6kNJ-f2) (17 minutes) and [hierarchical clustering](https://www.youtube.com/watch?v=Tuuc9Y06tAc&list=PL5-da3qGB5IBC-MneTc9oBZz0C6kNJ-f2) (15 minutes).
* Fun examples of clustering: [A Statistical Analysis of the Work of Bob Ross](http://fivethirtyeight.com/features/a-statistical-analysis-of-the-work-of-bob-ross/) (with [data and Python code](https://github.com/fivethirtyeight/data/tree/master/bob-ross)), [How a Math Genius Hacked OkCupid to Find True Love](http://www.wired.com/2014/01/how-to-hack-okcupid/all/).

-----

### Class 7: Advanced Supervised Learning
* Ensembles: From Decision Trees to Random Forests [notebook](notebooks/07_from_decision_trees_to_random_forests.ipynb)

**Resources:**
* scikit-learn's documentation on [ensemble methods](http://scikit-learn.org/stable/modules/ensemble.html) covers both "averaging methods" (such as bagging and Random Forests) as well as "boosting methods" (such as AdaBoost and Gradient Tree Boosting).
* For an intuitive explanation of Random Forests, read Edwin Chen's answer to [How do random forests work in layman's terms?](http://www.quora.com/Random-Forests/How-do-random-forests-work-in-laymans-terms/answer/Edwin-Chen-1)
* [Interpretable vs Powerful Predictive Models: Why We Need Them Both](https://medium.com/@chris_bour/interpretable-vs-powerful-predictive-models-why-we-need-them-both-990340074979) is a short post on how the tactics useful in a Kaggle competition are not always useful in the real world.

-----

### Class 8: Feature Engineering and Basic Cross Validation
* Feature Engineering/Cross Validation [notebook](notebooks/08_feature_engineering_cross_validation.ipynb)
    
**Feature Engineering/Selection Resources:**
* Machine Learning Mastery: [An Introduction to Feature Selection](http://machinelearningmastery.com/an-introduction-to-feature-selection/)
* [StandardScaler](http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
* Here is a longer example of [feature scaling](http://nbviewer.ipython.org/github/rasbt/pattern_classification/blob/master/preprocessing/about_standardization_normalization.ipynb) in scikit-learn, with additional discussion of the types of scaling you can use.
* Section 3.3.1 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (4 pages) has a great explanation of dummy encoding for categorical features.
* These examples may help you to better understand the process of feature engineering: 
    * [predicting the number of passengers at a train station](https://medium.com/@chris_bour/french-largest-data-science-challenge-ever-organized-shows-the-unreasonable-effectiveness-of-open-8399705a20ef)
    * [identifying fraudulent users of an online store](https://docs.google.com/presentation/d/1UdI5NY-mlHyseiRVbpTLyvbrHxY8RciHp5Vc-ZLrwmU/edit#slide=id.p)
    * [identifying bots in an online auction](https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot/forums/t/14628/share-your-secret-sauce)
    * [predicting who will subscribe to the next season of an orchestra](http://blog.kaggle.com/2015/01/05/kaggle-inclass-stanfords-getting-a-handel-on-data-science-winners-report/)
    * [evaluating the quality of e-commerce search engine results](http://blog.kaggle.com/2015/07/22/crowdflower-winners-interview-3rd-place-team-quartet/).

**Cross-Validation Resources:**
* scikit-learn documentation: 
    * [Cross-validation](http://scikit-learn.org/stable/modules/cross_validation.html)
    * [Model evaluation](http://scikit-learn.org/stable/modules/model_evaluation.html)
* scikit-learn issue on GitHub: [MSE is negative when returned by cross_val_score](https://github.com/scikit-learn/scikit-learn/issues/2439)
* Section 5.1 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (11 pages) and related videos: 
    * [K-fold and leave-one-out cross-validation](https://www.youtube.com/watch?v=nZAM5OXrktY) (14 minutes)
    * [Cross-validation the right and wrong ways](https://www.youtube.com/watch?v=S06JpVoNaA0) (10 minutes)
* Scott Fortmann-Roe: [Accurately Measuring Model Prediction Error](http://scott.fortmann-roe.com/docs/MeasuringError.html)
* Harvard CS109: [Cross-Validation: The Right and Wrong Way](http://nbviewer.ipython.org/github/cs109/content/blob/master/lec_10_cross_val.ipynb)
* Journal of Cheminformatics: [Cross-validation pitfalls when selecting and assessing regression and classification models](http://www.jcheminf.com/content/pdf/1758-2946-6-10.pdf)
* For a recap of today's lesson on GridSearchCV, plus a comparison with RandomizedSearchCV, watch [How to find the best model parameters in scikit-learn](https://www.youtube.com/watch?v=Gol_qOgRqfA&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=8) (28 minutes)

-----

## Bonus Resources

### Pandas/SQL/Databases
* This [slide deck](https://github.com/justmarkham/DAT5/blob/master/slides/20_sql.pdf) provides a brief introduction to databases and SQL.
* The repository for this [SQL Bootcamp](https://github.com/brandonmburroughs/sql_bootcamp) contains an extremely well-commented SQL script that is suitable for walking through on your own.
* This [ipython notebook](http://nbviewer.ipython.org/github/podopie/DAT18NYC/blob/master/classes/17-relational_databases.ipynb) provides a shorter introduction to databases and SQL that helpfully contrasts SQL queries with Pandas syntax.
* [SQLZOO](http://sqlzoo.net/wiki/SQL_Tutorial), [Mode Analytics](http://sqlschool.modeanalytics.com/), and [Code School](http://campus.codeschool.com/courses/try-sql/contents) all have online beginner SQL tutorials that look promising.
* [w3schools](http://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) has a sample database that allows you to practice SQL from your browser. Similarly, Kaggle allows you to query a large SQLite database of [Reddit Comments](https://www.kaggle.com/c/reddit-comments-may-2015/data) using their online "Scripts" application.
* [What Every Data Scientist Needs to Know about SQL](http://joshualande.com/data-science-sql/) is a brief series of posts about SQL basics, and [Introduction to SQL for Data Scientists](http://bensresearch.com/downloads/SQL.pdf) is a paper with similar goals.
* [10 Easy Steps to a Complete Understanding of SQL](http://tech.pro/tutorial/1555/10-easy-steps-to-a-complete-understanding-of-sql) is a good article for those who have some SQL experience and want to understand it at a deeper level.
* SQLite's article on [Query Planning](http://www.sqlite.org/queryplanner.html) explains how SQL queries "work".
* [A Comparison Of Relational Database Management Systems](https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems) gives the pros and cons of SQLite, MySQL, and PostgreSQL.
* If you want to go deeper into databases and SQL, Stanford has a well-respected series of [14 mini-courses](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about).
* [Blaze](http://blaze.readthedocs.org/en/latest/index.html) is a Python package enabling you to use Pandas-like syntax to query data living in a variety of data storage systems.

### Tidy Data is Better Data
* [Good Data Management Practices for Data Analysis](https://www.prometheusresearch.com/good-data-management-practices-for-data-analysis-tidy-data-part-2/) briefly summarizes the principles of "tidy data".
* [Hadley Wickham's paper](http://www.jstatsoft.org/v59/i10/paper) explains tidy data in detail and includes lots of good examples.
* Example of a tidy dataset:
    * [Bob Ross](https://github.com/fivethirtyeight/data/blob/master/bob-ross/elements-by-episode.csv)
* Examples of godawful/untidy datasets: 
    * [NFL ticket prices](https://github.com/fivethirtyeight/data/blob/master/nfl-ticket-prices/2014-average-ticket-price.csv)
    * [airline safety](https://github.com/fivethirtyeight/data/blob/master/airline-safety/airline-safety.csv)
    * [Jets ticket prices](https://github.com/fivethirtyeight/data/blob/master/nfl-ticket-prices/jets-buyer.csv)
    * [Chipotle orders](https://github.com/TheUpshot/chipotle/blob/master/orders.tsv)

In general, [spreadsheets that are unreadable by computers](https://bosker.wordpress.com/2014/12/05/the-government-statistical-services-terrible-spreadsheet-advice/) are the worst. 

If you (or your friends/colleagues) tend to make them, please [read this](http://www.clean-sheet.org/). There are additional suggestions for how to make tidy data [here](http://stats.stackexchange.com/questions/83614/best-practices-for-creating-tidy-data/83711#83711).
