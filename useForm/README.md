# userForm Hook

Ejemplo de uso: 
```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };
    const [ formValues, handleInputChange, reset ] = useForm(initialForm);
```

useForm() // recibe un valor por defecto de las propiedades del formulario