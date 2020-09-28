 # Basic Cleaning Project

## Reflection

This reflection should demonstrate a general understanding of the tasks (what you had to do), methods used, etc.

This project was all about cleaning data by either deleting or filling the missing values with predictive values to analyze the data correctly without any bias. The data from the site kaggle, named **Detailed NFL Play-by-Play Data 2009-2017**, and **San Francisco Building Permits** were used for the project.

The process was straight forward. After going through what data looks like, the information on missing values was checked. The amount of overall missing values, how many were missing in each field, the percentage of overall data missing and in each field were analyzed. 

Then, it was time to find out the reasons the missing data existed for each field. What happens if all the missing values were just dropped? Why can’t they be left as it is? 

The attempts to fill in the missing values were done with different methods for different types of data. This step is known as imputing, and there are so many ways to impute the missing values from data. But, there is no right answer. 

Finally, the statistical impact was discussed how imputed data affect average, standard deviations, and the correlation between data.

All python requirements are stored in `requirements.txt`. Run the code below to install the requirements.


    pip install -r requirements.txt


## Reflection questions

**1. What do I believe I did well on this assignment?**
I seriously want to give a tap on my shoulder for not giving up on this project. I tried using various types of imputing methods from ScikitLearn. I am pretty sure I did not do it the way it supposed to be, but I tried my best. I got KNNimputer working but computation using it is super slow. It was a whole mass but I learned a lot, and should do better for the next assignment.  

**2. What was the most challenging part of this assignment?**
I thought there would be a way to impute the entire data set with a single function. Multivariate feature imputation would be one, but not in all cases with different datatypes. Also, connecting dots with various columns was difficult. I want to know how experts think and act for the entire data cleaning process.

Lastly, it is challenging to combine technical knowledge and analytics knowledge at the same time to give great insight. I want to be good at it, but I’m just at the first step.

**3. What would have made this assignment a better experience?**
I know there cannot be a step by step guideline for this kind of project. However, some examples of how we should think about or proceed with imputing data on certain types of situations would be a great guideline. For example, I was just lost on imputing data that were not numerical, but either objects or strings.

**4. What do I need help with?**
Detailed steps on how the thought process should be when looking at the data for the first time would help a lot. When I sat down and opened the massive CSV file, I was misplaced then to be excited. I believe what I need is more exposure and experience in data cleaning and analyzing. Rather than having a panic attack about what to do, I just read so many articles on how people did about the imputing data.

**5. What did I actually learn by doing this assignment? Why does it matter?**
I learned a lot. It was pretty much the first time working on a data cleaning project. I now understand there is no such thing as clean data. There will be something or a lot of things that are not input. There is no global guideline on how to collect data, so it is our job to clean the dataset to be able to work with them. I learned the importance of how to clean them by using different types of imputation methods. None of them are perfect for every situation, but the predictiveness is getting better with machine learning and deep learning. I am learning and growing. That's all it matters. Be easy on the grades please. I spent nights on this.

## License

[MIT](https://choosealicense.com/licenses/mit/)

