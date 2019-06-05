<script>
    export let value;
</script>
<style type="text/scss">
div {
    box-sizing: border-box;
}
button {
    font-size: inherit;
    //color: blue;
    border-radius: 15px;
    padding: 5px 10px;
}
</style>
<button><slot/></button>