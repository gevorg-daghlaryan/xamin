<template>
  <div>
<!--    <Loader />-->
    <HeaderStyle1 :logo-img="logo" :nav-item-list="navItems" class-name="style-one position-relative" :styled-logo="styleLogo" />
    <nuxt />
    <ScrollTop />
  </div>
</template>
<script>
import { menu, services, pages, landing1About, ourCases, blog } from '../config/constant.js'
import logoImg from '../assets/images/logo_1.svg'
export default {
  name: 'LandingPage21',
  data () {
    return {
      styleLogo: false,
      logo: logoImg,
      navItems: [
        { href: '/landing-page-21',
          title: 'Home',
          active: true,
          children: true,
          child: menu,
          classname: 'menu'
        },
        { href: '/about-1', title: 'About Us', children: true, child: landing1About, classname: ' ' },
        { href: '/services', title: 'Services', children: true, child: services, classname: ' ' },
        { href: '/masonry-2', title: 'Our Cases', children: true, child: ourCases, classname: ' ' },
        { href: '/blog', title: 'Blog', children: true, child: blog, classname: ' ' },
        { href: '/our-team', title: 'Pages', children: true, child: pages, classname: ' ' }
      ]
    }
  },
  mounted () {
  }
}
</script>
<style>
  @import url('../assets/css/style.css');
  @import url('../assets/css/responsive.css');
</style>
