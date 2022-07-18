<template>

    <div class="card">

        <div class="card-image">
            <img :src="imageUrl" :alt="titleBook">
        </div>

        <h5>{{ titleBook }}</h5>

    </div>

</template>

<script>
export default {
    props: {
        imageUrl: String,
        titleBook: String,
    },
}
</script>

<style lang="scss" scoped>
  @import'../styles/variables.scss';



    .card {

        width: calc(100% / 6);

        h5 {
            color: white;
            text-transform: uppercase;
            padding: 5px 15px 30px 15px;
        }

        .card-image {

            width: 100%;
            padding: 0 15px;

            img {
                object-fit: cover;
                object-position: top;
                height: 100%;
                width: 100%;
            }
        }
    }

</style>