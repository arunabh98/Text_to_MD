# Text_to_MD
Convert your docs to markdown format. 

Sometimes someone shares a blog written by them in Google Docs or MS Word and we have to manually convert it to markdown for our site. Or we copy things from the internet and wish it could have been in markdown format on pasting!
Well to solve this problem I have made a converter which can convert our normal documents to markdown language.

The editor used is [ckeditor](http://ckeditor.com/) and the HTML to markdown converter used is [domchristie/to-markdown](https://github.com/domchristie/to-markdown).
I have also made use of the Resize sensor in [marcj/css-element-queries](https://github.com/marcj/css-element-queries) to detect the height changes in ckeditor and accordingly change the height of the output textarea.
