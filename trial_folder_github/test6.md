this is created directly from github

 ## How should I understand this Notebook?

Each Cell below is a markdown language cell, so please take time to click on each of the cell to see the underlying markdown syntax and make beautiful Markdowns...

This is totally inspired by the following articles:

https://www.markdownguide.org/

https://letsfigureout.com/writing-mathematical-expressions-in-jupyter-notebooks/

https://www.ibm.com/docs/en/db2-event-store/2.0.0?topic=notebooks-markdown-jupyter-cheatsheet
## How do I write nice Quotes?
> blockquote

## Headings Demo

Using blockquote with Heading looks like:
   > # Heading 1
   > ## Heading 2
   > ### Heading 3
## Bold Text

**I am as bold as I think**
## Italicized Text

*This is italicized text*

Items in the list

1. First item
2. Second item
3. Third item
- First item
- Second item
- Third item
## Numbered Items

1. Numbered item
     1. Substep1
     2. Substep2
## Bulleted Items and Sub Items

- Main bullet point
     - Sub bullet point
## Code highlight/ block

`code`

## Line 

Use 3 hyphens like this:

---

or 3 asterisks like this:

***
## Hyper Link/ URL

[title](https://www.example.com)

## Image display

![alt text](./Hubble_ultra_deep_field.jpg)

## Table

**Tabular Data 1**

| Country | City |
| --- | ----------- |
| India | Delhi |
| United States of America | Sacramento |


**Tabular Data 2**

Notice the placement of the semi-colon(s) in the respective column Alignment

|Left Aligned Column|Right Aligned Column|Center Aligned Column|
| :---        |      ---:   | :---:   | 
| row1_col1   | row1_col2   | row1_col3 |
| row2_col1   | row2_col2   | row2_col3 |
| row3_col1   | row4_col2   | row3_col3 |

# Fenced Code Block

*```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
# Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
[My Heading] (#custom-id)
Gone camping! :tent: Be back soon.

That is so funny! :)
## Strike through

~Strike this portion~

## Highlighting

I need to highlight these ==very important words==

 ## Task Checklist
 - [x] Task1
 - [ ] Task2
## Text Colour

Markdown Supports HTML, try changing the colour of the font like the below snippet


<font color="red">This text is red!</font>

## Super Script

X<sup>2</sup>

## Sub Script

H<sub>2</sub>
## Latex Sub Script

$X_{2}$

$x_{2}$

## Latex Super Script

$x^{2}$

$X^{2}$
## Align environment

To display an equation with an equation number, use the `align` environment:

\begin{align}
E = mc^2
\end{align}
## Lowercase Greek letters 

$\alpha, \beta, \gamma, \delta, \epsilon, \theta $

## Uppercase Greek letters

$\Gamma, \Delta, \Theta, \Lambda, \Pi, \Theta $
## Coloured Note boxes

<div class="alert alert-block alert-info">
<b>Tip:</b> Use blue boxes (alert-info) for tips and notes. 
If it’s a note, you don’t have to include the word “Note”.
</div>
## Mathematical Symbols and Notations

$ integration $


Summation: $\sum_{i=1}^n i = \frac{n(n+1)}{2}$

Integral: $\int_{0}^{1} x^2 dx = \frac{1}{3}$
Fractions: $\frac{a}{b}, \frac{1}{2}, \frac{x^2}{x^2 + y^2}$
Summation: $\sum_{i=1}^n i = \frac{n(n+1)}{2}$

Integral: $\int_{0}^{1} x^2 dx = \frac{1}{3}$
To display an equation on a separate line, use double dollar signs:
$$
E = mc^2
$$
Matrix example:
$$
\begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{bmatrix}
$$
<div class="alert alert-block alert-warning">
<b>Example:</b> Use yellow boxes for examples that are not 
inside code cells, or use for mathematical formulas if needed.
</div>
<div class="alert alert-block alert-success">
<b>Up to you:</b> Use green boxes sparingly, and only for some specific 
purpose that the other boxes can't cover. For example, if you have a lot 
of related content to link to, maybe you decide to use green boxes for 
related links from each section of a notebook.
</div>
<div class="alert alert-block alert-danger">
<b>Just don't:</b> In general, avoid the red boxes. These should only be
used for actions that might cause data loss or another major issue.
</div>
## Graphic Display

<img src="Hubble_ultra_deep_field.jpg" alt="Alt text that describes the graphic" title="Title text" />


Array example:
$$
\left\{
\begin{array}{l}
x = 3y + 4z \\
y = 2x - z \\
z = x + y
\end{array}
\right.
$$
## More Math Equation styles (Customizing Text)


Bold: $\mathbf{This \; is \; bold}$

Italic: $\mathit{This \; is \; italic}$

Underline: $\underline{This \; is \; underlined}$
[Analyzing customer purchasing habits](#analyzing-customer-purchasing-habits)


## Controlling Size of fonts in a formula

Small: $\small{E = mc^2}$

Large: $\large{E = mc^2}$

Huge: $\Huge{E = mc^2}$

