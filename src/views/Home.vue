<template>
  <div id="home">
    <button class="uppercase mt-10 mx-auto active:bg-blue-700 focus:outline-none">click me</button>
    <div class="content container mx-auto shadow-2xl">
      <h2 class="capitalize">this is title</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor ducimus eveniet aspernatur veniam et magni repudiandae libero. Consequatur nisi asperiores possimus voluptate sint officiis, corporis accusamus aperiam molestiae veritatis natus.</p>
      <a href="#" class="text-gray-600 hover:text-gray-300 hover:underline">This is a link</a>
    </div>
  </div>
</template>

<style lang="scss">
$white: white;
.content{
  padding: 2rem 4rem;
  background-color: rgb(3, 20, 44);
  h2{
    color: $white;
    font-size: 1.5rem;
  }
  p{
    color: $white;
  }
}

</style>