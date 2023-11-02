# Notas de MARKDOWN

---

<center><h2>Tabla de contenido</h2></center>

---

- Texto
  - [Encabezados](#encabezados)
  - [Párrafos](#párrafos-de-texto)
  - [Saltos de Línea](#saltos-de-línea)
  - [En Negrita](#texto-en-negrita)
  - [En Cursiva](#texto-en-cursiva)
  - [En Negrita y Cursiva](#texto-en-cursiva-y-negrita-a-la-vez)
  - [Texto Tachado](#texto-tachado)
- Links
  - [Links normales](#links-normales)
  - [Links a partes del documento](#links-a-partes-del-documento)
  - [Links que sean algo más que texto](#links-que-sean-algo-más-que-texto-imágenes)
- [Imágenes](#imágenes)
- Listas
  - [Listas desordenadas](#listas-desordenadas)
  - [Listas ordenadas](#listas-ordenadas)
- [Tablas](#tablas)
- [Bloques de código](#bloques-de-código)
  - [Bloques de código in-line](#bloques-de-código-in-line)
  - [Bloques multi-linea y con lenguaje específico](#bloques-multi-linea-y-con-lenguaje-específico)
- [Citas](#citas)
- [Lista de Tareas (checkbox)](#lista-de-tareas-checkbox)

---

## Textos

---

### Encabezados

Para definis los "títulos" o encabezados de nuestras diferentes secciones utilizamos el símbolo `#`.
Escribiremos un `#` hasta un máximo de seis `#` para marcar la como si de un ínice de un libro la importancia de nuestros encabezados o "títulos".

Ejemplo:

# esto es un encabezado o título de nivel 1

## esto es un encabezado o título de nivel 2

### esto es un encabezado o título de nivel 3

#### esto es un encabezado o título de nivel 4

##### esto es un encabezado o título de nivel 5

###### esto es un encabezado o título de nivel 6

---

### Párrafos de texto

---

Para escribir párrafos de texto no es necesario especificar con ningún símbolo o indentación específica, simplemente se comienza a escribir y listo.

---

### Saltos de línea

---

Para definir saltos de línea en párrafos, tenemos varias opciones dependiendo del "sabor" de markdown que estemos utilizando.

En la mayoría de editores y navegadores modernos, sólo necesitaremos darle al `Enter` y sería suficiente, pero para estar 100% seguro, deberíamos escribir:

**2 espacios seguidos**

No se me ocurre de que manera mostrarlo sin estar viendo el archivo original en MarkDown, así que para este ejemplo debeis visualizar esto ne el editor.

---

## **Párrafo de ejemplo con saltos de línea mediante espacios visualizado en editor antiguo o navegador antiguo.**

Lorem ipsum dolor,  
sit, amet consectetur adipisicing elit. Incidunt nemo, maxime.  
Distinctio similique et perspiciatis nisi officiis eum placeat delectus illo cupiditate voluptate aliquam voluptatem, porro adipisci qui, libero reiciendis maxime quia!  
Magnam, libero velit optio iste distinctio non tempore.

### Texto en negrita

---

`se utiliza **TEXTO EN NEGRITA** entre 2 asteriscos`

ejemplo:

**TEXTO EN NEGRITA**

### Texto en cursiva

---

`se utiliza *TEXTO EN NEGRITA* entre 1 asteriscos`

ejemplo:

_TEXTO EN CURSIVA_

### Texto en cursiva y negrita a la vez

---

`se utiliza ***TEXTO EN NEGRITA y CURSIVA*** entre 3 asteriscos`

ejemplo:

**_TEXTO EN CURSIVA_**

### Texto tachado

---

`se utiliza ~~Tachado~~ entre 2 ~`

ejemplo:

~~tachado~~

---

## Links

---

### Links normales

`[aqui va el texto que se verá](aquí va la URL a la que queremos navegar)`

ejemplo:

`[link a google](http://www.google.com)`
[link a google](http://www.google.com)

---

### Links a partes del documento

`[aqui va el texto que se verá](#parte del documento a la que queremos ir con el símbolo # delante)`

ejemplo:

`[link al inicio del documento](#notas-de-markdown)`
[link al inicio del documento](#notas-de-markdown)

---

### Links que sean algo más que texto (imágenes)

antes de nada habría que saber comoo se ponen [imágenes](#imágenes) en documentos de Markdown

`[aqui va la imágen en formato ![alt text](link de imágen)](link o #link)`

ejemplo:

`[![emoji de fonsidev](./img1.png)](http://www.google.com)`
[![emoji de fonsidev](./img1.png)](http://www.google.com)

---

## Imágenes

Es como un link, pero hay que poner primero el símbolo de exclamación `!`.
A parte de eso el link de la imagen puede ser externo o interno desde la ruta que sea.

(ejemplo básicamente el de arriba con link, pero sin la parte del link.)

estructura:
`!` + `[alt text]` + `(dirección del link donde está la imagen)`

ejemplo:

`![emoji de fonsidev](./img1.png)`
![emoji de fonsidev](./img1.png)

---

## Listas

### Listas desordenadas

```
- utilizar el dash
* o utilizar el asterisco
* todo seguido por un espacio y luego el texto
	* también si tabulamos cambiará el símbolo pero se creará una lista dentro de la lista.
```

ejemplo:

```
- item 1
- item 2
- item 3
	- subitem 1
	- subitem 2
	- subitem 3
```

output:

- item 1
- item 2
- item 3
  - subitem 1
  - subitem 2
  - subitem 3

### Listas ordenadas

lo mismo pero con 1. / a. / A.
(dependiendo de la versión de markdown que se use las a. ó A. puede no funcionar así que aconsejo el número.)
y no hace falta marcar 2. ... 3. ... 4. ...

si usas la extensión que recomiendo lo hace automáticamente, pero sino, puedes poner 1. ... 1. ... 1. ... 1... pero el output será lo mismo

ejemplo:

```
1. item 1
1. item 2
1. item 3
1. item 4
```

1. item 1
1. item 2
1. item 3
1. item 4

---

## Tablas

formato para crear tablas de contenido:

```
---

| Comando      | ejecución         |
| ------------ | ----------------- |
| commando + W | cerrar ventana    |
| commando + Q | cerrar aplicación |
```

output:

| Comando      | ejecución         |
| ------------ | ----------------- |
| commando + W | cerrar ventana    |
| commando + Q | cerrar aplicación |

## Bloques de código

para especificar commandos de teclado o algún caracter en programación que normalmente los navegadores o editores de código interpretarían como código real, pero nosotros lo queremos mostrar por motivos de usabilidad etc.

### Bloques de código in-line

ejemplo:

el contenido que se quiere mostrar "tal cual", debe encontrarse entre este símbolo `. (si hay dudas mirar el archivo markdown)

en el lenguaje HTML el tag que debe envolver el contenido principal de la página es `<main>`, es erróneo utilizar `<div>`.

### Bloques multi-linea y con lenguaje específico

en vez de usar sólo 1 símbolo de estos ( ` ), se usan 3 ``` al principio y 3 al final que crean un bloque donde podemos escribir tanto código como queramos

ejemplo sin lenguaje:

```
export default function Button () {
	return (
		<>
		<button className={cosas raras}>
			{children}
		</button>

	)
}
```

ejemplo con lenguaje, pero no correcto:
(se pone ```js , o html, o css o lo que sea. en este caso he pueso js, por javascript, pero en realidad puedo mejorarlo, poniendo jsx, para React)

```js
export default function Button () {
	return (
		<>
		<button className={cosas raras}>
			{children}
		</button>

	)
}
```

ejemplo con lenguaje correcto:

```jsx
export default function Button () {
	return (
		<>
		<button className={cosas raras}>
			{children}
		</button>

	)
}
```

---

## Citas

Típica referencia a algo dicho por otra persona, o escrito en algun recurso que se quiera mostrar.

se utiliza el símbolo `>` y luego se escribe el texto de la cita.

ejemplo:

```
> *Lorem ipsum dolor, sit amet consectetur adipisicing elit.
Consequuntur hic quod libero, nesciunt reprehenderit.*
```

> _Lorem ipsum dolor, sit amet consectetur adipisicing elit. Consequuntur hic quod libero, nesciunt reprehenderit._

y obviamente lo puedes mezclar con cursiba, negrita, link etc.

ejemplo:

```
> *Lorem ipsum dolor, sit amet consectetur adipisicing elit. Consequuntur hic quod libero, nesciunt reprehenderit.*
> *by* ***[Alfonso Martín](http://www.alfonsomartingarcia.com)***
```

> _Lorem ipsum dolor, sit amet consectetur adipisicing elit. Consequuntur hic quod libero, nesciunt reprehenderit._ > _by_ **_[Alfonso Martín](http://www.alfonsomartingarcia.com)_**

---

## Lista de Tareas (checkbox)

se utiliza poniendo:
hay que poner símbolo `-` **un espacio** + `[ ]` (con **UN ESPCIO EN MEDIO**) + `texto de la tarea`
` - [ ] textp de la lista`

ejemplo:

```
- [x] lista de coasa por hacer en un proyecto
- [ ] lista de coasa por hacer en un proyecto
- [ ] lista de coasa por hacer en un proyecto
- [ ] lista de coasa por hacer en un proyecto
```

output:

- [x] lista de coasa por hacer en un proyecto
- [ ] lista de coasa por hacer en un proyecto
- [ ] lista de coasa por hacer en un proyecto
- [ ] lista de coasa por hacer en un proyecto
