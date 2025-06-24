# C-to-HTML
This is a library to use for C to write HTML.

🧠 Function Reference
Function	Description
starter(theme, title)	Starts the HTML document. Sets up the theme and title.
ender()	Closes the HTML document properly.
header(text)	Adds a <h1> heading to the page.
p(text)	Adds a paragraph (<p>) to the page.
link(href, text)	Adds a regular clickable hyperlink (<a>)
linkNewTab(href, text)	Same as link(), but opens in a new tab (target="_blank")
iframe(src, width, height)	Embeds a webpage or video with given dimensions
img(src, alt, width, height)	Adds an image with alt text and dimensions
button(text)	Adds a clickable HTML button


Be sure to use all functions inside the main(), and use the starter and ender to start and end the project.
The following themes can be used in starter() ex: starter(dark, title):

Theme	  Background	Text Color
dark	  black	      white
light	  white	      black
matrix	black	      lime
rose	  pink	      white
hacker	gray	      green
aqua	  aqua	      navy
sunset	orange	    maroon
ghost	  white	      gray
royal	  purple	    gold
dev	    black-ish	  cyan

