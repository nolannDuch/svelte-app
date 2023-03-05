<script lang="ts">
    export let color: string;
	let clicked = true;

    function handleClick (): void {
		clicked = !clicked;
	}
</script>

<div>
    <button style="color:{color};" on:click={handleClick}>click</button>
    <br/>
    etat du click : {clicked}
</div>

<style>

</style>