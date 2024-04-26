# Module_6_Data_Sourcing_Challenge

In this challenge we created a system so people can find movie reviews and related movies based on two different sources: The New York Times API and The Movie Database. The data text extracted from these APIs can later be used with natural language processing methods as per the bootcamp challenge document.

Authors & Citation

Shephali Dubey
Xpert learning to test some codes
Alberto Aigner, Kalvin Anglin & Ethan McManus's feedback for a few errors

Summary
First you import libraries and dependencies, set the NYT & TMDB API key variables in .env environment and save in gitignore or seprate directory so you don't end up uploading the API key on the public repository when uploading the challenge solution and created csv file. Set the base and query urls to make data requests , set the various filters and lists, ensure that each query response equals to 200 before proceeding as any other request response result indicates the request was not successful so no data will get pulled. Set loop to iterate through the reviews list pulled from NYT API, extract and dump data into a json format, convert to dataframe and extract titles to create titles list. Then use those titles list to pull movie reviews from TDMB API , use try and except clause to to search for full movie title details , extract key information to be saved as dictionary , converted in Json format and then in a dataframe, merge & clean the NY Times reviews and TMDB Dataframes based on title and export as a .csv file.
