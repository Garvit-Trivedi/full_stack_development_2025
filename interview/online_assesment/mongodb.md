MongoDB and C++/STL Interview Questions
MongoDB Long-Answer Questions

Explain the differences between embedded documents and document references in MongoDB. When would you choose one over the other?
Describe how MongoDB's aggregation pipeline works. What are the key stages and their purposes?
Compare $lookup in MongoDB with SQL joins. What are the limitations of $lookup?
How does indexing improve query performance in MongoDB? Explain with examples.
What is sharding in MongoDB, and how does it help with scalability?
Explain the CAP theorem and how MongoDB fits into it.
Describe how MongoDB ensures data durability with write concerns and journaling.
What are the advantages of using a document database like MongoDB over a relational database?
How does MongoDB handle transactions, and what are their limitations?
Explain the difference between find() and aggregate() in MongoDB.
What is a covered query in MongoDB, and how does it improve performance?
Describe how TTL (Time-To-Live) indexes work in MongoDB. Provide a use case.
How does MongoDB handle schema validation? Explain with an example.
What are MongoDB's replication and failover mechanisms?
Explain the role of the \_id field in MongoDB documents. Can it be customized?
What is the purpose of the explain() method in MongoDB? How do you interpret its output?
How does MongoDB handle concurrency with its locking mechanism?
Describe the differences between deleteOne(), deleteMany(), and drop().
What are MongoDB's geospatial query capabilities? Provide examples of $near and $geoWithin.
How do you model a many-to-many relationship in MongoDB?
What are the trade-offs between embedding documents and referencing them?
Explain how partial indexes work and when they should be used.
How does MongoDB handle case-insensitive searches? Compare $regex and text indexes.
What is a capped collection in MongoDB? When would you use one?
Describe MongoDB's oplog and its role in replication.

MongoDB Coding Questions

Insert a document into the books collection with fields: title, author, genres (array).
Find all books published between 2010 and 2020 using comparison operators ($gte, $lte).
Count the number of books in the "Science Fiction" genre.
Update a book's publication year from 2015 to 2016 using $set.
Delete all books with rating less than 3.
Create a compound index on author (ascending) and publication_year (descending).
Use $lookup to join books with authors and display each book's author details.
Aggregate data to find the average rating of books per genre.
Implement text search on a description field to find documents containing the word "fantasy".
Use $unwind to flatten an array of genres and group by genre name.
Create a unique index on the isbn field to prevent duplicates.
Write a query to find books that are either "Mystery" or "Thriller" genre ($in).
Use $elemMatch to find books that have at least one review with rating above 4.
Backup the books collection using mongodump with compression enabled.
Restore the books collection from a backup while preserving indexes.
Create a TTL index on a last_updated field to expire documents after 90 days.
Validate documents in a collection to ensure title exists and page_count is positive.
Use $regex to find books whose titles start with "The" (case-insensitive).
Implement pagination using limit() and skip() to fetch page 3 of books (15 per page).
Sort books by title (A-Z) and then by rating (descending).
Use $group to count how many books each author has written.
Update multiple documents to increment all books' ratings by 0.1 using $inc.
Drop all indexes from the books collection except the \_id index.
Create a capped collection named activity_logs with a size of 5MB.
Simulate a transaction to transfer a book between two categories (if using MongoDB 4.0+).

