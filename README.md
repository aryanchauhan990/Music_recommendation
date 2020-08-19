# Music_recommendation
Music_item_based_recommendation

# THIS IS ITEM BASED MUSIC RECOMMENDATION PROJECT 

There are three types of recommendations:-
1.First is popularity based recommendation system which us naive recommendation system , which recommend/provide top songs regardless of songs that are liked by user/ more frequently listened by user.

2.Second is content based recommendation system , which predicts what will user like based on user past liked songs.

3. Third is collaborative based system, in which what a particular user like based on what other similar users like.

4. Many big companies such as Netflix, Hulu adopts hybrid approach i.e. mixture of second and third points explained above.

5. My project is based on Hybrid approach .


# About Project

1. I have used oneMillionsongdataset(http://labrosa.ee.columbia.edu/millionsong) that contains two files : (I)triplets_file(https://static.turi.com/datasets/millionsong/10000.txt)
which contains  user_id, song_id , listening_time.

(II) metadata_file(https://static.turi.com/datasets/millionsong/song_data.csv) which contains song_id, title, release_by, artist_name.

2.Million Songs Dataset is a mixture of song from various website with the rating that users gave after listening to the song. A few examples are Last.fm(http://labrosa.ee.columbia.edu/millionsong/lastfm), thisismyjam(https://labrosa.ee.columbia.edu/millionsong/thisismyjam), musixmatch(http://labrosa.ee.columbia.edu/millionsong/musixmatch).

3. I have used concept of cooccurence matrix(https://blogs.msdn.microsoft.com/carlnol/2012/06/23/co-occurrence-approach-to-an-item-based-recommender/) for recommendation of songs to a paritcular user(You can also refer anderw ng on youtube).

# Dependencies
1.pandas
2.scikit learn
3.numpy


# Credits 
1.Siraj Raval(Youtube)
2.towardsdatascience.com(https://towardsdatascience.com/how-to-build-a-simple-song-recommender-296fcbc8c85)
