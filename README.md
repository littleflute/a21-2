
[v0.0.4](https://github.com/littleflute/a21-2/edit/master/README.md)

[show this page](https://littleflute.github.io/a21-2/)

[https://littleflute.github.io/a21](https://littleflute.github.io/a21)

[cd01](https://littleflute.github.io/a21/docs/cds/cd01)

[cd02](https://littleflute.github.io/a21/docs/cds/cd02)

[cd03](https://littleflute.github.io/a21/docs/cds/cd03)

[cd04](https://littleflute.github.io/a21/docs/cds/cd04)

[cd05](https://littleflute.github.io/a21/docs/cds/cd05)

[cd06](https://littleflute.github.io/a21/docs/cds/cd06)

[cd07](cd07)

[cd08](cd08)

[cd09](cd09)

[cd10](cd10)


[Foxy lady [sound recording] tribute to Jimi Hendrix Lonnie Smith Trio](Foxy lady [sound recording] tribute to Jimi Hendrix Lonnie Smith Trio)

[Power of soul-a tribute to Jimi Hendrix](Power of soul-a tribute to Jimi Hendrix)

[Rainbow bridge](Rainbow bridge/)

[Smash hits](Smash hits)


<audio controls id="player"> 
  <source src="https://littleflute.github.io/a21/docs/cds/cd01/01_曲目 1.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 

html += fNewBtn(1);
html += fNewBtn(2);
html += fNewBtn(3);
html += fNewBtn(4);
html += fNewBtn(5);
html += fNewBtn(6);
html += fNewBtn(7);
 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/a21/docs/cds/cd01/0";
    s += i;
    s += " 0";
    s += i;
    s += ".mp3";
    
	p.src = s; 
    p.play();
}
function fNewBtn(i)
{
	var rHTML = "";
    rHTML = "<button onclick='f(";
    rHTML += i;
    rHTML += ");'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
</script>















## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/littleflute/a21-2/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/littleflute/a21-2/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
