# useCounter Hook

Ejemplo:
```javascript

    const {counter, increment, decrement, reset} = useCounter(12); //Recibe un valor inicial

    // INCREMENTAR +1
    <button
        onClick= { increment }
    >
        Incrementar
    </button>

    // DECREMENTAR -1
    <button
        onClick= { decrement }
    >
        Decrementar
    </button>

    // INCREMENTAR
    <button
        onClick= { reset }
    >
        Reset
    </button>
    

```