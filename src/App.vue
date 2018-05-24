<template lang='pug'>
  #app
    .row
      .col-md-6.col-md-offset-3.col-xs-12
        h1 Christopher Jennison
        h2 Full Stack Software Engineer
        h3 NodeJS, VueJS, ReactJS, Ruby on Rails, MySQL, PostgreSQL
        hr
        p 
          ul I want to:
            li Work on cool new part time project
            li Learn to go from 0 to 60 on full AWS deployment
            li Build something in a language I have never used before
            li Own a dog
        p Email me at #[a(href="mailto:christopher.neal.jennison@gmail.com") christopher.neal.jennison@gmail.com]
        p Want to learn more about me? Check out my #[a(href="http://chris-jennison.com", target='_blank') official website]
</template>

<script>

export default {
  name: 'app'
}
</script>

<style lang='scss'>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;

    ul li {
      list-style-type: none;
    }
  }
</style>
