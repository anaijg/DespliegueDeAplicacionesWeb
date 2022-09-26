---
layout: post
title: Primer post de muestra
subtitle: Lo suyo es que cada post tenga un subtítulo
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

Este es un post de demostración para mostrarte cómo escribir posts con markdown. Te recomiendo encarecidamente que te tomes [5 minutos para aprender a escribir en markdown](https://markdowntutorial.com/) - aprenderás cómo convertir texto normal en negrita/cursiva/encabezados/tablas/etc.

**Aquí un poco de texto en negrita**

## Aquí un encabezado de segundo nivel

Aquí una tabla completamente inútil:

| Número | Siguiente número | Número anterior |
| :------ |:--- | :--- |
| Cinco | Seis | Cuatro |
| Diez | Once | Nueve |
| Siete | Ocho | Seis |
| Dos | Tres | Uno |


¿Te apetece una crepe deliciosa?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

¡Y también podemos centrarla!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.