<template>
  <div>
    <div class="wrapper">
      <div class="title">
        <h2>Example Display Use Vue JS</h2>
      </div>
      <div class="paragraph">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi, ipsam expedita. Asperiores esse corporis reprehenderit totam nulla, eaque voluptate provident, nobis unde distinctio voluptatum harum fugiat laborum magni molestias architecto.</p>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Perspiciatis amet nisi similique explicabo quam illo quaerat dicta pariatur deleniti delectus, maxime dolores animi et recusandae tempore sequi laudantium neque. Doloremque?</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident eligendi obcaecati assumenda corporis illo excepturi vitae aperiam autem natus iusto molestias voluptate hic architecto, nesciunt eveniet delectus, dolor commodi. Nobis!</p>
      </div>
    </div>
    <div class="text-container">
        <div class="text one">
            <h3>Content One</h3>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Praesentium aliquam quidem repudiandae consequuntur atque, nulla quas earum fuga, quis illum architecto corrupti et, ad est nihil? Natus dignissimos temporibus eos?</p>
        </div>
        <div class="text two">
            <h3>Content Two</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab est harum animi natus eaque sit cumque, earum maxime id quibusdam explicabo quidem fugiat repudiandae. Architecto tempore pariatur eligendi ut repellat.</p>
        </div>
        <div class="text three">
            <h3>Content Three</h3>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum, dignissimos. Aliquid vel eaque ad, dolor ipsam dolorem labore unde explicabo incidunt omnis, sint, fuga sunt quos illo natus molestias repudiandae.</p>
        </div>
    </div>
    <div class="galery">
        <div class="image">
            <img src="../assets/one.jpg">
        </div>
        <div class="image">
            <img src="../assets/two.jpg">
        </div>
        <div class="image">
            <img src="../assets/three.jpg">
        </div>
        <div class="image">
            <img src="../assets/four.jpg">
        </div>
        <div class="image">
            <img src="../assets/five.jpg">
        </div>
        <div class="image">
            <img src="../assets/six.jpg">
        </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Display"
};
</script>
<style scoped>
.wrapper {
  background-color: cornflowerblue;
  width: 90%;
  margin: auto;
  padding: 4px;
}
.text-container{
    display: flex;
    width: 90%;
    margin: auto;
    box-sizing: border-box;
}
.galery{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    width: 90%;
    margin: auto;
}
.image{
    width: 50%;
}
.image img{
    width: 100%;
    margin: 3px;
}
.title {
  text-align: center;
}
.paragraph {
  text-align: justify;
  padding: 5px;
}
.text.one{
    margin: 10px;
    padding: 5px;
    background-color: cyan;
    text-align: justify;
}
.text.two{
    margin: 10px;
    padding: 5px;
    background-color: darkgrey;
    text-align: justify;
}
.text.three{
    margin: 10px;
    padding: 5px;
    background-color: darkseagreen;
    text-align: justify;
}
</style>