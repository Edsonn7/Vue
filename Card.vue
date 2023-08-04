<template>
    <div>
        <img src="url" alt="Vue.js">
        <h2>Vue.js</h2>
        <a href="https://cdn.svgporn.com/logos/vue.svg?response-content-disposition=attachment%3Bfilename%3Dvue.svg" target="blank">
          Downland
        </a>
    </div>
</template>

<script>
export default {
    props: ["url"],
};
</script>

<style scoped>
div{
  display: inline-block;
  text-align: center;
  border: 1px solid #f2f2f2;
  padding: 1%;
  border-radius: 5px;
  margin: 4px ;
}

img {
  width: 10rem;
  padding: 0.5rem;
  background: antiquewhite;
}

a{
    text-decoration: none;
    color: snow;
    background: #160c31;
    padding: .5rem;
    border-radius: 5px;
    border: 1px solid #f2f2f2;
}

</style>