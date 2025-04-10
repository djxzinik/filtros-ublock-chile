# filtros-ublock-chile
Mi humilde y famelica colección de bloqueos de paywall de sitios chilenos, por ahora solo tiene dos :3

### filtros para importar

Acá dejo el [archivo](https://raw.githubusercontent.com/djxzinik/filtros-ublock-chile/mistress/filtros.txt) con todos los filtros para ser agregado en ublock.


### filtros individuales


#### BIO-BIO
```js
! Bio-Bio
https://www.biobiochile.cl/assets/js/block/bbcl-annoying-block.css
https://www.biobiochile.cl/assets/js/block/bbcl-annoying-block.es.js
```

#### LA TERCERA
```js
! La Tercera 
www.latercera.com##html:style(overflow: scroll !important;)
www.latercera.com##body:style(overflow: scroll !important;)
www.latercera.com##.paywall:style(display: none !important;)
```