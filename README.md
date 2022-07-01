Markdown to HTML
Turn Markdown files to HTML syntax just for fun!

Usage
./markdown2html.py readme.md readme.html



Features
MD syntax	HTML syntax/tags	Description
#, ##...	<h1>, <h2>	All level headings
-	<ul> <li>... </ul>	Unordered lists
*	<ol> </li>... </ol>	Ordered lists
Text	<p>Text</p>	Paragraph
**text**	<b>text</b>	Bold inline text
__text__	<em>text</\em>	Emphasis inline text
[[text]]	MD5 hash	Converts to MD5
((text))	Text	Text without the letter c
