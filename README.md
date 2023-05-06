# starsstudio
To use this script, you will need to have following libraries:
requests
json
pandas
scikit-learn


The code will make a request to a JSON endpoint to retrieve the product data, preprocess the data, 
and then find the alternates of the same product in the store. 
This will print the groups of alternate products.we have used CountVectorizer and cosine_similarity
