# Errores Comunes

A continuaci�n presentamos una lista de errores comunes.

---------

```
Error loading plugins: plugin1, ...
```

Este error ocurre porque Gitbook no puede resolver un plugin (o el plugin no es v�lido).
Los plugins externos deben especificarse en el campo `dependencies` de un archivo node.js `package.json`. [M�s informaci�n sobre el formato package.json](https://www.npmjs.org/doc/json.html).

Por ejemplo, si su libro depende del plugin **Auto-cubierta**, necesita un archivo `package.json` con el siguiente contenido:


```json
{
    "name": "mybook",
    "version": "0.0.0",
    "description": "",
    "repository": {
        "type": "git",
        "url": "https://github.com/Me/mybook.git"
    },
    "author": "Me <me@gmail.com>",
    "dependencies": {
        "gitbook-plugin-autocover": "0.0.5"
    }
}
```

---------




