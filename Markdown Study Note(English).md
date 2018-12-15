# Markdown Study Note

## How?

To use this note, you can either:

1. Save and open it with a Markdown Editor such as Macdown, or
2. View it using the Github editor mode.
</br>

## Why Markdown? 

- Plain text. Highly compatibility. Opened using any text editor.
- Focus on content instead of layout
- Convert to html, ebook, etc.
- highly readable
</br>

## Headers

There are two styles of headers in Markdown.

**1. Atx-style**

# H1
## H2
### H3
#### H4
##### H5
###### H6


**2. Setext-Style**


H1
=======

H2
--------

</br>

## Blockquotes
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

**Or you can use > in the beginning of a whole paragraph**

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

**Blockquotes could be nested.**

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.
> 


**Other Markdown syntaxes are supported inside a blockquote.**

> ### This is a header
> 
> 1.   This is the 1st line of a list
> 2.   This is the 2nd line of a list
> 
> code block:
> 
>     return hellow world

</br>

## List

> * Red
> * Blue
> * Yellow

***

> + Red
> + Blue
> + Yellow

***

> 1. Red
> 2. Blue
> 3. Yellow

</br>

## Code Blocks
To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab.

**Example Code:**

	Str = "hellow world!"
	return Str

</br>

## Horizontal Rules

content

* * *

content

***

content

*****

content

- - -

content

---------------------------------------

content

</br>

## Links

**Inline Links**

This is [an example](http://example.com/ "Title") inline link.

This is [another example](http://example.com/ "Title") inline link.

**Reference Links**

This is [an example][id] reference-style link.


[id]: http://example.com/  "Optional Title Here"


</br></br></br></br>

##### Reference: 
1. [http://wow.kuapp.com/markdown/#header][r1]
2. [https://daringfireball.net/projects/markdown/syntax#p][r2]

[r1]:http://wow.kuapp.com/markdown/#header
[r2]:https://daringfireball.net/projects/markdown/syntax#p
