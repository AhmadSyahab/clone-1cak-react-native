CloneWancak
===========

app using react-native, react-redux
just using store management not yet connect with backend , so state will lose when refresh
next feature will add realm

MVP
----
Using upload feature. Every posted picture can be commented and like. 

SCHEMA OF COLLECTIONS
---------------------

We have two (2) collections. users and memes. Schema for users are:

1. Name type String
2. User Name type String
3. Password type String
4. Age type Number
5. Email type String

Schema for memes are:

1. Title type String
2. Image URL type String
3. Author type ObjectType of Users Id
4. Funny type array or ObjectType of Users Id (likes)
5. comments type array of ObjectType of Users Id (comment count)
6. Created At type Date
7. Updated At type Date

For using this api you must install npm or yarn
and for start you must react-native link & react-native run-android
