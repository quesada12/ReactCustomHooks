# useForm Hook

Ejemplo:
```javascript

    const initialForm = {
        name:'',
        age:0,
        email:''
    }

    const [formValues, handleInputChange,reset] = useForm(initialForm); 

   //handleInputChange
   <input 
      name='email'
      onChange={ handleInputChange }
   />

   //reset
   const handleSubmit = e => {
       e.preventDefault();
       // ...
       reset();
   }

```