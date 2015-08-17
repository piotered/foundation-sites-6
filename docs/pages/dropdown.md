---
title: Dropdowns
description: Dropdowns. Or ups, rights, and lefts; horizontal or vertical. Your call! Dropdowns are a great way to add content to an element without taking up a bunch of space in your view.
sass: scss/components/_dropdown.scss
---

<h2>Horizontal</h2>

<ul class="dropdown menu-bar" data-dropdown>
  <li class="has-submenu">
    <a href="#">Item 1 &raquo;</a>
    <ul class="submenu vertical menu-bar" data-submenu>
      <li class='has-submenu'><a href="#">Item 1A Loooong &raquo;</a>
        <ul class='submenu vertical menu-bar' data-submenu>
          <li><a href="#">Item 1Aa</a></li>
          <li><a href="#">Item 1Ab</a></li>
          <li><a href="#">Item 1Ac</a></li>
        </ul>
      </li>
      <li><a href="#">Item 1B</a></li>
      <li><a href="#">Item 1C</a></li>
      <li><a href="#">Item 1D</a></li>
      <li><a href="#">Item 1E</a></li>
    </ul>
  </li>
  <li class="has-submenu">
    <a href="#">Item 2 &raquo;</a>
    <ul class="submenu vertical menu-bar" data-submenu data-closeonclick>
      <li><a href="#">Item 2A</a></li>
      <li><a href="#">Item 2B</a></li>
      <li><a href="#">Item 2C</a></li>
      <li><a href="#">Item 2D</a></li>
      <li><a href="#">Item 2E</a></li>
    </ul>
  </li>
  <li class="has-submenu">
    <a href="#">Item 3 &raquo;</a>
    <ul class="submenu vertical menu-bar" data-submenu>
      <li><a href="#">Item 3A</a></li>
      <li><a href="#">Item 3B</a></li>
      <li><a href="#">Item 3C</a></li>
      <li><a href="#">Item 3D</a></li>
      <li><a href="#">Item 3E</a></li>
    </ul>
  </li>
</ul>

<hr>

<h2>Vertical</h2>

<ul class="dropdown vertical menu-bar" style="width: 300px;" data-dropdown>
  <li class="has-submenu">
    <a href="#">Item 1 &raquo;</a>
    <ul class="submenu vertical menu-bar" data-submenu>
      <li><a href="#">Item 1A Loooong</a></li>
      <li><a href="#">Item 1B</a></li>
      <li><a href="#">Item 1C</a></li>
      <li><a href="#">Item 1D</a></li>
      <li><a href="#">Item 1E</a></li>
    </ul>
  </li>
  <li class="has-submenu">
    <a href="#">Item 2 &raquo;</a>
    <ul class="submenu vertical menu-bar" data-submenu>
      <li class="has-submenu">
        <a href="#">Item 2A &raquo;</a>
        <ul class="submenu vertical menu-bar">
          <li><a href="#">Item 2Ai</a></li>
          <li><a href="#">Item 2Aii</a></li>
          <li><a href="#">Item 2Aiii</a></li>
          <li><a href="#">Item 2Aiv</a></li>
        </ul>
      </li>
      <li><a href="#">Item 2B</a></li>
      <li><a href="#">Item 2C</a></li>
      <li><a href="#">Item 2D</a></li>
      <li><a href="#">Item 2E</a></li>
    </ul>
  </li>
  <li class="has-submenu">
    <a href="#">Item 3 &raquo;</a>
    <ul class="submenu vertical menu-bar" data-submenu>
      <li><a href="#">Item 3A</a></li>
      <li><a href="#">Item 3B</a></li>
      <li><a href="#">Item 3C</a></li>
      <li><a href="#">Item 3D</a></li>
      <li><a href="#">Item 3E</a></li>
    </ul>
  </li>
</ul>