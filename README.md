# contadorSvelte

## Contador hecho con Svelte

- Suma
- Resta
- Resetea

```
<script>
	let count = 0;

	const handleClickPlus= ()=> {
		count += 1;
	}
	
	const handleClickless = () =>{
		count -=1
	}
	
	const handleReset=()=>{
		count =0
	}
</script>

<p>
	{count}  {count === 1 ? 'time' : 'times'}
</p>

<button on:click={handleClickPlus}>
	Mas 
</button>

<button on:click={handleClickless}>
	menos 
</button>

<button on:click={handleReset}>
	Reset
</button>

```
