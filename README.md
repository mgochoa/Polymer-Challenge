# Primer trabajo de Ing Web con Polymer

**Requisitos**
- Bower: `npm install -g bower`
- Firebase-tools: `npm install -g firebase-tools`
- Polymer: `npm install -g polymer-cli`

**Estructura del proyecto**
```
|- public/   Contiene todo el proyecto de Polymer 1
  |- src/   Contiene los componenets del proyecto
  |- bower_components/   Contiene los paquetes de bower
  |- index.html   Pagina principal donde se llama al componente principal
|- database.rules.json   Es el archivo que tiene los permisos de la base de datos
|- firebase.json   Archivo de configuracion que le dice al proyecto donde desplegar en la nube 
```



**Servir por primera vez**
- `cd public/`
- `bower install`
- `cd ..`
- `firebase serve`

> Firebase sirve la carpeta __public/__ en [http://localhost:5000](http://localhost:5000)


**Desplegar en nube**
- `firebase deploy`
