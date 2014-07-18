This project takes the NYC DOT layer of point data for parking signs and converts it into line segments representing the date and time the street cleaner comes down the street. The final data is in street_segments.txt.gzip and is a pg_dump of the database. (The aggregation of that data from point into segments is not covered here.)

It then uses the OpenGeo Suite to build a map of those segments, with a selector for each day the street cleaner comes.

Warning: There are a lot of dependecies in deploying OpenGeo suite.