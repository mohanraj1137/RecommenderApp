# RecommenderApp
"company":CODTECH  IT SOLUTION
"NAME" :MOHANRAJ M
"INTER ID":CT04DZ1729
"DOMAIN":JAVA
"DURATION":4 WEEKS
"MENTOR": NEELA SANTOSH
This Java program implements a user-based collaborative filtering recommendation system using the Apache Mahout library. The goal is to suggest relevant products or items to a user based on the preferences of other users with similar interests. The main class, RecommenderApp, belongs to the com.codtech package and handles loading user-item rating data, computing similarity between users, identifying the nearest neighbors, and generating recommendations. The data is loaded from a file named data.csv, which contains entries in the format of userID, itemID, and rating. The program uses the Pearson Correlation Similarity method to measure the similarity between users based on their ratings. Then, it determines the two closest users (neighbors) for the target user. The recommendation engine is built using Mahout’s GenericUserBasedRecommender, which processes the model, similarity, and neighborhood information. When executed, the program attempts to recommend two items for user 1 using Mahout’s recommend() method. If the recommendation list is not empty, it displays the recommended item IDs along with the estimated preferences, which represent predicted ratings based on user similarity. If no recommendations are found, it notifies the user accordingly. This project demonstrates a real-world application of collaborative filtering, similar to how platforms like Netflix or Amazon suggest products. It highlights key concepts such as user similarity, neighborhood formation, and rating prediction. Although the implementation is basic, it successfully shows how a recommendation engine works and can be further enhanced with a larger dataset, integration into a user interface, or transition to an item-based recommendation system.
"output"
(https://github.com/user-attachments/assets/006e256d-41d2-410b-9f09-41f1319f5400)
