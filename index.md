# Lab Report 2
## The first code changes worked on in lab 3
1. Here is a screenshot of the code change diff from Github 
![image](https://imgur.com/1YgbKw4.jpg)

2. Link to the test file for a failure-inducing input that prompted me to make that change

[link](https://github.com/WanyingXu666/markdown-parser/blob/main/MarkdownParseTest.java)

3.Show the symptom of that failure-inducing input by showing the output of running the file at the command line for the version where it was failing 

![image](https://imgur.com/Ynxf4Zk.jpg)

Therefore, we can see that there is one failure for the third test. The reason is the original ```MarkdownParse.java``` will consider the image link as a link. The bug is the program cannot identify the "!" for the inmage link. My tests are basically check if the outcome is the same as I expected.

## The second code changes worked on in lab 3
1. Here is a screenshot of the code change diff from Github 
![image](https://imgur.com/rxdZ5xa.jpg)

2. Link to the test file for a failure-inducing input that prompted me to make that change

[link](https://github.com/WanyingXu666/markdown-parser/blob/main/MarkdownParseTest.java)

3.Show the symptom of that failure-inducing input by showing the output of running the file at the command line for the version where it was failing 

![image](https://imgur.com/XXWLYc2.jpg)

Therefore, we can see that there is one failure for the fourth test. The reason is the original ```MarkdownParse.java``` cannot recognize the "()" without "[]" as a link. The bug is the program cannot identify the first two lines. My tests are basically check if the outcome is the same as I expected.
## The third code changes worked on in lab 3
1. Here is a screenshot of the code change diff from Github 
![image](https://imgur.com/x7f07BY.jpg)

2. Link to the test file for a failure-inducing input that prompted me to make that change

[link](https://github.com/WanyingXu666/markdown-parser/blob/main/MarkdownParseTest.java)

3.Show the symptom of that failure-inducing input by showing the output of running the file at the command line for the version where it was failing 

![image](https://imgur.com/AFtDzBO.jpg)

Therefore, we can see that there is one failure for the fifith test. The reason is the test-file2 has some paragraphs after the links, and that will create a loop. The bug is the program will let ```openBracket``` be -1 when it cannot find any openBracket. My tests are basically check if the outcome is the same as I expected.
