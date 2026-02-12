# Header level 1, 2 & 3 example:
## Header level 2

This is a normal paragraph:

    This is a code block.

### Common text formating:
This is a **bold** text\
This is an _italic_ text\
***This is bold and italic text***\
This is an ~~italic~~ text
> This is a block quote

### Some basic `JavaScript` commands:
``` Javascript
const header = document.querySelector("#header");
if (!header) return;
const scrollTop = header.offsetHeight;

window.addEventListener("scroll", () => {
  header.classList.toggle("is_fixed", window.scrollY > scrollTop);
});
```

This is a [link](http://www.example.com)   
Link to the sample section: [Link Text](#sample-section).

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

<table>
    <tr>
        <th>Name</th>
        <th>Prop</th>
    </tr>
    <tr>
        <td>Foo</td>
        <td>Foo</td>
    </tr>
</table>

This is another regular paragraph.

This is a footer reference or html tooltip equivalent: 

A footnote can also have multiple lines[^1].

[^1]: My reference.

