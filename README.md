# Book_Recommendation_system
Book Recommendation System based upon a Book Review

<h3>Link of Data Set</h3>
http://www2.informatik.uni-freiburg.de/~cziegler/BX/ <br>
The Book-Crossing dataset comprises 3 tables.
<ul style="list-style-type:disc;">
  <li>BX-Users</li>
Contains the users. Note that user IDs (`User-ID`) have been anonymized and map to integers. Demographic data is provided (`Location`, `Age`) if available. Otherwise, these fields contain NULL-values.
 </ul>
 
 <ul style="list-style-type:disc;">
  <li>BX-Books</li>
Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (`Book-Title`, `Book-Author`, `Year-Of-Publication`, `Publisher`), obtained from Amazon Web Services. Note that in case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavours (`Image-URL-S`, `Image-URL-M`, `Image-URL-L`), i.e., small, medium, large. These URLs point to the Amazon web site.
 </ul>

<ul style="list-style-type:disc;">
  <li>BX-Book-Ratings</li>
Contains the book rating information. Ratings (`Book-Rating`) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.
 </ul>


The books dataset provides book details. It includes 271,360 records and 8 fields: ISBN, book title, book author, publisher and so on.<br>This dataset provides the user demographic information. It includes 278,858 records and 3 fields: user id, location, and age.<br>

 It contains 1.1 million ratings of 270,000 books by 90,000 users. The ratings are on a scale from 1 to 10.The data consists of three tables: ratings, books info, and users info from three diffrent tables.
 
 <h2>Ratings Data</h2>
 The ratings data set provides a list of ratings that users have given to books. It includes 1,149,780 records and 3 fields: userID, ISBN, and bookRating.The ratings are very unevenly distributed, and the vast majority of ratings are 0.<br>

<h3>Software Required</h3>
1. Anaconda <br>
2. Jupiter  </br>

<h3>Library Used</h3>
1. Numpy  <br>
2. Pandas <br>
3. Matplotlib  <br>
4. Seaborn  <br>

<h2>Objective</h2>
 The Book Recommendation System aims to provide the best suggestion to the user by analyzing the buyer’s interest. The quality and the content are taken into consideration by employing content filtering, association rule mining and collaborative filtering.

<h2>Project Overview</h2>
 The booming technology of the modern world has given rise to the enormous book websites. This makers the buyers to choose the best books to read as books play a vital role in many people’s life. The various kinds of books come into existence on day to day basis. So in order to eliminate this critical situation the recommendation system has been introduced in which the suggestion on the various books can be provided based on the analysis of the buyer’s interest. The Book Recommendation System is an intelligent algorithm which reduces the overhead of the people. This provides benefit to both the seller and the consumer creating the win-win situation. The E-commerce site to network security, all demands the need for the recommended system to increase their revenue rate. The content filtering, association rule mining and collaborative filtering are the various decision making techniques employed in the recommendation system as it helps buyers by the strong recommendations as there are various books, buyer’s sometimes cannot find the item they search for. The Book Recommendation System is widely implemented using search engines comprising of data sets.

<h2>Proposed System</h2>
The online book recommendation system involves various techniques for providing effective suggestion for the buyers. The association mining, collaborative filtering and content filtering are the three widely employed methods for strong impact using search engines.  The content based filtering system is one in which the recommendation to the buyers are provided based on the items they have searched for. The items are generally in the form of text, comprising e-mail and web pages. This method analyse the similarities between the items to bring out the best recommendation.
