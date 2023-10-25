<script>
	import Note from './Note.svelte';
	
	let notes = [
		{
			id: 1,
			text: 'welcome'
		},
		{
			id: 2,
			text: 'hello'
		},
    {
			id: 3,
			text: 'hii'
		},
		{
			id: 4,
			text: 'preety'
		},
    {
			id: 5,
			text: 'full stack'
		},
		{
			id: 6,
			text: 'bye'
		},
    {
			id: 7,
			text: 'nothing'
		},
		{
			id: 8,
			text: 'whaattt'
		},
    {
			id: 9,
			text: 'really'
		},
		{
			id: 10,
			text: 'How'
		}
	];
</script>

{#each notes as note}
	<Note>
		<div contenteditable>{note.text}</div>
	</Note>
{/each}

<style>
	div {
		background: rgb(132, 132, 239);
		padding: 20px;
		width: 100px;
		text-align: center;
	}
</style>
