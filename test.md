# Markdown syntax guide

## The Headers

# This is a Heading h1
## This is a Heading h2 
###### This is a Heading h6

## Emphasis

### Some Text ###

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_

## Lists

### Unordered

* Item 1
* Item 2
* Item 2a
* Item 2b

### Ordered

1. Item 1
1. Item 2
1. Item 3
  1. Item 3a
  1. Item 3b

## Images

![This is a alt text.](/image/sample.png "This is a sample image.")

## Links

You may be using [Markdown Live Preview](https://markdownlivepreview.com/).

## Internal Links

## 1.1 Hello World

Create a link to it this way:

[Link to Hello World](#11-hello-world)

[Link to Heading H1](#this-is-a-heading-h1)

## Blockquotes

> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz.
>
>> Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Tables

| Left columns  | Right columns |
| ------------- |:-------------:|
| left foo      | right foo     |
| left bar      | right bar     |
| left baz      | right baz     |

| Left columns  | Center columns | Right columns |
| ------------- |:-------------:| :-------------:|
| left foo      | right foo     | right foo     |
| left bar      | right bar     | right bar  in elongazione   |
| left baz      | right baz     | right baz     |


## Blocks of code

```
let message = 'Hello world';
alert(message);
```

## Inline code

This web site is using `markedjs/marked`.
