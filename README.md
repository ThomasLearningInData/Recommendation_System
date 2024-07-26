# Recommendation System on Glasgow's restaurants
Create a recommendation system based on Glasgow's restaurants. The data are collected from Yelp. 

This recommendation system utilizes a transformer model (DistilBERT) to provide personalized restaurant recommendations based on various user-specified criteria such as tags (e.g., cuisine type), location, normalized score, and normalized price. The system generates embeddings for each feature and combines them using specified weights to reflect their importance. It then calculates the cosine similarity between the query and the dataset items to identify the most similar restaurants. The results are sorted by the normalized score in descending order, ensuring the highest quality recommendations are displayed first.

### Adjustable parameters
In here, I consider tag > location > score > price.

<img width="481" alt="螢幕截圖 2024-07-25 下午5 45 00" src="https://github.com/user-attachments/assets/3499c667-aa74-4532-8262-ae4bff22b016">

### Result
The recommended items are sorted primarily by the normalized score in descending order, followed by other criteria (tags, location, price) in ascending order.

The results are displayed with relevant details including the name, rating, normalized score, normalized price, location, and tag of each restaurant.
The system will output the top 5 recommended restaurants that best match the specified criteria, displaying the name, rating, normalized score, normalized price, location, and tag of each restaurant.
<img width="850" alt="螢幕截圖 2024-07-25 下午5 45 27" src="https://github.com/user-attachments/assets/005de776-5e11-47db-a260-edcc7fff68fe">
