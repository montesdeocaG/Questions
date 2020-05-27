
Chapter 3
1. Why is it hard to debug data corruption?
Bcause it will take long before you notice them, and when you do its hard to track what caused the corruption.

2. What are the basic concepts of Thrift?
Struct and Union.
Unions are for representing nodes while structs are representing edges.

3. Must schmas evolve over time?
Yes, because projects will evolve and requierements will change and it has to be cost efficient. 

4. May fields be renamed? Can you re-use field ID?
You may rename but you cannot use field IDs because thats how it is identified, otherwise it will create invalid data.



Chapter 4
1. Which are the requierements for master ds?
Write
    Efficient appends of new data
    Scalable storage
Read
    Support for parallel processing
Both
    Tunable storage nad processing costs
    Enforceable inmmutabilitly

2. What is vertical partitioning?
    Its also known as sharding, you partitionate vertically, for example for recent data.

3. What are the advantages of using a DFS?
   You will have control over the bytes of data, you have fault tolerance, if one machine goes down your data will still be backed up.
   
4. key vs DFS?
    The key is very prone to errrs such as random read/write, with a DFS you will be protected from this



    


