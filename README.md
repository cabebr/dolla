# cla$$.js

**cla$$.js** lets you manipulate class names. For oldies that don't
support `element.classList`, and for homies that don't want any nonsense.
It's nice and tight, just over 500 bytes minified.

Basic syntax is like

```js
cla$$(element).add(class)
cla$$(element).remove(class)
cla$$(element).toggle(class)
cla$$(element).contains(class)
```

&& you can do cool stuff like

```js
element.addEventListener('click', function() {
  if (cla$$(element).contains('pizza'))
    cla$$(element).add('pepperoni')
});
```

Try it with all your favorite toppings.

dolla dolla bill y'all.
