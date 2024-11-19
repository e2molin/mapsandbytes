---
slug: genesispost
title: Beginning Docusaurus 3.6
authors: [e2molin]
tags: [learning]
---

import BeautyTag from '@site/src/components/BeautyTag';
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';


Cosas de resumen de resumen.<BeautyTag color="#ff5753">Add</BeautyTag>

<!-- truncate -->

Imagen en la misma carpeta

![Banner](image/mapparama.jpg)

Podemos introducir pestañas importando los componentes *Tabs* y *TabItem*.
<Tabs>
  <TabItem value="book" label="Book">
  Dive into the world of knowledge with a captivating book
  </TabItem>
  <TabItem value="painting" label="Painting">
  Admire the strokes of artistry on a beautiful painting
  </TabItem>
  <TabItem value="music" label="Music">
  Let the soothing melodies of music transport you
  </TabItem>
</Tabs>




La propiedad `slug` nos permite definir un alias para el post. Es opcional, y si no lo ponemos el post tendrá una URL standard:

* Con slug `property: genesispost`: `http://localhost:3000/blog/genesispost`
* Sin slug property: `http://localhost:3000/blog/2024/11/19/genesis`

:::note

Esto es una *note* al lector

:::

:::info

Esto es un *info* al lector

:::

:::tip

Esto es un *tip* al lector

:::

:::caution

Esto es un *caution* al lector

:::

:::danger

Esto es un *danger* al lector

:::

:::note Esto es una _Custom Title_

Esto es una *Custom Title* al lector

:::


...consectetur adipiscing elit. Pellentesque elementum dignissim ultricies. Fusce rhoncus ipsum tempor eros aliquam consequat. Lorem ipsum dolor sit amet
