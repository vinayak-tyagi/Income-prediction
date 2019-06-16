# Income-Prediction
This repository uses the data from [Kaggle-US Adult Income data](https://www.kaggle.com/johnolafenwa/us-census-data#adult-training.csv)

In this dataset Income is related to social factor's like Age, Education, Race etc.
This data has been extracted by Barry Becker from the 1994 US Census Database.The data set consists of anonymous information such as occupation, age, native country, race, capital gain, capital loss, education, work class and more. Each row is labelled as either having a salary greater than ">50K" or "<=50K".

The `goal` here is to train a binary classifier on the training dataset to predict the column `income_bracket` which has two possible values ">50K" and "<=50K".

Since most of the plots that I made were using Seaborn and matplotlib, they are not rendered in the file so I'll show them here with the insights I got from them. Although you can find some plots that I made with matplotlib in the code file itself.

### Age Distribution
![](https://github.com/vinayak-tyagi/Income-prediction/blob/master/viz/age_categ_pic.JPG)

- we can see that number's of younger and adult are more than old and teen's because of there working hour's capacity and ablity to solve complex task and matureness in working.

### Occupation Distribution
![](https://github.com/vinayak-tyagi/Income-prediction/blob/master/viz/occupation_pic.JPG)

- we can observe over here that prof-speciality has the highest number for people than any other occupation.

### Working Hour's Distribution
![](https://github.com/vinayak-tyagi/Income-prediction/blob/master/viz/hours_cat_week_pic.JPG)

- We can see that number of people working for 40-30 hrs are most and than 40-60 hrs and than 30 hrs and at last 60 hrs.
- People working 40-60 hrs usually sometime also works for 30 hrs or vice-versa.

### Age Distribution With Income
![](https://github.com/vinayak-tyagi/Income-prediction/blob/master/viz/age_categ_income_pic.JPG)

- We can Observe that mostly adult and old have income `>50k` the reason for that may be there working experience and matureness in work.
- Where as younger's are learner's so they earn lesser than Adult's and Older's.

### Workclass Distribution With Income
![](https://github.com/vinayak-tyagi/Income-prediction/blob/master/viz/workclass_income_pic.JPG)

- We can Observe that number of Self-Employee which earn `50k` is greatest than any other category and than feral-gov and then local-gov employee earn the highest.

### Working hours-per-week categories Distribution With Income
![](https://github.com/vinayak-tyagi/Income-prediction/blob/master/viz/hours_cat_week_income_pic.JPG)

- We can Observe that number of peoples which works `>40&<60 hrs` and `>= 60 hrs` earn the most which is greater than 50K.
