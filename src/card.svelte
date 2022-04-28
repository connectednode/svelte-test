<script>
    export let card = {
        suit : "",
        face: ""
        }


</script>

<style>
    div {
        border-style: solid;
        border-width: 10px;
        border-color: black;
        border-radius: 30px;
        height: 92mm;
        width: 59mm;
        font-size: xx-large;
    }
</style>

<div>
    {card.suit}
    <br>
    {card.face}
</div>