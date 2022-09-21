<template>
    <div class="jumbo">
        <h1>io sono un jumbotron (credo)</h1>
    </div>
</template>

<script>
export default {
    name: "JumboTron",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbo {
    background-color: rgb(181, 222, 121);

    padding: 30px;
    border-radius: 2rem;
    h1 {
        font-size: 3rem;
        color: white;
    }
}
</style>
