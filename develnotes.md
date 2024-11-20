Para craer un bolilerplate de Docusarurus, usamos el comando

```bash
npx create-docusaurus@latest mapsandbytes classic
```

Cabeceras de los  ficheros markdown
https://docusaurus.io/docs/api/plugins/@docusaurus/plugin-content-docs#markdown-front-matter

Markdown language and extras
https://docusaurus.io/docs/markdown-features

  --gray-ign: #f5f5f5;
  --black-ign: #636466;
  --orange-ign:#db8239;
  --blue-soft-ign: #accce6;
  --blue-light-ign: #71A7D3;
  --blue-medium-ign: #0077b3;
  --blue-dark-ign:#364b5f;
  --height-header: 4rem;
  --ign-black-font: #636466;
  --ign-orange-font: #db8239;
  --ign-blue-font: #72a8d3;
  --ign-blue-intense-font: #0079fd;
  --black-darkest: #313131;
  
  
  Conceptos en SVG
    https://undraw.co/
 Generacion de Faviconos
 https://favicon.io/
 Ejemplo
 https://github.com/FedericoTartarini?tab=repositories
 https://www.youtube.com/watch?v=xKOhIJQi84w
 Instalar Algolia Search bar
 
 npm install --save @easyops-cn/docusaurus-search-local
 
 
 
 git init
 git add .
 git commit -m "First version of the site"
 -- Una vez cerado el repositorio
 git remote add origin https://github.com/e2molin/mapsandbytes
 git branch -M main
 git push -u origin main
 
 
import React from "react";

export const BeautyTag =({children,color}) =>(
  <span
    style={{
      backgroundColor:color,
      borderRadius: "4px",
      color: "#fff",
      padding: "0.2rem 0.5rem",
      fontWeight: "bold"
    }}>
    {children}
  </span>
);


 npm install standard --save-dev --package-lock



Para publicar en GitHub Pages tenemos que tner el proyecto Píblico. Esto es fundamental

Seguidamente el la pestaña de Settings de nuestro proyecto Y pestaña `Pages` tenemoxs que configurar varias cosas

* En la sección `Build and deployment` tenemos que elegir la opción Deploy from a branch
* Un poco más abajo en branch seleccionamos la opción de publicar desde la rama `gh-pages`

![](assets/capture-gh-pages.png)

Si la primera vez que lo hacemos todavía no tenemos creada la rama `gh-pages`, podemos lanzar el comando en powershell

```bash
cmd /C 'set "GIT_USER=e2molin" && set CURRENT_BRANCH=main && set USE_SSH=true && npm run deploy'
```

