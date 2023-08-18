Markdown... What is that? Let's take a look to the original description:

>A lightweight markup language for creating formatted text using a plain-text editor. John Gruber created Markdown in 2004 as a markup language that is easier to read in its source code form. Markdown is widely used for blogging and instant messaging, and also used elsewhere in online forums, collaborative software, documentation pages, and readme files.

Ok, let's stop right there. See that last part "collaborative software, documentation pages and readme files"? That's the key.

In summary, markdown is a **format language** that can be saved as a file extension md, and which **gives format to the text by using specific wildcards, behaving in that aspect as any other programming language.** In addition, markdowns are widely used in the data community and as good practice for creating **data project documentation.**

The most famous document would be the **README.md**, which essencially are **descriptive information about the project, porpuse, needed packages/libraries, considerations and limitations.** This help final users, programmers, and any person working in a data project to **understand better a project.**

Another **important aspect** to comment for data scientists and statistics, is that markdown has been extended to **Rmarkdown**, meaning, you can create a complete **script in markdown with chunks of code written in R, and execute it to generate informs and data projects** in Rstudio IDE.

[More about Rmarkdown and Rstudio](https://en.wikipedia.org/wiki/RStudio#Packages)

In this article, **the aim is focused on giving the proper description about the specifics of the language, functionalities, so that any person interested in learning this resourceful language, can have a solid base for starting to test and create .md files.**

>It's important to understand that it's not limited to data projects. Markdown language can be used in any text editor and executed by compatible interpreters for as many different porpuses. Personally, I use it because of 2 main reasons. It's needed in data mining projects and it's better that most text editors in terms of functionalities. 

At the end, a link to this article in Markdown code will be provided, that way, you can jump and check how it would look. You will notice it's easly readible, that's the first and best of Markdown characteristics.

Let's begin with an index of what we will cover:

1. Titles
2. Lists
   1. Unordered Lists
   2. Ordered Lists
3. Blockquotes
4. Nested blockquotes
5. Bold text
6. Italic text
7. Highlight text
8. Bold and Italic text
9. Embed Code
10. Scape wildcards
11. Images
12. Horizontal rules
13. Links
    1. Title links
    2. Turning URLs into links
14. Tables
15. Task Lists
16. Strikethrough
17. Footnotes
18. Next Steps!


# TITLES

To create a **title**, use ``#``. The bigger text title size is with one ``#``, the more used, the smalled the text will be.


![TitleCarbon](image-1.png)

>Now that we know more or less the structure, let's go over the other topics of the guide :)


# LISTS

To create an **unordered list**, add dashes ``-``, asterisks ``*``, or plus signs ``+`` in front of line items. Indent one or more items to create a nested list.

![ListCarbon](image-2.png)

To create an **ordered list**, use numbers as usual:
1. This is the first element
2. Second...
  
# BLOCKQUOTES

To create a **blockquote**, use ``>``:
  >This is a blockquote, here something interesting could be explained.
A blockquote can be **nested**:
  > First level
  >
  > First level still
  >> Second level! (See we used 2 intead of one) ``>``.

![BlockquoteCarbon](image-3.png)

# BOLD TEXT

To **bold** text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters. Eg: I just love **bold text**. Love**is**bold.

![BoldCarbon](image-4.png)

# ITALICIZE TEXT

To **italicize** text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters. Italicized tezt is the *cat's meow*.
**Bold and Italic** has 3 asterisks. ***This is REALLY IMPORTANT***.

![ItalicCarbon](image-5.png)

# HIGHLIGHT TEXT

This isn’t common, but some Markdown processors allow you to highlight text. The result looks like this. To highlight words, use two equal signs (==) before and after the words.

![highcarbon](image-6.png)

The rendered output looks like this:

I need to highlight these ==very important words==.

# EMBED CODE

To **embed code**, you should use 3 or 4 \``` symbols, and specify the language at the beggining, followed by a line with the code, and finish the block with another 3 or 4 \``` (see image below):
  
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
If we just want to indicate a **function** or a specific word, we can use only 1 or 2 (It`s more common 2 since the keyboard will generate 2 automatically):
  
  The function `AVG` is used to calculate the average of a numeric attribute. 
  
