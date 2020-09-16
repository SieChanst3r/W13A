<template>
    <div class="page-body">
        <div>1</div>
        <div>2</div>
        <div>3</div>

    </div>
</template>

<script>
export default {
    name:"page-body"
}
</script>

<style scoped>
 .page-body {
        display:grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: 1fr 1fr 1fr;
        height: 45vh;
        border: solid black 2px; 
    }
</style>