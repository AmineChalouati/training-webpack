<template>

  <div id="test">
  	<exo mynewmsg="lvl1"mynewestmsg="=>begineer">exo</exo>
    <h1>{{message}}</h1>

  	<exo mynewmsg="lvl2" mynewestmsg="=>hardLevel"></exo>

  </div>
//<slot>

</template>
<script>

  import exo from './components/exo.vue'

export default {
  data () {
    return {
      message : "Les exoers sont les meilleurs now yes no no jhjhjhjhjh dddd!!!"
    }
  },

  components: {
   exo
}

var string = 'exo',
    searchFor = 'is',
    count = 0,
    pos = string.indexOf(searchFor);
}

</script>
  
 