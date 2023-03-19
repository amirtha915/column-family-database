HBbase is linearly scalable and it integrates with source and destination

HBase is most effectively used to store non-relational data, accessed via the HBase API. Apache Phoenix is commonly used as a SQL layer on top of HBase allowing you to use familiar SQL syntax to insert, delete, and query data stored in HBase.

HBase is a popular NoSQL database with high throughput and low latency. HBase is Java-based Not Only SQL i.e. NoSQL database which runs on top of Hadoop.

Hotel_details
Customer_details
Liquid and cool products

The Hotel_details stores information about hotel details including 1)name 2)cost 3)item 4)location

The Cus_details stores information about customer details including 1)name 2)age 3)location 4)mailid

The liquid and cool products stores information including flavor,name,price

In this family table there are three columns named hotel_details,cus_details and liquid and cool products information contain three rows
![Screenshot (85)](https://user-images.githubusercontent.com/124859726/226177620-0ba5fc41-a028-4ff4-a4be-78fc2ea41379.png)

updated the values of row no 02 by changing their hotel_details.And in the second row inserted the location information in the customer details column using put keyword.finally deleted the last row of liquid and cool products that they have dropped using deleted keyword

![Screenshot (84)](https://user-images.githubusercontent.com/124859726/226177704-fb31ab48-98a7-4abe-9c37-087f0ed7eaa4.png)

column family database stores data in column families as rows that have many columns associated with row key.It is a database object.Each row has unique key.And it is continue to generate and collect more data
