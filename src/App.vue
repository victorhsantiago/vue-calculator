<template>
    <div id="app">
        <h3>Calculator</h3>
        <Calculator/>
    </div>
</template>

<script>
import Calculator from "./main/Calculator";
export default {
    components: { Calculator }
};
</script>

<style>
@font-face {
    font-family: "RobotoMono";
    src: url("./fonts/RobotoMono-Thin.ttf");
}

* {
    font-family: "RobotoMono", monospace;
}

body {
    margin: 0;
}

#app {
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #fff;
    background: linear-gradient(to right, rgb(19, 106, 138), rgb(38, 120, 113));
}
</style>
