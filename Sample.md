
# Markdown sample syntax

### 1. Text and Style
***
This is a sample file of markdown language! It's amazing.<br>
If you want to go to the next line add a space line or use "\<br\>" tag.

This is **bold** text! also you can use __this__ as a bold text.

You can use *italic* style by adding single star or single _under_score_ symbol

If you want to use ***bold and italic*** use three stars or three ___under_score___

If you decide to ~~Strikethrough~~ a word just add double ~ before and after of it.

<br>

### 2. Block quotes
***
> In order to add a quote use > symbol at the first line


>You can use multi line quote also. It's so easy.
>
>The only need to use > symbol in each line of your quotes.

> block quotes can be nested.
>
>>This is nested block quotes
>
>And This is the continue of main quote.

<br>

### 3. Ordered Lists
***
1. first item
2. second item
3. third item
  1. first intended item
  2. second intended item
4. forth item

<br>

### 4. Unordered Lists
***
- First Item
* Second item
+ Third Item
  - First intended item
  + Second intended Item
+ Forth item

<br>

### 5. Adding Elements in Lists
***
#### paragraph

*   This is the first list item.
*   Here's the second list item.

    I need to add another paragraph below the second list item.

*   And here's the third list item.
<br>

#### Block quote
***
*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.

<br>

### 6. Code block
***
1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.  

also you can use code blocking by indent with four spaces:

    if (isAwesome){
      return true
    }

<br>

### 7. Image
***
1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.

<br>


### 8. code
***
At the command prompt, type `nano`.

```java
String string = new String();
string.concat("adasd");
```
<br>


### 9. Horizontal Rules
***
To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

<br>

### 10. Links
---
To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

<br>

### 11. URLs and Email Addresses
---

To quickly turn a URL or email address into a link, enclose it in angle brackets.

<https://www.markdownguide.org>

<fake@example.com>

<br>

### 12. Formatting Links
---
I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the section on [`code`](#code).

<br>

### 13. Reference-style Links
---


[hobbit-hole] [1] <br>
[hobbit-hole] [2] <br>
[hobbit-hole] [3] <br>
[hobbit-hole] [4] <br>

[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[2]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[3]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[4]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'

<br>

### 14. table
---

| Title one     | Title two     | Title one     | Title two     |
| :------------- | :------------- | :------------- | :-------------
| Item One       | Item Two       | Item One       | Item Two       |
| Item One       | Item Two       | Item One       | Item Two       |
| Item One       | Item Two       | Item One       | Item Two       |

<br>


### 15. Task List
---

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

<br>


##### An Example Putting the Parts Together
---


In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.


In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

<br>
