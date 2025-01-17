# print-markdown

Print a web page as if it was plain markdown, with few CSS rules, it is possible to style the elements in a way that reflects its markdown counterparts, and it can be done without any JavaScript or server-side processing. 

This technique uses the CSS pseudo-elements `::before` and `::after` to add the markdown syntax to the content, like `#` for headings, `*` for strong text, `_` for emphasized text, and `-` for list items. 
