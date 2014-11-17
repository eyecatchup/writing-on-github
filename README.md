# WRITING ON GITHUB
===================  

>   _This is ~~just~~ a private backup of Github's post series "Writing on Github"._  
>   _I'm gonna add some more, relevant information from other sources soon and will 
>   leave this here as a _private_ **markdown reference**._  

---  

### Table of Contents

1. __[MARKDOWN BASICS](#)__
    2. [Basic writing](#)
        3. _[Paragraphs](#)_
        4. _[Headings](#)_
        5. _[Blockquotes](#)_
        6. _[Styling text](#)_
    7. [Lists](#)
        8. _[Unordered lists](#)_
        9. _[Ordered lists](#)_
        10. _[Nested lists](#)_
    11. [Code Formatting](#)
        12. _[Inline formats](#)_
        13. _[Multiple lines](#)_
    14. [Links](#)

--- 

    Backup of https://help.github.com/articles/markdown-basics/, created 2014/11/18.

---  

## MARKDOWN BASICS


[Markdown][md] allows you to write using an easy-to-read, easy-to-write plain text format, which then converts to valid HTML for viewing on GitHub

-- 

### Basic writing  

---  

##### Paragraphs

Paragraphs in Markdown are just one or more lines of consecutive text followed by one or more blank lines.

    On July 2, an alien mothership entered Earth's orbit and deployed several dozen saucer-shaped "destroyer" spacecraft, each 15 miles (24 km) wide.
     
    On July 3, the Black Knights, a squadron of Marine Corps F/A-18 Hornets, participated in an assault on a destroyer near the city of Los Angeles.

-- 

##### Headings

You can create a heading by adding one or more `#` symbols before your heading text. The number of `#` you use will determine the size of the heading.

    # The largest heading (an <h1> tag)
    ## The second largest heading (an <h2> tag)
    …
    ###### The 6th largest heading (an <h6> tag)

--  

##### Blockquotes

    You can indicate [blockquotes][bq] with a `>`.
    
    In the words of Abraham Lincoln:

    > Pardon my french
    
--  

##### Styling text

You can make text **[bold][b]** or *[italic][i]*.

    *This text will be italic*
    **This text will be bold**

Both **bold** and *italic* can use either a `*` or an `_` around the text for styling. This allows you to combine both bold and italic if needed.

    **Everyone _must_ attend the meeting at 5 o'clock today.**
    
--  

### Lists  

---  

##### Unordered lists

You can make an [unordered list][ul] by preceding list items with either a `*` or a `-`.  

    * Item
    * Item
    * Item

    - Item
    - Item
    - Item

--   

##### Ordered lists

You can make an [ordered list][ol] by preceding list items with a number.

    1. Item 1
    2. Item 2
    3. Item 3

--   

##### Nested lists

You can create nested lists by indenting list items by two spaces.

    1. Item 1
      1. A corollary to the above item.
      2. Yet another point to consider.
    2. Item 2
      * A corollary that does not need to be ordered.
        * This is indented four spaces, because it's two spaces further than the item above.
        * You might want to consider making a new list.
    3. Item 3

--  

### Code formatting  

--- 

##### Inline formats  

Use single backticks (<code>`</code>) to format text in a special monospace format. Everything within the backticks appear as-is, with no other special formatting.

    Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.
  
-- 

##### Multiple lines

You can use triple backticks (<code>```</code>) to format text as its own distinct block.

    Check out this neat program I wrote:

    ```
    x = 0  
    x = 2 + 2
    what is x
    ```

--

### Links  
  
---  

You can create an inline link by wrapping link text in brackets ( `[ ]` ), and then wrapping the link in parenthesis ( `( )` ).

For example, to create a hyperlink to [www.github.com](https://github.com), with a link text that says, Visit GitHub!, you'd write this in Markdown: `[Visit GitHub!](www.github.com)`.

--  

[md]: http://daringfireball.net/projects/markdown/    
[bq]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote    
[b]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong    
[i]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em   
[ol]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol  
[ul]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul  
  
>   <em><strong>END of "Markdown basics".</strong></em>

---
 
 
