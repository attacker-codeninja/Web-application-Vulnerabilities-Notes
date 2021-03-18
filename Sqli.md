# Finding the number of columns in the table with union statement
```
'+union+select+null,null--
```

Increase the number of null's when u dont get any error on the page , the number of null's are the number of columns

# Finding the data-type of the column

Replace the null with 'a'/1 to check what data type the column has

# Using String concatination to get more useful data

We can use string concating to get more useful data from tables

like we can extract the username and password from a table

'+union+select+null,username+||+'~'+||+password+from+users--

the '||' is the symbol
