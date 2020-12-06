<template>
<footer class="themefooter">

<div class="container">
<div class="row justify-content-between">
<div class="col text-right">
<ul v-if="contact" class="list-unstyled">
<li
v-for="item in contact"
:key="item.iconComponent"
class="contact-item"
>
<NavLink :link="item.link">
<component :is="item.iconComponent"></component>
{{ item.text }}
</NavLink>
</li>
</ul>
<ul v-if="copyright" class="list-unstyled">
<li v-for="item in copyright" :key="item.text" class="copyright-item">
<NavLink :link="item.link">{{ item.text }}</NavLink>
</li>
</ul>
</div>
</div>
</div>

</footer>
</template>
