## Instructions for students:

### Find the Word

Create a program to search files for a word. The program should accept a word and a file path.

-   Make sure to create index.js and require filesystem and path, use createReadStream to read the data.txt file from this repository.
-   Make sure you separate the data in chunks, then find the word 'localhost', and you should also be able to find any word that you will add as an argument.

**Bonus**

-   When finding a word or even a space from other files make sure you are finding the correct amount of times is appears.

See following example

```bash
$ node index.js
Reading chunk 1
Reading chunk 2
Reading chunk 3
Reading chunk 4
Reading chunk 5
Reading chunk 6
Reading chunk 7
Reading chunk 8
End of data
Number of chunks: 8
Found 'localhost' 1 times
```

-   When you pass the argument to the program as expected the output should look like the following:

```bash
$ node index.js function
Reading chunk 1
Reading chunk 2
Reading chunk 3
Reading chunk 4
Reading chunk 5
Reading chunk 6
Reading chunk 7
Reading chunk 8
End of data
Number of chunks: 8
Found 'function' 8 times
```

### Rules

-   This is an individual assignment.
-   Deadline: 30 minutes.
-   Use **Git properly**
