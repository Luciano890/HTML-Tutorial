# HTML para dommies

## Etiquetas de Texto

* `<em></em>` Le da enfasis al texto

```html
<!-- Ejemplo -->

<em>Lorem ipsum dolor sit amet consectetur.</em>
```
**Salida**

![em](./Img/em.png "em")

* `<i></i>` Texto en italico

```html
<!-- Ejemplo -->

<i>Lorem ipsum dolor sit amet consectetur.</i>
```
**Salida**

![i](./Img/i.png "i")

* `<span></span>` Contenedor de elementos en línia

```html
<!-- Ejemplo -->

<span>Lorem ipsum dolor sit amet consectetur.</span>
```
**Salida**

![span](./Img/span.png "span")

* `<mark></mark>` Remarca la relevancia

```html
<!-- Ejemplo -->

Lorem ipsum dolor <mark>sit amet consectetur.</mark>
```
**Salida**

![mark](./Img/mark.png "mark")

* `<b></b>` Pone la letra en negritas

```html
<!-- Ejemplo -->

Lorem ipsum dolor <b>sit amet consectetur.</b>
```
**Salida**

![b](./Img/b.png "b")

* `<u></u>` Subraya el texto

```html
<!-- Ejemplo -->

Lorem ipsum dolor <u>sit amet consectetur.</u>
```
**Salida**

![u](./Img/u.png "u")

* `<strong></strong>` Importancia del texto

```html
<!-- Ejemplo -->

Lorem ipsum dolor <strong>sit amet consectetur.</strong>
```
**Salida**

![strong](./Img/strong.png "strong")

* `<small></small>` El texto no tiene importancia

```html
<!-- Ejemplo -->

Lorem ipsum dolor <small>sit amet consectetur.</small>
```
**Salida**

![small](./Img/small.png "small")

* `<s></s>` El texto se tacha

```html
<!-- Ejemplo -->

Lorem ipsum dolor <s>sit amet consectetur.</s>
```
**Salida**

![s](./Img/s.png "s")

* `<cite></cite>` Mención a un proyecto

```html
<!-- Ejemplo -->

Lorem ipsum dolor <cite>sit amet consectetur.</cite>
```
**Salida**

![cite](./Img/cite.png "cite")

* `<sup></sup>` Superíndice

```html
<!-- Ejemplo -->

x<sup>2</sup> + 1 = 0
```
**Salida**

![sup](./Img/sup.png "sup")

* `<sub></sub>` Subíndice

```html
<!-- Ejemplo -->

H<sub>2</sub>O
```
**Salida**

![sub](./Img/sub.png "sub")

___

## Títulos

```html
    <h1>Hola Mundo!!</h1>
    <h2>Hola Mundo!!</h2>
    <h3>Hola Mundo!!</h3>
    <h4>Hola Mundo!!</h4>
    <h5>Hola Mundo!!</h5>
    <h6>Hola Mundo!!</h6>
```
**Salida**

![Títulos](./Img/h.png "títulos")

___

## Plantilla Semántica Página Web

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Styles.css">
    <title>Main</title>
</head>
<body>
    <!-- Plantilla semántica HTML para una página -->
    <header>
        <nav>
            <ul>
                <li><a href="#">Menu 1</a></li>
                <li><a href="#">Menu 2</a></li>
                <li><a href="#">Menu 3</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis, soluta.</p>
        </section>
        <aside>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing.</p>
        </aside>
        <article>
            <span>Hola Mundo!!</span>
        </article>
    </main>
    <footer>
        <strong>Derechos Luciano 2021</strong>
    </footer>
</body>
</html>
```
