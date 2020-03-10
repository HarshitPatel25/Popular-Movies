# Popular-Movies
An app that displays details about popular playing movies.
It also allows the user to view and explore his favourite movies while in offline mode.
Created as a part of Android Developer Nanodegree provided by Udacity.
Note: In order to build your own app, add your own API key obtained from http://themoviedb.org to build.gradle:Module as


buildTypes.each{
        it.buildConfigField 'String', 'MOBDB_API_KEY',"\"api_key\""
    }
    
    
Replace api_key with your own API KEY.

#Libraries Used :
Butterknife
Retrofit
Glide
Simple Sql Provider
