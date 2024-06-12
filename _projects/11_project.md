---
layout: page
title: Authored Books
description: As a speaker of a very low resourced language - Tigrinya - I grew up without access to reading materials, especially during the early child hood years. To alleviate this problem, I have worked with some authors to adapt children's books to Tigrinya. You can check on Amazon some of the recently published storybooks <a href="https://amzn.to/3dXVMX1">here</a> and <a href="https://amzn.to/3sWssUP">here</a>.
img: /assets/img/books.jpg
github:
pdf:
blog:
importance: 11
category: other
---

As a speaker of a very low resourced languages - Tigrinya - I grew up without access to reading materials, especially during the early child hood years. To alleviate this problem I have worked with some authors to adapt children's books to Tigrinya.

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/1.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/3.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal it's glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    <img
      class="img-fluid rounded z-depth-1"
      src="{{ '/assets/img/6.jpg' | relative_url }}"
      alt=""
      title="example image"
    />
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    <img
      class="img-fluid rounded z-depth-1"
      src="{{ '/assets/img/11.jpg' | relative_url }}"
      alt=""
      title="example image"
    />
  </div>
</div>
```
