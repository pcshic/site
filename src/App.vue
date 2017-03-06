<template>
<div id="app" class="ui center aligned container">
  <router-view></router-view>
</div>
</template>

<script>
import _ from 'lodash'
import $ from 'jquery'

/**
 *  Setup jQuery
 */
window.jQuery = window.$ = $

/**
 *  semantic UI theme
 */
require('semantic-ui-css/semantic.css')
require('semantic-ui-css/semantic.js')

export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: '微軟正黑體','Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 6rem;
}
</style>
