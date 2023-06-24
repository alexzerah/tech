# Svelte

## JS

Svelte / Svelte kit

Svelte kit : Svelte + vite.

Svelte est un ensemble de composantes.

Composant : HTML + JS + CSS.

`composant.svelte`.

```(javascript)
<script>
  let name = "Svelte";
</script>

<h1>Hello {svelte}</h1>
```

Dans les `{}` c'est n'importe quel code JS (ex: `name.toUpperCase()`).

## Style

```(js)
<style>
h1 {
  color: red;
}
</style>
```

Les règles sont appliquées au composant seulement (*scoped to the composant*).

## Souces

- [Svelte dev docs](https://svelte.dev/)