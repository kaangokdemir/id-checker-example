<template lang='pug'>
  nav.navbar.is-light(role='navigation' aria-label='main navigation')
    .navbar-brand
      a.navbar-item(href='/')
        img(src='@/assets/id-logo.svg' width='242' height='28')
      a.navbar-burger.burger(role='button' aria-label='menu' aria-expanded='false' data-target='navbarBasicExample')
        span(aria-hidden='true')
        span(aria-hidden='true')
        span(aria-hidden='true')
    //- #navbarBasicExample.navbar-menu
      .navbar-start
        a.navbar-item
          | Home
        a.navbar-item
          | Documentation
        .navbar-item.has-dropdown.is-hoverable
          a.navbar-link
            | More
          .navbar-dropdown
            a.navbar-item
              | About
            a.navbar-item
              | Jobs
            a.navbar-item
              | Contact
            hr.navbar-divider
            a.navbar-item
              | Report an issue
</template>

<script>
import burger from '@/utilities/navbar-burger'
  export default {
    
  }
</script>

