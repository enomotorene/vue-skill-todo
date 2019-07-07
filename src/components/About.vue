<template>
    <div class="about">
        <h1>Hello {{ their_name }}, This is an about page</h1>
        <p>this is my first vue app</p>
    </div>
</template>


<script>
export default {
  name: 'Skills',
  data(){
    return{
      their_name: this.$route.params.name
    }
  }
}
</script>
