# MARKDOWN FILE SYNTAX
## What is a Markdown?
### A MARKDOWN file is a text file created using one of several possible dialects of the Markdown language. It uses plain text formatting but contains inline text symbols that specify how to format the text


#### File extensionto denote a file that uses Markdown is .md

There are two types of syntax in a markdown file

-Basic Syntax
-Advanced Syntax
---

#### BASIC SYNTAX
These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

Element	Markdown Syntax

# H1
## H2
### H3


#### How to Bold a text
**This is a bold text**

#### Italic	
*This is a text with italics*

#### Blockquote	
> This is a blockquote

#### Ordered List	

1. First item
2. Second item
3. Third item

#### Unordered List	

- First item
- Second item
- Third item

#### Code	
`let arr=[1,2,3,4,5]`

#### Horizontal Rule	
---
#### Link	
[Google.com](https://www.google.com)

#### Image
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

#### Check out this program I wrote:

```c
#comment
x = 0
x = 2 + 2
what is x
```

```text
#comment
x = 0
x = 2 + 2
what is x
```


**What is Lorem Ipsum?**
```Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.```

**Why do we use it?**
```It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).```


**Where does it come from?**
```Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.```

*```The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.```*


#### This is a code block

```js
{
function formatMarkdown(text) {
return format(text);
} 
```

#### INLINE LINKS
<p>&nbsp;</p>
#### The following hyperlink to www.github.com has link text that says ""Visit GitHub!": 

[Visit GitHub!](https://www.github.com)


### AUTOLINK
<p>&nbsp;</p>
Please go to http://demo.dotcms.com to try out dotCMS for yourself.

### Anchor Links
<p>&nbsp;</p>
# Header with ID {#headid}

* List item 1 with ID {#listid1}
* List item 2 with ID {#listid2}

Create a link to : [Headline with ID](#headid)

### TABLE
<p>&nbsp;</p>
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |


| Name | Description          |
| ------------- | ----------- |
| Help          | ~~Display the~~ help window.|
| Close         | _Closes_ a window     


 Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        | $12 |
| zebra stripes | are neat        | $1 ||

### MISCELLANEOUS
* (C) becomes &copy;
* (R) becomes &reg;
* (TM) becomes &trade;
* -- becomes &ndash;
* --- becomes &mdash;
* ... becomes &hellip;
* << becomes &laquo;
* When *not* placed at the beginning of the line, >> becomes &raquo;
* "Text" becomes &ldquo;Text&rdquo;
