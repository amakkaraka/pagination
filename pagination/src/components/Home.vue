<template>
<div>

    <paginate
    :page-count="20"
    :page-range="3"
    :margin-pages="2"
    :click-handler="clickCallback"
    :prev-text="'Prev'"
    :next-text="'Next'"
    :container-class="'pagination'"
    :page-class="'page-item'"
  >
</div>
</template>

<script setup>

const clickCallback = (page) => {
  console.log(page)
}
</script> 