
<h1> 📧 Spam Email Classification </h1>
The aim of this project is to suspect the E-mails which consist of offensive, anti-social elements and block them which help in identifying the suspicious user.

<br>

Suspicious email detection is a kind of mailing system where suspicious users are identified by determining the keywords used by him/her. The keywords such as bomb, RDX, are found in the mails which are sent by the user. All these blocked mails are checked by the administrator and identify the users who sent such mails.

The given code is an implementation of a spam email classifier using the Multinomial Naive Bayes algorithm. The dataset used for training the model is "spam.csv", which contains labeled messages as either _"spam"_ or _"ham"_ (not spam). The dataset is read into a Pandas dataframe and preprocessed to drop unnecessary columns and map the "ham" and "spam" labels to numerical values.

The text data is then transformed into numerical features using CountVectorizer, which converts each message into a vector of word frequencies. The data is then split into training and testing sets using train_test_split, with a test size of 20% and a random state of 42 to ensure reproducibility.

A **Multinomial Naive Bayes** model is then trained on the training data using the fit method, and the accuracy of the model is evaluated on the test data using the score method. The model achieves an accuracy of around 98%, indicating that it is performing well in classifying spam and ham messages.

Finally, a function named "result" is defined that takes a message as input, transforms it using the CountVectorizer, and predicts whether it is spam or not using the trained model. If the prediction is 1, it is classified as spam, and if it is 0, it is classified as ham. The function then prints the corresponding output message.

Overall, the code provides a simple and effective implementation of a spam email classifier using the 
<a href = "https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html" target="_blank">
Multinomial Naive Bayes algorithm. </a> It can be easily adapted to other datasets and classification tasks by modifying the preprocessing steps and the choice of machine learning algorithm.




## 🗃️ Table of Contents 
<ul>
<li> Getting Started </li>
<li> Tools </li>
<li> Resources </li>
<li> Contributing</li>
<li> Bug Reports and Feature Requests </li>
<li> Code of Conduct </li>
<li> Credits </li>
<li> License </li>

</ul>

## ▶️ Getting Started
If you're new to web development, here are some resources to help you get started:

<ul>
<li> <a href = "https://www.ibm.com/docs/en/i/7.1?topic=communications-socket-programming"> IBM : Introduction to Socket Programming </a> </li>
<li> <a href="https://scikit-learn.org/stable/" target="_top"> Scikit-Learn : Simple and efficient tools for predictive data analysis  </a></li> 
<li>  <a href="https://monkeylearn.com/machine-learning/#:~:text=Machine%20learning%20(ML)%20is%20a,to%20make%20their%20own%20predictions." target="_top"> MonkeyLearn : What is Machine Learning? </a> </li>
</ul>

## 🔨 Tools
Here are some tools that can help you streamline your web development workflow:
<ul>
<li>Jupyter Notebook / Google Colab Notebook - A powerful and customizable code editor.
</li>

<li>Git - A version control system for tracking changes in your code</li>
</ul>

## 📖 Resources
Here are some additional resources for web development:
<ul>
<li> <a href = "https://stackoverflow.com/questions/tagged/machine-learning"> Stack Overflow </a> : A community-driven Q&A site for programming questions</li>

<li><a href="https://machinelearningmastery.com/" target = "_blank"> Machine Learning Mastery </a> : A website that provides tutorials and courses on various aspects of machine learning, including deep learning, natural language processing, and time series forecasting.</li>
<li><a href="https://realpython.com/python-sockets/" target = "_blank"> Python Socket Programming Tutorial </a>:  A tutorial on socket programming in Python, with code examples and explanations. </li>
<li><a href="https://www.kaggle.com/" target = "_blank"> Kaggle </a> : A platform that hosts machine learning competitions and provides datasets for practice and learning.</li>
</ul>

## 🙌 Contributing

We welcome contributions from the community! Here are some guidelines to follow:

- Please fork the repository and create a new branch for your contribution.
- Make sure to follow the existing code style and conventions.
- Write clear and concise commit messages.
- Submit a pull request with your changes and a description of what you added or fixed.

## 🐞 Bug Reports and Feature Requests

If you find a bug or have a feature request, please open an issue on the project's [issue tracker](https://github.com/example/project/issues) with a detailed description.

## 🚦 Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](https://github.com/example/project/blob/main/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## ©️ Credits
This was created by [Lakshya Singh](https://lakshya-gg.github.io/) . If you have any questions or feedback, please feel free to contact me at @**lakshyasinghwork@gmail.com**.


## 📌 License
This game is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html). Please see the [LICENSE.md](https://github.com/Lakshya-GG/Dash-Game/blob/main/LICENSE.md) file for more information.
