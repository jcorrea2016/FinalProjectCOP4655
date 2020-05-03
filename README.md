# FinalProjectCOP4655
Final project for COP 4655 this is a COVID 19 Tracker App made in Android Studio written in Java

For USA Statistics(api used: disease.sh also known as corona.lmao.ninja):
classes include the response object where the data from the api is stored. I used the 'get' methods for JSONObject.

For States Statistics(api used: disease.sh also known as corona.lmao.ninja):
Similar implementation to the USA Statistics, however there is a child display activity, as the onclick listener was not functioning properly

For News Headlines(api used: newsapi.org):
Used a for loop for indexing, and the JSONObject methods to fetch and format the data

For Country Rankings(api used: disease.sh also known as corona.lmao.ninja):
For this api I had to combine a little bit of both elements from the USA Statistics and the News Headline Activities. the JSONObject Request was switched to a JSONArrayRequest as iterating through the returned JSON with an object was a bit challenging, the array made things easier to index. A similar for loop was used from the News Headlines Activity

Login Service used: FirebaseAuth
Method: email and password
