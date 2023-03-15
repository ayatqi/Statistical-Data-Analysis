# Statistical Data Analysis

Two datasets were given : “ppv.csv” which contains 100 vaccination centres’ locations and “people.csv” which consists of 10000 vaccines’ locations. Based on both datasets, we were tasked with matching each person from the “people.csv” file to their nearest vaccine centre. This matching was done by using the address coordinates(latitude and longitude). Our computer specification, ASUS Vivobook has the highest performance and HP Notebook has the lowest performance.

For the program we have created four methods to calculate the distances: Great Circle, Haversine, Haversine Vector and Euclidean. Three different libraries were used: scipy, haversine and geopy. In the program we have three for loops:the first loop runs the program 50 times, which will calculate the execution time for each loop then save the inside time array. To find execution time a time library was import, and to calculate the execution time we subtracted the end time from start time. In the second for loop, it will loop based on the number of indexes in the “people.csv” file. Then we created a distance empty array and coords 1 tuple which consist of the latitude and longitude of each person depending on the loop number.For the third for loop, it will loop based on the number of indexes in the “ppv.csv” file.

