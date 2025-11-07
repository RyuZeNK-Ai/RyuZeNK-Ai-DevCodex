<h1 align="center"> 🧠 Variables en Python 🧠 </h1>

- Una **variable** es un **nombre** que se utiliza para **guardar un valor** en la memoria.
- Python detecta automáticamente el tipo de dato (esto se llama **tipado dinámico**).

## 🧩 ¿Cómo se crea una variable?

```python
nombre_variable = valor
```


### ✅ Ejemplos:
```python
nombre = "RyuZeNK.Ai"      # string (texto)
edad = 27                  # int (entero)
altura = 1.80              # float (decimal)
es_estudiante = True       # booleano (verdadero o falso)
```

## 🔁 Cambiar el valor (reasignación)

```python
nivel = 1
nivel = nivel + 1  # ahora nivel vale 2
```

---

## 🎨 Reglas importantes

| Evitar ❌ | Usar ✅ |
|---------|---------|
| `Nombre = "Ryu"` | `nombre = "Ryu"` |
| `miVariable = 10` | `mi_variable = 10` |
| `1usuario = "Ari"` | `usuario1 = "Ari"` |

---

## ⚡ Errores comunes

- Usar nombres sin significado:
  ```python
  x = 10        # ❌ mal
  vida_inicial = 10  # ✅ bien
  ```

  - Cambiar el valor de una **constante** (las constantes van en MAYÚSCULAS):
  ```python
  PI = 3.1416  # deberías mantenerla igual
  ```

  
## ♻️ Python permite cambiar el tipo de una variable

- Python ajusta el tipo automáticamente según el valor, esto se llama tipado dinámico.
  ```python
  x = 10        # int
  x = "Hola"    # ahora es str
  ```

## 🧱 Buenas prácticas para nombrar variables

- Usa snake_case → nombres en minúscula con guiones bajos.
- Nombres claros y descriptivos.
- Evita abreviaciones sin sentido.
- Evita una sola letra (salvo en ciclos o matemáticas).
  ```python
  #  ✅ Bien
  puntos_actuales = 120
  nombre_usuario = "Ryu"

  # ❌ Mal
  pa = 120
  nU = "Ryu"
  ```

## 🏋️ Mini práctica

Crea estas variables y muéstralas con `print()`:

```python
usuario = "RyuZeNK.Ai"
xp = 120
nivel = 3
es_vip = True

print(usuario, xp, nivel, es_vip)
```
```python
RyuZeNK.Ai 120 3 True
```

## 🔍 Comprobando el tipo de dato

Puedes ver el tipo del valor guardado usando `type()`:

```python
nombre = "Ryu"
print(type(nombre))   # <class 'str'>




## 🧬 Resumen rápido
- Una variable **guarda un valor**.
- Python **no necesita declarar tipo**.
- Usar nombres **claros y descriptivos**.
