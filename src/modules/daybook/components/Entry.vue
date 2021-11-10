<template>
  <div 
    class="mb-3 pointer p-2 entry-container"
    @click="$router.push({ name: 'Entry', params: { id: 10} })"
    >
        <div class="entrty-title d-flex">
            <span class="text-success fs-6 fw-bold">10</span>
            <span class="mx-1 fs-6 fw-bold">Noviembre 2021</span>
            <span class="mx-2 fw-light fs-6">, Miércoles</span>
        </div>
        <div class="entry-description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio voluptate perferendis molestias eos tempora. Voluptatem neque deleniti consequatur laboriosam architecto, corrupti amet reiciendis voluptate nihil adipisci, fuga sunt repudiandae facilis?
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Labore culpa quasi amet ullam autem. Quo neque aliquam minus, ab sit aperiam tempore facilis reprehenderit sunt alias quidem illo. 
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .entry-container{

        border-bottom: 1px solid #2c3e50;
        transition: 0.2 all ease-in;

        &:hover {
            background-color: lighten($color: grey, $amount: 45);
            transition: 0.2 all ease-in;
        }

        .entry-description{
    
            font-size: 12px;
            margin:10px auto;
            font-weight: normal;
            text-align: justify;
        }
    }

</style>