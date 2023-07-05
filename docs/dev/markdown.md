# Markdown Syntax

## Headings

<div class="grid" markdown>
=== "Result"
    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>
```markdown title="Markdown code"
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
</div>

## Font style

<div class="grid" markdown>
=== "Result"
    Italics with *asterisks* or _underscores_.
    
    Bold with **asterisks** or __underscores__.
    
    Combined with **asterisks and _underscores_**.
    
    Strikethrough with tildes. ~~Scratch this.~~

```markdown title="Markdown code"
Italics with *asterisks* or _underscores_.

Bold with **asterisks** or __underscores__.

Combined with **asterisks and _underscores_**.

Strikethrough with two tildes. ~~Scratch this.~~
```
</div>

## Line breaks & Paragraphs

<div class="grid" markdown>
=== "Result"
    Here's a line for us to start with.

    This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

    This line is also a separate paragraph, but...
    This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
```markdown title="Markdown code"
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
```
</div>

## Lists

<div class="grid" markdown>
=== "Result"
    1. Apple
        1. Grany Smith
        2. Elstar
    2. Pear
    3. Banana
```markdown title="Markdown"
1. Apple
    1. Grany Smith
    2. Elstar
2. Pear
3. Banana
```
</div>

<div class="grid" markdown>
=== "Result"
    * Apple
        - Grany Smith
        - Elstar
    * Pear
    * Banana
```markdown title="Markdown"
* Apple
    - Grany Smith
    - Elstar
* Pear
* Banana
```
</div>

## Links

<div class="grid" markdown>
=== "Result"
    [Google](https://www.google.com)  
    [Homepage](/)  
    https://facebook.com/  
```markdown title="Markdown"
[Google](https://www.google.com)
[Homepage](/)
https://facebook.com/
```
</div>

## Images

<div class="grid" markdown>
=== "Result"
    ![Description](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Hover text")
```markdown title="Markdown"
![Description](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Hover text")
```
</div>

## Tables

<div class="grid" markdown>
=== "Result"
    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |
```markdown title="Markdown"
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```
</div>