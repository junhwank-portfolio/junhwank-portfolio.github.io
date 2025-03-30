---
title: Add Tab Title Here
layout: single
author_profile: true
permalink: /projects/sample-project/
classes: wide
github: https://github.com/JunhwanK/portfolio-template/
---

# Page Title

Add a brief description here. If a github link is provided, a 'View on Github' link will appear here. {% if page.github %} <a href="{{ page.github }}">View on GitHub</a> {% endif %}

## Embed Youtube Video {#embed-youtube}

This is how to embed a youtube video with the link <https://www.youtube.com/watch?v=dQw4w9WgXcQ>. You only need the video id, i.e. dQw4w9WgXcQ.

{% include youtube_video.html id="dQw4w9WgXcQ" %}

## Sample Subheading (level 2)

- Sample bullet point 1.
- Sample bullet point 2.
- Sample bullet point 3.

## Sample subheading (level 2)

some text description.

1. numbered list, item 1.
2. numbered list, item 2.
3. numbered list, item 3.

some text description.

### Sample subheading (level 3)

Make text **bold** or *italicized* in markdown.

Add inline math equations in latex like this $ a_x \cdot p + b_y \times q = z $.

Or add math equations in blocks like this below.

$$ a^{x+y} = b $$

$$ x + y = z $$

## Sample subheading (level 2)

Organize texts, images, and bullet points into columns using the 'side-by-side' class like this.

### Images side-by-side

The 'width: n%' controls the width of each column. The sum of the percentages does not have to add up to 100.

The 'responsive-width' class allows the columns to stack vertically when viewing the page on a small window or screen (where screen width $\leq$ 480px), for example when view this webpage on a phone.

<div class="side-by-side">
  <figure style="width: 40%" class="responsive-width" id="temp_id_1">
    <img
      src="{{ site.url }}{{ site.baseurl }}/assets/images/sample-images/image-alignment-300x200.jpg"
      alt="alternative text description of the image.">
    <figcaption>Image caption goes here.</figcaption>
  </figure>
  <figure style="width: 40%" class="responsive-width" id="temp_id_2">
    <img
      src="{{ site.url }}{{ site.baseurl }}/assets/images/sample-images/image-alignment-300x200.jpg"
      alt="alternative text description of the image.">
    <figcaption>Image caption goes here.</figcaption>
  </figure>
</div>

Figure numbers are automatically incremented (even when the figure does not have a caption). Also, 'Fig. n:' is automatically prepended to the figure caption.

Add an 'id' to the figure and reference it like this (see <span data-figure-ref="temp_id_1"></span> and <span data-figure-ref="temp_id_3"></span>). The 'span' elements are automatically replaced with the figure number.

<figure style="width: 40%" class="align-center" id="temp_id_3">
  <img
    src="{{ site.url }}{{ site.baseurl }}/assets/images/sample-images/image-alignment-580x300.jpg"
    alt="alternative text description of the image.">
  <figcaption>Image caption goes here.</figcaption>
</figure>

### Image and text side-by-side

To put text into columns, they need to be written in html.

<div class="side-by-side">
  <div style="width: 65%" class="responsive-width">
    <p>
      Paragarphs needs to be wrapped by the 'p' tag.
    </p>
    <p>
      This is a new paragraph in column 1. <b>Bold text in html.</b> <em>Italicized text in html.</em>
    </p>
  </div>
  <figure style="width: 35%" class="responsive-width">
    <img
      src="{{ site.url }}{{ site.baseurl }}/assets/images/sample-images/image-alignment-300x200.jpg"
      alt="alternative text description of the image.">
    <figcaption>Image caption goes here.</figcaption>
  </figure>
</div>

### Text and bullet points side-by-side

<div class="side-by-side">
  <div style="width: 33%" class="responsive-width">
    <b> Some bold text (<span data-figure-ref="temp_id_2"></span>):</b>
    <ul>
      <li> bullet point in column 1. </li>
      <li> bullet point in column 1. </li>
      <li> bullet point in column 1. </li>
    </ul>
  </div>
  <div style="width: 33%" class="responsive-width">
    <ol>
      <li> numbered item in column 2. </li>
      <li> numbered item in column 2. </li>
      <li> numbered item in column 2. </li>
    </ol>
  </div>
  <div style="width: 33%" class="responsive-width">
  <p>
    some text in column 3.
  </p>
  </div>
</div>

## Add images with text-wrap {#text-wrap}

To have text wrapped around the images, do not use the "side-by-side" class. Instead use the 'align-left' or 'align-right' classes provided by the minimal-mistakes template. You can optionally use the style="width: n%" to resize the images to a certain width in proportion to the screen. Below are some examples.

### Align Center

To center an image, use the 'align-center' class provided by the minimal-mistakes template.

<figure style="width: 20%" class="align-center">
  <img
    src="{{ site.url }}{{ site.baseurl }}/assets/images/sample-images/image-alignment-300x200.jpg"
    alt="alternative text description of the image.">
  <figcaption>Image caption goes here.</figcaption>
</figure>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Align Left

<figure style="width: 20%" class="align-left">
  <img
    src="{{ site.url }}{{ site.baseurl }}/assets/images/sample-images/image-alignment-300x200.jpg"
    alt="alternative text description of the image.">
  <figcaption>Image caption goes here.</figcaption>
</figure>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Align Right

<figure style="width: 20%" class="align-right">
  <img
    src="{{ site.url }}{{ site.baseurl }}/assets/images/sample-images/image-alignment-300x200.jpg"
    alt="alternative text description of the image.">
  <figcaption>Image caption goes here.</figcaption>
</figure>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Add reference link to a heading

Add links to headings within this page. Like this [some text](#text-wrap), or like this <A href="#text-wrap">some text</A>.

<br><br>
<a href="{{ site.url }}{{ site.baseurl }}/projects/">← Back to 'Projects'</a>
