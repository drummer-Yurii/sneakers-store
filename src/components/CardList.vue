<script setup>
import Card from './Card.vue'

const onClickAdd = () => {
  alert('111')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      title="Men's Sneakers Nike Blazer Suede"
      imageUrl="/sneakers/sneakers-1.jpg"
      :price="1205"
      :isAdded="true"
      :isFavourite="true"
      :onClickAdd="onClickAdd"
    />
  </div>
</template>
