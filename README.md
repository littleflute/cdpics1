### [v0.0.8](https://github.com/littleflute/cdpics1/edit/master/README.md)
### [2          168M]
### [3          28M]
### [4          90.4M]
### [cdpics1    207M]



<style>
#myViewer{
	border:1px red solid;
    height:50px;
}
</style>
<div id="myViewer"></div>
<script>
function blPicViewer()
{
	this.init = function ()
    {
    	var v = document.getElementById("myViewer");
        v.style.width 	= "100px";
        v.style.height 	= "100px";
        v.style.border 	= "1px blue solid"; 
        this.setVer("v0.0.2");
    }
    this.setVer = function(v)
    {
    	var p = document.getElementById("myViewer");
        var o = document.createElement("div");
        o.style.border = "1px green solid";
        o.innerHTML = v;
        p.appendChild(o);
    }
}
var v = new blPicViewer();
v.init();

</script>

























## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/littleflute/cdpics1/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/littleflute/cdpics1/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
