# Markdown Language Sintax Summary
  ## For new users

This document is to summarize the MD language basic sintax, and to serve as a basic guide to any person new to this topic.

- To create a **title**, use ``#``. The bigger text title size is with one ``#``, the more used, the smalled the text will be.
- To create an **unordered list**, add dashes ``-``, asterisks ``*``, or plus signs ``+`` in front of line items. Indent one or more items to create a nested list.
- To create an **ordered list**, use numbers as usual:
1. This is the first element
2. Second...
+ To create a **blockquote**, use ``>``:
  >This is a blockquote, here something interesting could be explained.
+ A blockquote can be **nested**:
  > First level
  >
  > First level still
  >> Second level! (See we used 2 intead of one) ``>``.
* To **bold** text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters. Eg: I just love **bold text**. Love**is**bold.
+ To **italicize** text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters. Italicized tezt is the *cat's meow*.
+ **Bold and Italic** has 3 asterisks. ***This is REALLY IMPORTANT***.
+ To **embed code**, you should use 3 or 4 \``` symbols, and specify the language at the beggining, followed by a line with the code, and finish the block with another 3 or 4 \``` (see image below):
  
  ![image](https://github.com/jpiedehierroa/files/assets/93861551/c6badcd9-2bb9-4d00-8ebd-25948734bc26)
  
  **Python**
  ````python 
  import pandas as pd

  pd = pd.read_csv (".......", parameter1, parameter2, ...)
  ````
  **SQL**
  ````sql
  SELECT *
  FROM TABLE
  WHERE 
  ````
  **R**
  ````r
  vector <- c(1,2,3,4,5)
  length(vector)
  ````
+ If we just want to indicate a **function** or a specific word, we can use only 1 or 2 (It`s more common 2 since the keyboard will generate 2 automatically):
  
  >The function `AVG` is used to calculate the average of a numeric attribute. 
+ Sometimes we will need to use one of above **wildcards** in a sentence, or to reference it. In these case, we will need to **scape the default use**, and to avoid triggering the functionalities, we will need to place a backslash ``\`` before the wildcard.
+ For **images**,we need to open the image and copy the image to the clipboard and paste it in the document, Markdown will automatically format the image and embed it, normally with the following format: ``![image](link to the asset)``.
+ 
