In the e-commerce industry, personalized recommendations can help customers find products they are interested in and improve their overall shopping experience. IBM wanted to develop a recommendation system using their Watson Studio dataset and Collaborative Filtering algorithm to suggest products to users based on their browsing and purchase history.

The task of this project was to build a recommendation system that would suggest products to users based on their interactions with articles on the IBM platform. The recommendation system needed to be able to provide personalized recommendations to users using collaborative filtering or rank-based methods for existing users and content-based methods for new users.

To achieve this task, the project performed exploratory data analysis to gain insights into the data. A user-article interaction matrix was created to represent the interactions between users and articles, and the similarity between articles was calculated using the dot product to create an article similarity matrix. The project then implemented different recommendation systems, such as rank-based recommendations, user-user based collaborative filtering, content-based recommendations, and matrix factorization. The performance of the model was evaluated using precision, recall, and F1-score metrics.

The developed recommendation system was able to provide personalized recommendations to users based on their interactions with articles on the IBM platform. Collaborative filtering and rank-based methods were used for existing users, while content-based methods were used for new users. The project's evaluation using precision, recall, and F1-score metrics showed that the model performed well, indicating that the system can help improve customer satisfaction and increase sales for IBM's e-commerce clients.

Extra : A matrix decomposition is performed on the user-article matrix to better predict new articles a user might be interested in.

### **Libraries and Installations**
The project is implemented using Python 3.x and the following libraries are used:

- nltk
- numpy
- pandas
- re
- scikit-learn
To run this project, you need to have these libraries installed on your system. If not, you can install them by running the following command in your terminal/command prompt:

```
    pip install nltk numpy pandas re scikit-learn
```

### **Data**
The dataset used in this project is a subset of real data from the IBM Watson Studio platform. The data contains information on user interactions with articles, including article titles and article IDs.

### **Conclusion**
This project showcases the implementation of a basic recommender system. The system uses a combination of different recommendation techniques to provide personalized recommendations to each user. The project can be further improved by incorporating additional features, such as article content or user profiles, and using more advanced algorithms.

Check out my Medium post about the project [here](https://medium.com/@seunshix/recommendation-systems-how-machine-learning-is-transforming-the-way-we-discover-content-6132bcb54989)
