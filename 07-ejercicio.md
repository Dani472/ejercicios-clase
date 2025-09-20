# Ejercicio: Función Genérica 

## Enunciado

Crea una función genérica llamada `crearCaja<T>` que reciba un valor de cualquier tipo y lo devuelva dentro de un objeto con la propiedad `contenido`.

---

### Ejemplos

```typescript
crearCaja(5) // { contenido: 5 }
crearCaja("pizza") // { contenido: "pizza" }
```

---

## Prueba la función con distintos tipos de datos:

- Un **número**
- Un **string**
- Un **objeto** (por ejemplo, una comida con nombre y calorías)

Muestra en consola los resultados para ver cómo el tipo se adapta automáticamente.