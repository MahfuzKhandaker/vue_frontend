<template>
    <div class="column is-4">
    <div class="level">
        <div class="level-item">
            <figure class="image is-128X128">
                <img v-bind:src="product.get_thumbnail">
            </figure>
        </div>
    </div>
    <h5 class="title is-5">Angelina Jolie</h5>
    <p class="subtitle is-6">CEO</p>
    <p>When I'm not obsessively stressing ...</p>
</div>


</template>

<script>
export default {
    name: 'ProductBox',
    props: {
        product: Object
    }
}
</script>

<style scoped>
  .image {
    margin-top: -1.25rem;
    margin-left: -1.25rem;
    margin-right: -1.25rem;
  }
</style>