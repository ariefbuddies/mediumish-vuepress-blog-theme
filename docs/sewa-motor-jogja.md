---
title: Sewa Motor Jogja
description: Sewa motor untuk wong jogja

---
Berikut ini adalah daftar motor yang terdapat di garasi kami.

To write a theme, create a `.vuepress/theme` directory in your docs root, and then create a `Layout.vue` file:

    .
    └─ .vuepress
       └─ `theme`
           └─ Layout.vue

From there it's the same as developing a normal Vue application. It is entirely up to you how to organize your theme.

## Content Outlet

The compiled content of the current `.md` file being rendered will be available as a special `<Content/>` global component. You will need to render it somewhere in your layout in order to display the content of the page. The simplest theme can be just a single `Layout.vue` component with the following content:

    <template>
      <div class="theme-container">
        <Content/>
      </div>
    </template>

**Also see:**

* [Markdown Slot](../guide/markdown-slot.md)

<style>

\* {

box-sizing: border-box;

}

.column {

float: left;

width: 50%;

padding: 1px;

height: 600px; /* Should be removed. Only for demonstration */

}

/* Clear floats after the columns */

.row:after {

content: "";

display: table;

clear: both;

}

</style>

<body>

<h2>Daftar Motor Rental</h2>

<div class="row">

<div class="column" style="background-color:#aaa;">

    Honda Beat
    Umum 70 Ribu
    Pelajar 60 Ribu
    -------------

![](/assets/img/avatar.png)

</div>

<div class="column" style="background-color:#bbb;">

    Honda Scoopy
    Umum 75 Ribu

![](/assets/img/sal.jpg)

</div>

</div>

</body>

![](/assets/img/11-08-22-eovwg91wmagevce.jpg)