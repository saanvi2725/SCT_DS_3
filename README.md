# SCT_DS_3

Task 03 – Decision Tree Classifier
SkillCraft Technology – Data Science Internship


I worked with Bank Marketing data for this task, using a Decision Tree Classifier. It was trained to predict if a customer will subscribe to a term deposit based on demographic and past interaction details.

Dataset Info
For the UCI Bank Marketing Dataset, I used the bank-full.csv file.

Age, job, education, marital status

Whether the customer has a loan or housing loan

Column of Interest: y → yes/no (Did the client subscribe?)


Tools & Libraries Used

pandas, numpy for data wrangling

scikit-learn for modeling

matplotlib, seaborn for visualization


What I Did
🔹 Step 1: Data Cleaning
Checked for null values and data types

Encoded categorical variables using LabelEncoder

Removed any obvious inconsistencies

🔹 Step 2: Splitting the Data
I used train-test-split to split the data into a training set (80%) and a test set (20%).

🔹 Step 3: Building the Classifier
The training data has been trained a Decision Tree Classifier on.

Tuned basic parameters for better performance

🔹 Step 4: Model Evaluation
Reticulated precision, perplexity matrix, and classification report.

Visualized the tree using plot_tree from sklearn


📊 Sample Output
Accuracy: 87.4%
The model showed a clear split pattern between yes/no subscriptions.
