---
title: Book-1 | Ethereal
html_template: book1/book1.html
id_to_make_active: chapter1
source: True
---

# H1 Header
### *Subtitle class for a fancy tagline* {: class="subtitle" }


## Responsive {: class="template__section" }

Resize your browser to see how the page responds to different screen sizes.  Breakpoints are 

**phone** | `768px` | **tablet** | `1024px` | **laptop**

* Under 1024px Hamburger menu icon appears, left TOC hidden & moved to menu
* Under 768px right TOC hidden; current version of this template does not place it in menu

### H3 Header

## Top Buttons {: class="template__section" }

Click the buttons at the top to view/edit source code on GitHub, and to toggle the theme between light, dark, and default modes.  The chosen theme persists across page views.  


## Scrollspy {: class="template__section" }

See it highlight your position on the page to the right.  
 


## Abbreviations {: class="template__section" }

Hover over the abbreviations.  See [python-markdown doc](https://python-markdown.github.io/extensions/abbreviations/).

The HTML specification is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium


## Admonitions {: class="template__section" }

See [python-markdown docs](https://python-markdown.github.io/extensions/admonition/) for usage.  


!!! info ""
    An admonition without a title.

    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 


!!! info "An 'info' admonition with title"
    The quick brown fox jumps over the lazy log.

    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 


 
## Code {: class="template__section" }

A client connects to a server using an SSH [URI](https://en.wikipedia.org/wiki/Uniform_Resource_Identifier) such as

*[URI]: Uniform Resource Identifier

```bash
ssh://[user@]<server-hostname><some-path>
```

The square brackets ```[user@]``` indicate that part is optional.  If the username on the client and the server are the same, this can be omitted. The ```<server-hostname>``` is the server's domain name or IP address; it might be, for example, the name of a server in your home ```myHomelab.local```, or it might be an external website like ```example.com```:

```bash
ssh://ted@example.com/path/to/project.git
```


## Tables {: class="template__section" }

[python-markdown doc](https://python-markdown.github.io/extensions/tables/)

| Startup page          |                                      |
| :---------------------| :----------------------------------- |
| `Raspberry Pi Device` | Raspberry Pi 5                       |
| `Operating System`    | Raspberry Pi OS (64-bit)<br>Raspberry Pi OS (other) >> Raspberry Pi OS Lite (64-bit) |
| `Storage`             | Select the micro SD card             |





## Attribute Lists {: class="template__section" }

If you view our source you will notice the use of attribute lists such as 
```
{: #someid .someclass somekey='some value' }
```

To add class, id, and other info to HTML tags.  See [python-markdown doc](https://python-markdown.github.io/extensions/attr_list/) for usage.  

