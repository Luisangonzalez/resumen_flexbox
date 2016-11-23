# Flex wrap

Cuando no hay espacio horizontalmente coloca los elementos una debajo de otro, verticalmente, parecido a display block.

* Displaying flex items across multiple lines
* Changing the direction of flex lines
* **Distributing space vertically**

```CSS
.setup {
  border: 1px solid #d1eda6;
  display: flex;
  flex-wrap: wrap;
  
}
```
#### Put in reverse
Renderiza al reves, el primer elemento es colocado el último.

```CSS
.setup { 
border: 1px solid #d1eda6; 
display: flex; 
flex-wrap: wrap-reverse; 
}
```

