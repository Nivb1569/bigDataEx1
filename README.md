# bigDataEx1

Name: Niv Baumel.

Id: 322755737

Exercise 1:

Q1. Six files (without the success file).

Q2. No, the number of mappers is not change because the number of the reducers.

Q3. Yes, changed to six.

Q4. Yes cause the number of reducers defines how many output files are created.

Q5. The value represents the numebr of intermidate map output segment that the Hadoop shuffle and combine
befor sending them to the reducers.
The calculate is : number of mappers x number of reducers
this because each mapper produce output for every reducer, all these segments must be merged befor the reduce is run.

Exercise 2:

Q1. In the mapper only.
