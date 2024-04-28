# CONCEPTO DE NOMENCLATURA CSS

## Authors

- [@GallegoKevin](https://github.com/GallegoKevin/SMACSS_TUTORIA)
 

## BEM

1. Bloque (Block): Representa una entidad independiente, componente y /0 modulo de alto nivel en la interfaz.
2. Elemento (Element): Cada elemento que conforma el bloque.
3. Modificador (Modifier): Variaciones de un bloque o elemento que alteran o modifican la apariencia o comportamiento.

```
.bloque {}
.bloque__elemento {}
.bloque-
-modificador {}
```

```
.menu {...}
.menu__item {...}
.menu__item--active {...}
```


## SUITCSS

1. Componente (Component): Representa una entidad independiente y modular en la interfaz.
2. Elemento (Element): Partes de un componente que tienen significado solo en el contexto del componente padre.
3. Modificador (Modifier): Variaciones de un componente o elemento que alteran su apariencia o comportamiento.

```
.Component {}
.Component-Element {}
.Component-Element_modifier {}
```

```
.Menu {...}
.Menu-item {...}
.Menu-link {...}
.Menu--active {...}
.Menu--isLiked {...}
```

# SMACSS (Scalable and Modular Architecture for CSS) 

Metodología para organizar y estructurar código CSS. Se centra en cinco categorías principales:
1. Base: Contiene estilos generales. Tales como estilos de texto básicos y estilos de elementos HTML comunes.
Ejemplo: 
```
/* Resetear estilos */
html, body, h1, p, a {
  margin: 0;
  padding: 0;
}

/* Estilos básicos */
body {
  font-family: Arial, sans-serif;
  font-size: 16px;
  line-height: 1.5;
  background-color: #f0f0f0;
}

h1 {
  font-size: 24px;
}

p {
  margin-bottom: 10px;
}


```
2. Layout: Define la estructura general de la página, la ubicación de elementos principales como el header, el footer , etc.
Por ejemplo:

```
.header {
  background-color: #333;
  color: #fff;
  padding: 10px 20px;
}

.footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px 0;
}
```

3. Modules: Agrupa componentes independientes y reutilizables.Tales como botones, tarjetas, formularios, etc.
```
.card {
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-radius: 4px;
  padding: 20px;
  margin-bottom: 20px;
}
```
4. State: Maneja los estados de los elementos. Tales como :hover, :active, :focus, etc., así como los estados de interacción, como .is-active, .is-hidden, etc.

```
.btn:hover {
  background-color: #0056b3;
}

input:focus {
  border-color: #007bff;
  box-shadow: 0 0 0 2px rgba(0, 123, 255, 0.25);
}
```

5. Themes: Permite crear variaciones visuales del diseño, como temas de color, tipografía alternativa, etc.
```
$First-text-shadow : 2px 2px 4px rgb(131, 224, 220);
$First-color: white;
```


## MY WEBSITE


## Captura de Navegador 

![Pestaña Servicios](https://i.ibb.co/1qFG5YZ/servicios.png)

![Pestaña Inicio](https://i.ibb.co/ScFNkrh/Inicio.png)


## 🔗 Links
[![SMACSS_TUTORIA](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/GallegoKevin/SMACSS_TUTORIA.git)