# SCAPING WILDCARDS

Sometimes we will need to use one of above **wildcards** in a sentence, or to reference it. In these case, we will need to **scape the default use**, and to avoid triggering the functionalities, we will need to place a backslash ``\`` before the wildcard.

This is the tipical behaviour of regular expressions, which I introduced to you in my previous article, that you can check by clicking this [link](https://www.linkedin.com/pulse/regular-expressions-your-best-friend-jose-antonio-piedehierro-arias%3FtrackingId=XM66tjSiSaqGki7rDKtdJQ%253D%253D/?trackingId=XM66tjSiSaqGki7rDKtdJQ%3D%3D&lipi=urn%3Ali%3Apage%3Ad_flagship3_publishing_post_edit%3BQ44Tv3rXQCG4Np49NhlW0g%3D%3D).

# IMAGES

For **images**,we need to open the image and copy the image to the clipboard and paste it in the document, Markdown will automatically format the image and embed it, normally with the following format: ``![image](link to the asset)``. To **add a link to an image**, enclose the Markdown for the image in brackets, and then add the link in parentheses.

# HORIZONTAL RULES

If we want to change the topic, and **insert a horizontal rule**, use 3 or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

---

# LINKS

To **create a link**, enclose the link text in brackets (e.g., [Linkedin Profile]) and then follow it immediately with the URL in parentheses (e.g., (https://www.linkedin.com/in/jose-antonio-piedehierro-arias-707518105/)). You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. 

To **add a title**, enclose it in quotation marks after the URL.
  
[Linkedin Profile](https://www.linkedin.com/in/jose-antonio-piedehierro-arias-707518105/ "Link to my personal profile in LinkedIn")

To quickly **turn a URL or email address into a link**, enclose it in angle brackets.

<https://www.markdownguide.org>

<fake@example.com>

# TABLES

To create a table, the pipe symbol &#124; can be used. Let's use as example of a table of elements that can be scaped with a backslash in Markdown:

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


I need to highlight these ==very important words==.

> Note that we use ``:`` on both side below the table headers, to indicate the allignment of the text. If we use only in the left side, all would be aligned to the left side. Also, we are using 3 or more hyphens to create the horizontal delimitation inside the table.

# TASK LISTS

To create a task list, add dashes (-) and brackets with a space ([ ]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).

- [X] Write the press release
- [] Update the website
- [] Contact the media

![taskCarbon](image-7.png)

# STRIKETHROUGH

You can strikethrough words by putting a horizontal line through the center of them. The result looks like this. This feature allows you to indicate that certain words are a mistake not meant for inclusion in the document. To strikethrough words, use two tilde symbols (~~) before and after the words.

# DEFINITION LISTS

To create a definition list, type the term on the first line. On the next line, type a colon followed by a space and the definition.

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

# FOOTNOTES

To create a footnote reference, add a caret and an identifier inside brackets ([^1]). Identifiers can be numbers or words, but they can’t contain spaces or tabs. 

Add the footnote using another caret and number inside brackets with a colon and text ([^1]: My footnote.). You don’t have to put footnotes at the end of the document. You can put them anywhere except inside other elements like lists, block quotes, and tables.

![FOOTNOTESCARBON](image-8.png)


# NEXT STEPS!

There are many other tips that can be learned with Markdown, please follow this link for the complete guide:

[MarkDown Guide](https://www.markdownguide.org/)

As promised, check the following Github link to get the md file used to generate this article, in markdown code:

[Github Markdown Guide](https://github.com/jpiedehierroa/files/blob/main/MarkdownSintaxGuide.md)

As a bonus for those who have reached the very end of the article, I am sharing the page which has helped me as interpreter for screenshots of markdown code when creating it. You can select the background color, picture and the interpreter language!

[Carbon.sh](https://carbon.now.sh/)

Thanks for reading, drop a like if it has been useful, or even better, a comment!

See you around!