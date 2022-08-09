<template>
    <header>
        <h2>Welcome</h2>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
        </nav>
    </header>
</template>

<script>
    export default {
        name: 'page-header'
    }
</script>

<style scoped>
header{
    display: grid;
    grid-template-columns: 1fr 1fr;

    background-color: aquamarine;

}

h2, nav{
    align-self: center;
    margin: 35px;
}
h2{
    justify-self: start;
 
}
nav{
    justify-self: end;

    display: grid;
    grid-template-columns: 1fr 1fr;
    column-gap: 15px;


}
</style>