# Markdown Syntax Guide

### Table of Contents : 

- [Headings](#headings)  
- [Paragraphs](#paragraphs)  
- [Line Breaks](#line-breaks)  
- [Styling Texts](#styling-texts)  
- [Blockquotes](#blockquotes)  
- [Lists](#lists)  
- [Quoting Code](#quoting-code)    
- [Images](#images)  
- [Horizontal Rule](#horizontal-rule)   
- [Links](#links)  
- [Escaping Characters](#escaping-characters)   
- [Collapsible Section (Toggle)](#collapsible-section-toggle)          
- [Tables](#tables)
- [Syntax Highlighting](#syntax-highlighting)
- Footnotes
- [Task Lists](#task-lists)
- [Emoji](#emoji)
- [Mentioning people and teams](#mentioning-people-and-teams)

<br /> 

**_Note_**: Many Markdown applications allow you to use HTML tags in Markdown-formatted text. So, you can also create all the following markdown using HTML code.  

<br />

<!-- =================================================== HEADINGS ============================================ -->
## Headings

### #1 Markdown Method- 

    # Heading 1
    ## Heading 2
    ### Heading 3
    #### Heading 4
    ##### Heading 5
    ###### Heading 6

Output:

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

### #2 HTML Tags Method-

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```
Output :

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

### #3 Alternative Method for `<h1>` & `<h2>` tags-

```
Heading 1
=========
Heading 2
---------
```

Output :

Heading 1
=========
Heading 2
---------

<br/>

When you use two or more headings, Github automatically generates a table of contents which you can access by clicking 3 dots before README.md within the file header. Each heading title is listed in the table of contents and you can click a title to navigate to the selected section.  

<br/>

<!-- ======================================== PARAGAPHS =============================================== -->
## Paragraphs

To create paragraphs, use a blank line to separate one or more lines of text.

<br/>

<!-- ======================================= LINE BREAKS ================================================ -->
## Line Breaks

To create a line break or new line, use trailing white space (two or more spaces) or the `<br>` HTML tag at the end of the line. 

<br/>

<!-- ======================================== STYLING TEXTS ============================================= -->
## Styling Texts

### #1 Bold

    This is **bold text** 1
    This is __bold text__ 2
    This is b**old** text 3

Output:   

This is **bold text** 1  
This is __bold text__ 2  
This is b**old** text 3  

### #2 Italic

    This is *italicized text* 1
    This is _italicized text_ 2
    This is *italic*ized text 3
    
Output:  

This is *italicized text* 1  
This is _italicized text_ 2  
This is *italic*ized text 3 

### #3 Bold & Italic

    This is ***italic & bold*** text

Output:  

This is ***italic & bold*** text 1  
This is ___italic & bold___ text 2  
This is **_italic & bold_** text 3  
This is __*italic & bold*__ text 4  

### #4 Strikethrough

    Your ~~Deleted chats~~ will shown here.

Output:

Your ~~Deleted chats~~ will shown here.

<br/>

<!-- ============================================== BLOCKQUOTES ============================================== -->
## Blockquotes

```
> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus, et?
> 
> Velit pariatur quidem similique sequi eius nihil quas vitae. Doloribus, vitae repellat.
```
Ouput:  

> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus, et?
> 
> Velit pariatur quidem similique sequi eius nihil quas vitae. Doloribus, vitae repellat.

### #1 Nested Blockquotes

```
> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus, et?
> 
>> Lorem ipsum dolor sit amet. 
```
Output:  

> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus, et?
> 
>> Lorem ipsum dolor sit amet. 

### #2 Blockquotes with Other Elements

```
> #### Blockquotes Best Practices!
> 
> - Try to put blank line before...
> - ... and after a blockquote.
> 
> Without *blank lines*, this might not look right.
```
Output:  

> #### Blockquotes Best Practices!
> 
> - Try to put blank line before...
> - ... and after a blockquote.
> 
> Without *blank lines*, this might not look right.

<br/>

<!-- ================================================ LISTS ============================================= -->
## Lists

### #1 Ordered Lists

To create, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

```
1. Item 1
2. Item 2
3. Item 3
    1. Sub-item 1
    2. Sub-item 2
5. Item 4
```
Ouput:  

1. Item 1
2. Item 2
3. Item 3
    1. Sub-item 1
    2. Sub-item 2
5. Item 4

### #2 Unordered Lists

To create, add dashes (-), asterisks (*), or plus signs (+) in front of line items.

```
- Item 1
- Item 2
    - Sub-item 1
    - Sub-item 2
- Item 3
- Item 4
```
Output:  

- Item 1
- Item 2
    - Sub-item 1
    - Sub-item 2
- Item 3
- Item 4

<br/>

<!-- ================================================ QUOTING CODE ============================================= -->
## Quoting Code

### #1 Inline Code

Put the the code or cmd within a sentence with single backticks or press `Ctrl/cmd`+`E` to insert the backticks for inline code.  

```
Use `git status` to list all new or modified files that haven't yet been committed.
```

Output:  

Use `git status` to list all new or modified files that haven't yet been committed.

### #2 Code Blocks

#### Method 1- using triple backticks

    Some basic Git Commands are:
    ```
    git init
    git status
    git add
    ```

Output:

Some basic Git Commands are:
```
git init
git status
git add
```

#### Method 2- using spaces or tab

    Normally indent the code with 4 spaces or one tab. (when they are in a list, indent them 8 spaces or 2 tabs)

Output:

    .container{
        max-width: 1200px;
    }


<br/>

<!-- ============================================== IMAGES ============================================ -->
## Images

```
![Alt Text](url)
```

Output: 

![Linux](https://upload.wikimedia.org/wikipedia/commons/0/09/Tux%2C_gray%EF%BC%8Fgrey_background.png)

<br/>

<!-- =========================================== HORIZONTAL RULE ====================================== -->
## Horizontal Rule

can create using 3 or more asterisks (***), dashes (---), or underscores (___) on a line. It's good to put blank lines before and after horizontal rule.

```
***

---

_______________
```

Output (all three will look same):  

***

<br />

<!-- ============================================ Links ============================================== -->
## Links

You can create by enclosing link text in brackets `[ ]` and then follow it with URL in parantheses `( )`.

```
Search this on [Google](https://www.google.com/) instead.
```

Search this on [Google](https://www.google.com/) instead.

### #1 Adding Titles to the Link

You can add a title to a link by enclosing it in quotation marks after URL, but it's optional. This will appear as a tooltip when the user hovers over the link.

```
Search this on [Google](https://www.google.com/ "Google") instead.
```

### #2 Sectional Links

To create anchor links that jump down to different sections of a README. Steps are: 

1. first create a heading:
    ```
    # Your Heading Name
    ```
2. The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting that README file and clicking on the anchor that appears when you hover to the left of the heading. Copy everything starting from  '#':
   ```
   #your-heading-name
   ```
3. Wherever you want to link to that Heading section, put your desired text in brackets, followed by the anchor link in parentheses:
    ```
    [Click to Sectional Link for more](#your-heading-name)
    ```

<br />

<!-- ==================================== ESCAPING CHARACTERS ======================================== -->
## Escaping Characters

To display a literal character that would otherwise be used to format text, add a backslash ( \\ ) in front of the character.

Those characters are: 
```
*   Asterisk
\   Backslash
`   Backtick
{}  Curly braces
()  Parentheses
[]  Square brackets
<>  Angle brackets
.   Dot
_   Underscore
!   Exclamation mark
#   Hash symbol
+   Plus symbol
-   Hyphen symbol
```

Example:  

```
+ Using Plus Symbol (as unorderd list) before escaping it
```

Output:  

+ Using Plus Symbol (as unorderd list) before escaping it  

<br />

Now see what will happen after escaping:   

```
\+ Using Plus Symbol (as Plus) after escaping it
```

Output:  

\+ Using Plus Symbol (as Plus) after escaping it  

<br />

<!-- ==================================== COLLAPSIBLE SECTION (toggle)  ======================================== -->
## Collapsible Section (Toggle)  

```
<details>
  <summary>Click to Expand!!</summary>
    
  ### Points:
  1. Make sure to have empty line after \</summary\> tag.
  2. Hidden Code Blocks:
        ```
        console.log('Hello World');
        ```
</details>
```

Output:  

<details>
  <summary>Click to Expand!!</summary>
    
  ### Points:
  1. Make sure to have empty line after \</summary\> tag.
  2. Hidden Code Blocks:
        ```
        console.log('Hello World');
        ```
</details>

<br />

<!-- ==================================== TABLES ======================================== -->
## Tables

- to create each column's header, use 3 or more hyphens (---)
- to separate each column, use pipes (|)

```
| Syntax | Description |
|   ---  |   ------    |
|  text  |   text      |
```

Output:

| Syntax | Description |
|   ---  |   ------    |
|  text  |   text      |

### #1 Alignment in Tables

Use colon(:) to the left, right or both side of hyphens within header row to align text in columns to the left, right, or center.

```
|   Column1    |     Column2    |    Column3    |
|     :---     |      :---:     |      ---:     |
| left aligned | center aligned | right aligned |
|    text1     |      text2     |     text3     |    
```
Output:

|   Column1    |     Column2    |    Column3    |
|     :---     |      :---:     |      ---:     |
| left aligned | center aligned | right aligned |
|    text1     |      text2     |     text3     |

### #2 Table with Multiple Lines

```
| Column1 | Column2 | Column3 |
|   ---   |   ---   |   ---   |
|  text1  |  text2  | text3 <br/> text4 <br/> text5 |
```

Output:

| Column1 | Column2 | Column3 |
|   ---   |   ---   |   ---   |
|  text1  |  text2  | text3 <br/> text4 <br/> text5 |

<br />

<!-- ==================================== SYNTAX HIGHLIGHTING ======================================== -->
## Syntax Highlighting

To add syntax highlighting, specify a language next to the backticks before the code block.

    ```javascript
    function show(){
        console.log("Hello World!!");
    }
    ```

Output:

```javascript
function show(){
    console.log("Hello World!!");
}
```

<br />

<!-- ==================================== TASK LISTS ======================================== -->
## Task Lists

also referred as Checklists and todo lists. 
- To create a task list: add dashes (-) & brackets `[ ]` with space inside, in front of task lists
- To select a checkbox, add 'x' in between brackets `[x]`

```
- [x] item 1 done
- [ ] item 2 incomplete
- [ ] item 3 incomplete
```

Output:

- [x] item 1 done
- [ ] item 2 incomplete
- [ ] item 3 incomplete

<br/>

If a task list item description begins with a parenthesis, you'll need to escape it with `\`, example:

```
- [ ] \(optional) task description
```

<br />

<!-- ==================================== EMOJI ======================================== -->
## Emoji

### #1 Method1- Copying and Pasting Emoji

Simply copy an emoji from a source and paste it into your doc. 🎉

### #2 Method2- Using Emoji Shortcodes

Begin and end with a colon and include the name of emoji.

```
This was hilarious :joy:
```

Output:

This was hilarious :joy:

- Check out [website](https://www.webfx.com/tools/emoji-cheat-sheet) and [github repo](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) for Emoji Cheat Sheet


<br />

<!-- ==================================== MENTIONING PEOPLE AND TEAMS ======================================== -->
## Mentioning people and teams

You can mention a person or team on GitHub by typing `@` followed by their username or team name.
