# Bloques de Texto (Blockquotes)

Para crear un bloque con texto (cita en bloque o blockquote), se debe añadir `>` al principio del párrafo que se desea remarcar, por ejemplo:

Se debe escribir así:
```
> Mi amigo pedro es super genial, él sí que sabe como tener su propia fiesta.
```

Para que se vea de esta manera:

> Mi amigo pedro es super genial, él sí que sabe como tener su propia fiesta.

En caso de tener más de un párrafo se deberá añadir `>` en cada linea que se desee renderizar (cada párrafo y cada linea en blanco que se desee mostrar)

De esta manera para el siguiente texto:

```
> Mi amigo pedro es super genial, él sí que sabe como tener su propia fiesta.
>
> Es una lástima que no sea tan bueno estudiando.
```

La salida será:

> Mi amigo pedro es super genial, él sí que sabe como tener su propia fiesta.
>
> Es una lástima que no sea tan bueno estudiando.


Dentro del blockquote se pueden tener distintos elementos, como numeraciones, texto inclinado, titulos o incluso otro blockquote dentro.

Para esto se deberá agregar `>>` adelante del párrafo a mostrar dentro del blockquote dentro del blockquote.

Entonces este texto:

```
> Mi amigo pedro es super genial, él sí que sabe como tener su propia fiesta.
>
> Es una lástima que no sea tan bueno estudiando.
```

Tendrá la siguiente salida:

> ## La historia de mi amigo Pedro
> Mi amigo pedro es **super genial**, él sí que sabe como tener su propia fiesta.
>
>> Es una *lástima* que no sea tan bueno ***estudiando***.
