---
title: Sticky
description: Stick nearly anything, anywhere you like!
sass: scss/components/_sticky.scss
js: js/foundation.sticky.js
---

<div class="alert callout">
  <h5>Known Issues</h5>
  <ul>
    <li><em>Future Feature:</em> Needs method for elements to be sticky on the top of the viewport when scrolling down, and if the lower breakpoint is reached, stick to bottom on scroll up.</li>
    <li>Seems to have a problem with short elements: < 2x the sticky element's height or so.</li>
  </ul>
</div>

## Basics

Add the `.sticky` class and `[data-sticky]` to an element to create something that sticks. Sticky elements must be wrapped in a container, which will determine your sizing and grid layout, with `[data-sticky-container]`.

```html
<div class="columns small-6 right" data-sticky-container>
  <div class="sticky" data-sticky>
    <img src="assets/img/interchange/small.jpg">
  </div>
</div>
```

<!-- ```html_example -->
<div class="row">
  <div class="columns small-12">
    <div class="columns small-6" id="example1" data-something>
      <p id="doodle">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
    </div>
    <div class="columns small-6 right" data-sticky-container>
      <div class="sticky" data-sticky data-anchor='#example1'>
        <img src="assets/img/interchange/small.jpg">
      </div>
    </div>
  </div>
</div>

## Advanced

You can also use two anchors, if you please. Using `data-top-anchor='idOfSomething'`, `data-btm-anchor='idOfSomething:[top/bottom]'`, or a set pixel number `data-top-anchor='150'`. If you use an element id with no top/bottom specified, it defaults to the top.
```html
<div class="columns small-6 right" data-sticky-container>
  <div class="sticky" data-sticky data-top-anchor='example2' data-btm-anchor='foo:bottom'>
    <img src="assets/img/interchange/small.jpg">
  </div>
</div>
```


<div class="row">
  <div class="columns small-12">
    <div class="columns small-6" id="example2">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      <p id='foo'>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
    </div>
    <div class='columns small-6 right' data-sticky-container>
      <div class="sticky" data-sticky data-top-anchor='example2:top' data-btm-anchor='foo' data-stick-to="bottom">
        <img src='assets/img/interchange/small.jpg'>
      </div>
    </div>
  </div>
</div>
<!-- ``` -->
