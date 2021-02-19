---
title: This is a page to play and learn how to use Markdown language
---

## Main Markdown to use

Be careful with spaces, one space can break it.


# This is an H1 
We don't need to use one as there is one for each page already

## This an H2

### This is an H3

#### This is an H4

##### This is an H5

**this is bold text**

_This is italic text but for accessibility, it's best not to use it_

[This is the text of a link which will open in the same tab](http://www.this-is-the-url-of-your-link.com)

- this is the first bullet point of a list
- this is the second
- the third

This is how to add an image
![description of the image for screen readers or when the image doesn't load](/practitioner-stories/images/name-of-the-file-of-the-image)


> this is how to make a blockquote (makes the blue one type)

## Main Html you might need


You can use both on the page you are creating but don't mix them within a paragraph or component.

<p>This is a paragraph, you might need html instead of Mark Down if you want to add a link the open in a new tab in your paragraph</p>

<p><a href="http://www.this-is-the-url-of-your-link.com" target="_blank">The text of my link which will open in a new tab</a></p>

This is how to make the horizontal line, but I'm changing this as I've learned it's not that accessible for people with screen readers, they hear: separation block or something
<hr class="big">

So instead you can add a top line to a h2 or a h3:
<h2 class="top-line">Heading 2 with a top line</h2>
<h3 class="top-line">Heading 3 with a top line</h3>

<blockquote class="alt">
  <p>This is a quote, but this one is orangy, you need html to do this one.</p>
</blockquote>


<p><a href="" target="_blank">Access the part of the Miro Board represented in the image</a></p>

This is how to make the element which opens and closes to reveal content
 <details>
 <summary>Text that is seen at the top</summary>
 <p>text that displays when open - this is a paragraph</p>
 <ul>
    <li>this is a bullet point</li>
    <li>another bullet point</li>
 </ul>
 </details>

This is how you force your text to go back to the line. Can be used to add some space, but it's a dirty way to do it ;)
<br><br><br>


This is how you add the little bit for the feedback the code for it is in another file
{% include give-feedback.html %}

