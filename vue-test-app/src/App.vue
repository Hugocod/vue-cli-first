<template>
    <div id="app">
        <img alt="Vue logo" src="./assets/logo.webp" />
        <MyTitle msg="Viva React! :P" />
        <JumboTron />
    </div>
</template>

<script>
import MyTitle from "./components/MyTitle";
import JumboTron from "./components/JumboTron";

export default {
    name: "App",
    components: {
        MyTitle,
        JumboTron,
    },
};
</script>

<style lang="scss">
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;

    height: 100vh;

    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;

    img {
        animation: spin 5s infinite;
    }

    @keyframes spin {
        from {
            transform: rotate(0deg);
        }
        to {
            transform: rotate(360deg);
        }
    }
}
</style>
