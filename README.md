# Application web design

# 👤 Datos Personales

| Campo | Información |
|-------|-------------|
| **Nombre completo** | Jose Daniel Muñoz Martinez |
| **Matrícula** | 2941584 |
| **Carrera** | Ingeniería en Desarrollo de Software |
| **Semestre** | 7° Semestre |

---

# 📚 Datos de la Materia

| Campo | Información |
|-------|-------------|
| **Asignatura** | Diseño de Aplicaciones Web |
| **Profesor** | Christopher Gerardo Gaytan Diaz |

---

# 📝 ¿Qué es Markdown?

**Markdown** es un lenguaje que permite dar formato a texto plano de manera sencilla, utilizando caracteres especiales como para dejar texto entendible para la documentación o al dejar archivos README.

# 🏷️ Opciones de Etiquetado en Markdown

## 1. Títulos y Subtítulos

Los títulos se crean usando el símbolo `#`. La cantidad de `#` define el nivel del título, del 1 al 6. Se usan para organizar el contenido en secciones y permitir una lectura más clara.

```
# Título nivel 1
## Título nivel 2
### Título nivel 3
#### Título nivel 4
##### Título nivel 5
###### Título nivel 6
```

**Resultado:**

# Título nivel 1
## Título nivel 2
### Título nivel 3

---

## 2. Texto en Negritas y Cursivas

Permiten dar énfasis visual a palabras o frases dentro de un párrafo. Las **negritas** se usan para resaltar información importante, y las *cursivas* para términos técnicos o títulos.

```
**Este texto está en negrita**
*Este texto está en cursiva*
***Este texto está en negrita y cursiva***
```

**Resultado:**

**Este texto está en negrita**

*Este texto está en cursiva*

***Este texto está en negrita y cursiva***

---

## 3. Listas Ordenadas y No Ordenadas

Las listas sirven para enumerar elementos. Las **ordenadas** se usan cuando el orden importa (pasos, instrucciones) y las **no ordenadas** cuando los elementos no tienen jerarquía.

**Lista no ordenada** (con `-` o `*`):

```
- Manzana
- Naranja
- Plátano
```

**Resultado:**

- Manzana
- Naranja
- Plátano

**Lista ordenada** (con números):

```
1. Instalar XAMPP
2. Crear repositorio en GitHub
3. Inicializar Git
4. Hacer el primer commit
```

**Resultado:**

1. Instalar XAMPP
2. Crear repositorio en GitHub
3. Inicializar Git
4. Hacer el primer commit

---

## 4. Enlaces

Permiten insertar hipervínculos dentro del texto. Son útiles para referenciar documentación, repositorios o cualquier recurso externo sin mostrar la URL completa.

```
[Texto visible](https://url-del-enlace.com)
```

**Ejemplo:**

```
[Repositorio en GitHub](https://github.com/JosuzMtz/Application-Web-Design)
```

**Resultado:**

[Repositorio en GitHub](https://github.com/JosuzMtz/Application-Web-Design)

---

## 5. Imágenes

Funcionan igual que los enlaces pero con un `!` al inicio. Se usan para mostrar capturas de pantalla, diagramas o cualquier recurso visual directamente en el documento.

```
![Texto alternativo](https://url-de-la-imagen.com/imagen.png)
```

**Ejemplo:**

```
![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

**Resultado:**

![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

---

## 6. Bloques de Código

Permiten mostrar código fuente con formato especial. Los bloques de una línea usan comillas invertidas `` ` `` y los bloques multilínea usan tres comillas ` ``` `. Son esenciales para documentación técnica.

**Bloque de código multilínea** (especificando el lenguaje para resaltado):

````
```php
<?php
echo "Hola, mundo!";
?>
```
````

**Resultado:**

```php
<?php
echo "Hola, mundo!";
?>
```