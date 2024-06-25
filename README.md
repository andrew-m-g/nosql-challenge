# nosql-challenge

3rd party code sources:
    class exercises
    chat gpt
    tutor

code functions:
    NoSQL_setup_starter:
        -creates an instance of a mongo client
        -accesses the uk_food database, displays a single document from the single collection
        -assings the collection to a variable
        -inserts a new document into the collection
        -updates the inserted document with the correct BusinessType ID
        -queries for and deletes all documents with "Dover" in LocalAuthorityName then runs a confirmation
        -performs a mass update on longitude and latitude fields to decimals using update_many()
    NoSQL_analysis_starter:
        -queries which establishments have a hygiene score equal to 20. Converts the query into a pandas dataframe and displays the first 10 rows
        -queries which establishments in London have a RatingValue greater than or equal to 4 using the $regex operator, then converts the query into a pandas dataframe and displays the first 10 rows
        -queries the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours". Uses a sort and limit function in addition to the query then converts and displays the results in a pandas dataframe
        -queries wow many establishments in each Local Authority area have a hygiene score of 0 by building an aggregation pipeline consisting of a match query, group_query and sort_query with the results then being converted and displayed in a pandas dataframe format
