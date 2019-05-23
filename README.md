# Welcome to Littlebird!
## Littlebird is a world in itself.  A world of many worlds... each colliding with itself....
----
# Structured documents

Sometimes it's useful to have different levels of headings to structure your documents. Start lines with a `#` to create headings. Multiple `##` in a row denote smaller heading sizes.

### This is a third-tier heading

You can use one `#` all the way up to `######` six for different heading sizes.

If you'd like to quote someone, use the > character before the line:

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway
----
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
----
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
----
* Item 1
* Item 2
  * Item 2a
  * Item 2b
----
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
----
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
----
http://github.com - automatic!
[GitHub](http://github.com)
----
As Kanye West said:

> We're living the future so
> the present is our past.
----
I think you should use an
`<addr>` element here instead.
----
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
----
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
----
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.
