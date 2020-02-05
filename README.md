# r-custom-function-training
A training resource on how to create custom functions in R
---
title: "Creating custom functions in R"
authore: Jeremy Schreifels
output: html_notebook
---

You are already familiar with functions in R. Every time you use library(), readcsv(), mean(), ggplot(), or other action in R you are calling a function. You can use the power of custom functions to improve your own code. Some advantages of using functions, include:

1. You can reduce the risk of copy/paste errors (e.g., forgetting to update a variable in the pasted code).
2. You can easily  document your code and use descriptive names, making it easier for you and others to read your code in the future.
3. If changes are needed, you only have to make the changes to one code block (i.e., the code in the function).
4. You can limit the scope of your variables to only the function.

In general, you should consider creating a function whenever you are copying and pasting a code block that doesn't require signficant changes. 

Creating your own functions in R might seem intimidating, but it is quite easy and custom functions can reduce errors, improve consistency, and enhance readability. 

The attached R Notebook includes sample code.

For further information, refer to:
- [How to write and debug an R function](https://www.r-bloggers.com/how-to-write-and-debug-an-r-function/) by Slawa Rokicki
- [Writing Functions in R](https://rpubs.com/williamsurles/292234) by William Surles
