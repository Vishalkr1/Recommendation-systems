# Recommendation-systems
A blog post recommendation engine based on collaborative filtering and content based filtering.

Dataset Details

There are 3 files.

users.csv- Users dataset containing user's details like name, id, gender etc.

posts.csv- Post dataset containing posts details like title category etc.

views.csv- Views dataset contains the mapping which user views which post(s)

Users:

 _id: a unique alphanumeric id of the user (string)

 name: Name of user (string)

 gender: Gender of user (male | female)

 academics: Education of the use (undergraduate | graduate)

Posts:

 _id: a unique alphanumeric id of the post (string)

 title: Title of the post (string)

 category: Category of the post (string)

 post_type: Type of the post (blog | artwork | skill | project)

Views:

 user_id : a unique alphanumeric id of the user (string)

 post_id : a unique alphanumeric id of the post (string)

 time stamp: timestamp of when user viewed the post (ISO time format)
