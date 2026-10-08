# Guía de Markdown en Discord / Discord Markdown Guide

Una guía para darle un toque más bonito a tus mensajes de Discord :)
A markdown guide for Discord, use it to give a more beautiful touch to your messages :)

- 🇪🇸 [Español](#guía-de-markdown-en-discord)
- 🇬🇧 [English](#markdown-guide-discord)

---

# Guía de Markdown en Discord

#### Acá explico cómo usar el markdown que tiene Discord, el cual puede usarse en móvil y en PC.

En cada ejemplo verás **lo que tienes que escribir** dentro de un bloque gris, y debajo **cómo se verá** en Discord.

## Índice

1. [Diseños de texto](#diseños)
2. [Combinar diseños](#combinar-diseños)
3. [Spoilers](#spoilers)
4. [Títulos y subtexto](#títulos-y-subtexto)
5. [Citas](#citas)
6. [Listas](#listas)
7. [Código](#código)
8. [Enlaces con texto](#enlaces-con-texto)
9. [Marcas de tiempo](#marcas-de-tiempo)
10. [Menciones y emojis](#menciones-y-emojis)
11. [Cómo evitar el formato](#cómo-evitar-el-formato)
12. [Tabla resumen](#tabla-resumen)

### Diseños

#### Si quieres tener una letra más notoria, la cual llame la atención, podrás usar "*"

| Diseño | Escribes | Resultado |
|---|---|---|
| Cursiva | `*texto*` o `_texto_` | *texto* |
| Negrita | `**texto**` | **texto** |
| Negrita y cursiva | `***texto***` | ***texto*** |
| Subrayado | `__texto__` | <ins>texto</ins> |
| Tachado | `~~texto~~` | ~~texto~~ |

> 💡 Un asterisco pone la letra en cursiva, dos en negrita y tres en ambas.

### Combinar diseños

Los diseños se pueden mezclar. Solo tienes que abrir y cerrar los símbolos en el orden contrario:

| Diseño | Escribes |
|---|---|
| Subrayado y cursiva | `__*texto*__` |
| Subrayado y negrita | `__**texto**__` |
| Subrayado, negrita y cursiva | `__***texto***__` |
| Tachado y negrita | `~~**texto**~~` |

### Spoilers

Para ocultar un texto hasta que alguien le haga clic, rodéalo con dos barras verticales `||`:

```
||El final de la película es una sorpresa||
```

El texto aparecerá tapado con un recuadro negro hasta que lo toquen.

### Títulos y subtexto

Puedes escribir títulos de tres tamaños poniendo `#` al **inicio de la línea**, seguido de un espacio:

```
# Título grande
## Título mediano
### Título pequeño
-# Subtexto pequeño y gris
```

> ⚠️ El `#` debe ir al principio de la línea y con un espacio después, si no, no funciona.

### Citas

Para citar una sola línea usa `>` seguido de un espacio. Para citar todo lo que escribas después (varias líneas) usa `>>>`:

```
> Esto es una cita de una línea

>>> Esto es una cita
de varias líneas
hasta el final del mensaje
```

### Listas

Puedes hacer listas con viñetas usando `-` o `*`, y listas numeradas con `1.`. Para hacer una sublista, añade espacios al principio:

```
- Frutas
  - Manzana
  - Pera
- Verduras

1. Primer paso
2. Segundo paso
3. Tercer paso
```

### Código

Para resaltar una palabra o una línea corta, usa una comilla invertida `` ` ``:

```
Usa el comando `/ayuda` para ver la lista
```

Para un bloque de varias líneas usa tres comillas invertidas ` ``` `. Si escribes el nombre de un lenguaje justo después, Discord le pondrá colores:

````
```py
print("Hola, Discord")
```
````

Algunos lenguajes útiles: `py`, `js`, `css`, `html`, `json`, `cs`, `cpp`, `java`, `lua`, `bash`, `md`.

**Truco: texto de colores.** Con algunos lenguajes puedes "pintar" texto aunque no sea código:

````
```diff
+ Esto se ve verde
- Esto se ve rojo
```
````

````
```fix
Esto se ve amarillo
```
````

> 💡 El texto dentro de un bloque de código **no** recibe ningún otro formato (ni negrita, ni cursiva...).

### Enlaces con texto

Puedes esconder un enlace detrás de un texto:

```
[Visita GitHub](https://github.com)
```

Si quieres que el enlace **no** muestre la vista previa, rodéalo con `< >`:

```
<https://github.com>
```

### Marcas de tiempo

Discord puede mostrar una fecha u hora que se adapta automáticamente a la zona horaria de cada persona. Se escribe `<t:NÚMERO:FORMATO>`, donde `NÚMERO` es el tiempo Unix (lo puedes sacar en páginas como [unixtimestamp.com](https://www.unixtimestamp.com/)).

| Escribes | Resultado (ejemplo) |
|---|---|
| `<t:1684585522:t>` | 7:25 |
| `<t:1684585522:T>` | 7:25:22 |
| `<t:1684585522:d>` | 20/05/2023 |
| `<t:1684585522:D>` | 20 de mayo de 2023 |
| `<t:1684585522:f>` | 20 de mayo de 2023 7:25 |
| `<t:1684585522:F>` | sábado, 20 de mayo de 2023 7:25 |
| `<t:1684585522:R>` | hace 3 años |

### Menciones y emojis

| Qué | Escribes |
|---|---|
| Mencionar a un usuario | `@nombre` o `<@ID_DEL_USUARIO>` |
| Mencionar un rol | `@rol` o `<@&ID_DEL_ROL>` |
| Mencionar un canal | `#canal` o `<#ID_DEL_CANAL>` |
| Emoji | `:nombre_del_emoji:` |

> 💡 Para copiar IDs activa el **Modo desarrollador** en *Ajustes → Avanzado* y luego haz clic derecho (o mantén pulsado en móvil) → *Copiar ID*.

### Cómo evitar el formato

Si quieres que se vean los símbolos tal cual (por ejemplo, un asterisco), pon una barra invertida `\` antes:

```
\*esto no estará en cursiva\*
```

Resultado: \*esto no estará en cursiva\*

### Tabla resumen

| Formato | Sintaxis |
|---|---|
| Cursiva | `*texto*` / `_texto_` |
| Negrita | `**texto**` |
| Subrayado | `__texto__` |
| Tachado | `~~texto~~` |
| Spoiler | `\|\|texto\|\|` |
| Título | `#`, `##`, `###` |
| Subtexto | `-# texto` |
| Cita | `>` / `>>>` |
| Lista | `-` / `1.` |
| Código | `` `texto` `` / ` ```lenguaje ` |
| Enlace | `[texto](url)` |
| Marca de tiempo | `<t:NÚMERO:FORMATO>` |
| Escapar | `\` |

---

# Markdown guide Discord

#### I'm going to explain how to use the markdown that Discord has, you can use it on computer and cellphone.

In every example you'll see **what you have to type** inside a gray block, and below it **how it will look** on Discord.

## Index

1. [Text styles](#styles)
2. [Combining styles](#combining-styles)
3. [Spoilers](#spoilers-1)
4. [Headers and subtext](#headers-and-subtext)
5. [Quotes](#quotes)
6. [Lists](#lists)
7. [Code](#code)
8. [Masked links](#masked-links)
9. [Timestamps](#timestamps)
10. [Mentions and emojis](#mentions-and-emojis)
11. [Escaping formatting](#escaping-formatting)
12. [Cheat sheet](#cheat-sheet)

### Styles

#### If you want your text to stand out and catch people's attention, you can use "*"

| Style | You type | Result |
|---|---|---|
| Italics | `*text*` or `_text_` | *text* |
| Bold | `**text**` | **text** |
| Bold italics | `***text***` | ***text*** |
| Underline | `__text__` | <ins>text</ins> |
| Strikethrough | `~~text~~` | ~~text~~ |

> 💡 One asterisk makes italics, two make bold and three make both.

### Combining styles

Styles can be mixed. Just open and close the symbols in reverse order:

| Style | You type |
|---|---|
| Underline italics | `__*text*__` |
| Underline bold | `__**text**__` |
| Underline bold italics | `__***text***__` |
| Strikethrough bold | `~~**text**~~` |

### Spoilers

To hide text until someone clicks it, wrap it in two vertical bars `||`:

```
||The ending of the movie is a surprise||
```

The text will be covered by a black box until someone taps it.

### Headers and subtext

You can write headers in three sizes by putting `#` at the **start of the line**, followed by a space:

```
# Big header
## Medium header
### Small header
-# Small gray subtext
```

> ⚠️ The `#` must be at the start of the line and followed by a space, otherwise it won't work.

### Quotes

To quote a single line use `>` followed by a space. To quote everything after it (multiple lines) use `>>>`:

```
> This is a one-line quote

>>> This is a quote
spanning multiple lines
until the end of the message
```

### Lists

You can make bulleted lists with `-` or `*`, and numbered lists with `1.`. Add spaces at the start to make a sub-list:

```
- Fruits
  - Apple
  - Pear
- Vegetables

1. First step
2. Second step
3. Third step
```

### Code

To highlight a word or short line, use one backtick `` ` ``:

```
Use the `/help` command to see the list
```

For a multi-line block use three backticks ` ``` `. If you write a language name right after them, Discord will add syntax colors:

````
```py
print("Hello, Discord")
```
````

Some useful languages: `py`, `js`, `css`, `html`, `json`, `cs`, `cpp`, `java`, `lua`, `bash`, `md`.

**Trick: colored text.** Some languages let you "paint" text even if it isn't code:

````
```diff
+ This looks green
- This looks red
```
````

````
```fix
This looks yellow
```
````

> 💡 Text inside a code block does **not** get any other formatting (no bold, no italics...).

### Masked links

You can hide a link behind some text:

```
[Visit GitHub](https://github.com)
```

If you want the link to **not** show an embed preview, wrap it in `< >`:

```
<https://github.com>
```

### Timestamps

Discord can show a date or time that automatically adapts to each person's time zone. Type `<t:NUMBER:FORMAT>`, where `NUMBER` is the Unix time (you can get it from sites like [unixtimestamp.com](https://www.unixtimestamp.com/)).

| You type | Result (example) |
|---|---|
| `<t:1684585522:t>` | 7:25 AM |
| `<t:1684585522:T>` | 7:25:22 AM |
| `<t:1684585522:d>` | 05/20/2023 |
| `<t:1684585522:D>` | May 20, 2023 |
| `<t:1684585522:f>` | May 20, 2023 7:25 AM |
| `<t:1684585522:F>` | Saturday, May 20, 2023 7:25 AM |
| `<t:1684585522:R>` | 3 years ago |

### Mentions and emojis

| What | You type |
|---|---|
| Mention a user | `@name` or `<@USER_ID>` |
| Mention a role | `@role` or `<@&ROLE_ID>` |
| Mention a channel | `#channel` or `<#CHANNEL_ID>` |
| Emoji | `:emoji_name:` |

> 💡 To copy IDs, turn on **Developer Mode** in *Settings → Advanced*, then right-click (or long-press on mobile) → *Copy ID*.

### Escaping formatting

If you want the symbols to show as they are (for example, an asterisk), put a backslash `\` before them:

```
\*this won't be italic\*
```

Result: \*this won't be italic\*

### Cheat sheet

| Format | Syntax |
|---|---|
| Italics | `*text*` / `_text_` |
| Bold | `**text**` |
| Underline | `__text__` |
| Strikethrough | `~~text~~` |
| Spoiler | `\|\|text\|\|` |
| Header | `#`, `##`, `###` |
| Subtext | `-# text` |
| Quote | `>` / `>>>` |
| List | `-` / `1.` |
| Code | `` `text` `` / ` ```language ` |
| Masked link | `[text](url)` |
| Timestamp | `<t:NUMBER:FORMAT>` |
| Escape | `\` |
