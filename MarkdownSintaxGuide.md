# Markdown Language Sintax Summary
  ## For new users

This document is to summarize the MD language basic sintax, and to serve as a basic guide to any person new to this topic.

1. Titles
2. Lists
   1. Unordered Lists
   2. Ordered Lists
1. Blockquotes
2. Nested blockquotes
3. Bold text
4. Italic text
5. Bold and Italic text
6. Code
7. Scape wildcards
8. Images
9. Horizontal rules
10. Links
    1. Title links
    2. Turning URLs into links
1. Tables
2. Markdown Complete Guide




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
  FROM TABLE_A
  WHERE code like '%9961-%'
  ;
  ````
  **R**
  ````r
  vector <- c(1,2,3,4,5)
  length(vector)
  ````
+ If we just want to indicate a **function** or a specific word, we can use only 1 or 2 (It`s more common 2 since the keyboard will generate 2 automatically):
  
  >The function `AVG` is used to calculate the average of a numeric attribute. 
+ Sometimes we will need to use one of above **wildcards** in a sentence, or to reference it. In these case, we will need to **scape the default use**, and to avoid triggering the functionalities, we will need to place a backslash ``\`` before the wildcard.
+ For **images**,we need to open the image and copy the image to the clipboard and paste it in the document, Markdown will automatically format the image and embed it, normally with the following format: ``![image](link to the asset)``. To **add a link to an image**, enclose the Markdown for the image in brackets, and then add the link in parentheses.
+ If we want to change the topic, and **insert a horizontal rule**, use 3 or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

---

+ To **create a link**, enclose the link text in brackets (e.g., [Bismart Trainings]) and then follow it immediately with the URL in parentheses (e.g., (https://bismartbiss.sharepoint.com/Formacion/Documentos%20Formacion/Forms/AllItems.aspx?viewid=9a77c0ea%2D6fad%2D40aa%2D976d%2D914bec8e9ae0)). You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To **add a title**, enclose it in quotation marks after the URL.
  
>[Bismart Trainings](https://bismartbiss.sharepoint.com/Formacion/Documentos%20Formacion/Forms/AllItems.aspx?viewid=9a77c0ea%2D6fad%2D40aa%2D976d%2D914bec8e9ae0 "Link to all recorded trainings and documentation available at Bismart")
+ To quickly **turn a URL or email address into a link**, enclose it in angle brackets.

<https://www.markdownguide.org>

<fake@example.com>

+ Finally, to create a table, the pipe symbol &#124; can be used. Let's use as example of a table of elements that can be scaped with a backslash in Markdown:

|Wildcar Symbol|Description|
|:---:|:----:|
|``\``|backslash|
|\`|backstick|
|``*``|asterisk|
|``_``|underscore|
|``{}``|curly braces|
|``[]``|brackets|
|``<>``|angle brackets|
|``()``|parantheses|
|``#``|pound sign|
|``+``|plus sign|
|``-``|minus sign (hyphen)|
|``.``|dot|
|``!``|exclamation mark|
|&#124;|pipe|

In the backend, what we are doing is the following:

&#124; Wildcar Symbol &#124; Description &#124;

&#124; :---: &#124; :----: &#124;

&#124; ``\`` &#124; backslash &#124; 

> Note that we use ``:`` on both side below the table headers, to indicate the allignment of the text. If we use only in the left side, all would be aligned to the left side. Also, we are using 3 or more hyphens to create the horizontal delimitation inside the table.

There are many other tips that can be learned with Markdown, please follow this link for the complete guide:

[MarkDown Guide](https://www.markdownguide.org/)

