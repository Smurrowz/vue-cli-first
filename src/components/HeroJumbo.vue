<template>
  <div class="jumbo" >
    <h1>Hello, world!</h1>
    <p>This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured
      content or information.
    </p>
    <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
    <p >
      <a class="" href="#" role="button">Learn more</a>
    </p>
  </div>
</template>

<style scoped>
 .jumbo {
  height: 400px;
  margin: 0 auto;
  max-width: 700px;
  background-color: rgb(211, 211, 211);
  border-radius: 40px;
  border: 1px dashed black;
  padding: 30px;
 }
 .jumbo h1{
  font-size: 40px;
  color: blue;
 }
 .jumbo p{
  font-size: 1rem;
  text-decoration: underline;
  font-style: italic;
  color: indigo;
 }
 .jumbo p a{
  font-size:2rem;
  color: yellow;
  margin-top: 40px;
  display: inline-block;
 }
</style>


<script>
export default {
  name: 'HeroJumbo',
}
</script>
