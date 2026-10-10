# Seguimiento de precio – PlayStation 5 Digital PRO 2TB

Historial de precios de la consola **PlayStation 5 Digital PRO 2TB** en Colombia, monitoreando **múltiples retailers** (Sony Store, Alkosto, Éxito, Falabella, Mercado Libre, Enjoy VideoGames, entre otros que aparezcan) principalmente vía la pestaña Shopping de Google (`udm=28`), con respaldo de WebSearch y, cuando no está bloqueado, WebFetch directo a las páginas de producto.

**Meta del usuario:** comprarla con al menos **20% de descuento** o por **$3.700.000 COP o menos**.

Este archivo se actualiza automáticamente con una entrada diaria (o más de una, si el tracker corre varias veces el mismo día). Cada entrada indica el precio/oferta observado en cada retailer y su fuente (Google Shopping / WebFetch directo / WebSearch de respaldo).

---

## 2026-09-16

- **Sony Store Colombia**: No se pudo obtener un precio confiable. WebFetch a `store.sony.com.co` falló con error `EGRESS_BLOCKED` (bloqueado por el proxy de red saliente). WebSearch de respaldo (`PS5 Pro Digital 2TB precio site:store.sony.com.co` y variantes sin `site:`) no devolvió el precio de esta consola en los snippets; solo confirmó que la página del producto existe y mostró el precio de un producto distinto (PlayStation Portal). **No se registra cifra de precio — no inventada.**
- **Alkosto**: No se pudo obtener un precio confiable. WebFetch a `www.alkosto.com` falló con error `EGRESS_BLOCKED`. WebSearch de respaldo (`PS5 Pro Digital 2TB precio site:alkosto.com` y variantes) indica que el producto figura actualmente **sin unidades disponibles / agotado** en Alkosto, pero no devolvió el precio propio de Alkosto en los snippets (solo un precio de $3.699.000 COP atribuido a otro retailer distinto, no verificable como precio de Alkosto). **No se registra cifra de precio — no inventada.**
- **Nota**: Primera ejecución del tracker, sin historial previo para comparar. No se pudo obtener precio confiable de ninguna de las dos tiendas hoy (día 1 de posible racha de 2 días sin datos).

---

## 2026-09-16 (actualización — ampliación a múltiples retailers vía Google Shopping)

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas) → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co`, `www.alkosto.com`, `www.falabella.com.co`, `www.mercadolibre.com.co` y `enjoyvideogames.com.co` → todos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con varias consultas para reconstruir precios a partir de los snippets.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | **$4.199.000** (aprox.) | Financiación mencionada: 24 cuotas de $183.325/mes (oferta vigente 1–30 sep 2026 según nota de prensa). Precio **no confirmado por WebFetch directo** (bloqueado) — reconstruido de snippets de WebSearch, tratar con cautela moderada. | WebSearch (snippets + nota de prensa que referencia la oferta de Sony Store; WebFetch directo bloqueado) |
| Éxito | **$4.299.900** | 12 cuotas sin interés. Página: `exito.com/consola-ps5-pro-2-tb-blanco-3192604/p` | WebSearch (snippet del listado de Éxito) |
| Falabella | **$4.999.800** (antes $5.599.800, ~10,7% desc.) | ⚠️ Es un **bundle** "PS5 Pro 2TB Digital + 2 Mandos + Cargador Dobe" (producto 139040647), **no la consola sola** — no es directamente comparable con el resto de precios de esta tabla. No se pudo confirmar el precio de la consola sola (producto 145535455) en los snippets. | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | "Producto agotado" confirmado nuevamente. El mismo código de producto (711719595700) también aparece agotado en Ktronix y Alkomprar (retailers relacionados). | WebSearch |
| Enjoy VideoGames | **$3.699.000** | ⚠️ Aparece como **agotado / sin stock** en el snippet — no se puede comprar actualmente aunque el precio, de ser vigente, ya cumpliría la meta del usuario (≤ $3.700.000 COP). Tratar como referencia, no como oportunidad de compra real hasta confirmar disponibilidad. | WebSearch (`enjoyvideogames.com.co/product/sony-playstation-5-pro-2tb/`) |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos, mencionan envío gratis y cuotas sin interés, pero el precio no apareció en los snippets de búsqueda. | WebSearch |

**Retailers nuevos respecto a la entrada anterior:** Éxito, Falabella (bundle), Enjoy VideoGames y Mercado Libre no habían sido registrados antes (la entrada anterior solo cubría Sony Store y Alkosto, y ambos sin precio). Esta es la primera vez que el tracker logra registrar precios reales para algún retailer.

**Comparación con la entrada anterior (mismo día, ~7 min antes):**
- Sony Store: antes sin dato → hoy ~$4.199.000 (dato nuevo, no hay variación % que calcular).
- Alkosto: antes "agotado, sin precio" → hoy sigue "agotado, sin precio" (sin cambio).
- Todos los demás retailers son nuevos en el tracker (sin precio previo con el cual comparar variación %).

**Precios/ofertas no confirmados por WebFetch directo (Google Shopping y páginas de producto bloqueadas por EGRESS_BLOCKED); todas las cifras de esta sección provienen de snippets de WebSearch y deben tratarse con la cautela correspondiente. No se inventó ninguna cifra: donde no había dato confiable, se dejó explícito.**

---

## 2026-09-17

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries) → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co`, `www.alkosto.com`, `www.falabella.com.co`, `www.mercadolibre.com.co`, `gameplanet.com`, `gameplay.com.co` y `www.elespectador.com` → todos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con múltiples consultas dirigidas por retailer para reconstruir precios a partir de los snippets.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | **$4.199.000** | Financiación: 24 cuotas de $183.325/mes (oferta vigente 1–30 sep 2026). **Sin cambio** respecto a la entrada anterior. WebFetch directo bloqueado; cifra reconstruida de snippets (nota de prensa + listados), tratar con cautela moderada. | WebSearch |
| Éxito | **$4.299.900** | 12 cuotas sin interés. Página: `exito.com/consola-ps5-pro-2-tb-blanco-3192604/p`. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | "Producto agotado" confirmado nuevamente (mismo código 711719595700, también en Alkomprar). Un snippet mencionaba una consulta de "disponibilidad" en la categoría general de consolas, pero no confirma que la PS5 Pro Digital 2TB específica esté en stock — se trata como **sin cambio** respecto a la entrada anterior. | WebSearch |
| Enjoy VideoGames | **$3.699.000** (cifra consistente en varias búsquedas) | Listados en preventa/agotado, con disponibilidad estimada en 15–21 días tras la compra — sigue sin ser una compra inmediata real. **Sin cambio** respecto a la entrada anterior. Un snippet aislado mostró $2.960.000, pero es contradictorio con el resto de resultados y probablemente corresponde a otra variante/producto (posible mezcla con la unidad de disco u otro bundle) — **no se usa** por no ser confiable. | WebSearch |
| Falabella | Sin precio confiable confirmado | Falabella lista al menos 4 variantes/páginas distintas (consola sola y varios bundles). Un snippet devolvió una cifra internamente inconsistente ("29% desc., de $3.689.900 a $4.999.000" — la matemática no cuadra), probablemente por mezclar precios de productos distintos en el resumen de búsqueda. Sin acceso directo (bloqueado) no se puede aislar el precio real de la consola sola. **No se registra cifra — no inventada.** | WebSearch |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (ej. `MCO43294311`, `MCO41975964`) mencionan "cuotas sin interés", pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |

**Comparación con la entrada anterior (2026-09-16, retailer por retailer):**
- Sony Store Colombia: $4.199.000 → $4.199.000 (**sin cambio**).
- Éxito: $4.299.900 → $4.299.900 (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Enjoy VideoGames: $3.699.000 (agotado) → $3.699.000 (agotado/preventa) (**sin cambio real**).
- Falabella: sin cifra confiable (bundle no comparable) → sigue sin cifra confiable (**sin cambio**).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No hubo bajadas de precio, ninguna tienda alcanzó la meta del usuario con disponibilidad real (Enjoy VideoGames sigue en $3.699.000 pero agotado/preventa, igual que ayer), no aparecieron retailers ni ofertas nuevas, y sí se obtuvo precio confiable de al menos un retailer (no aplica la condición de "2 días seguidos sin datos"). **No se cumplió ninguna condición de notificación.**

---

## 2026-09-18

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt) → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co` y `www.alkosto.com` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y dirigidas por retailer (Éxito, Alkosto, Enjoy VideoGames, Falabella, Mercado Libre) para intentar reconstruir precios a partir de los snippets.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | **$4.199.000** (aprox., sin confirmar hoy) | Los snippets de hoy solo repiten la financiación de 24 cuotas de $183.325/mes (oferta 1–30 sep 2026), ya conocida. No se encontró un precio de contado nuevo en los snippets. Se mantiene el último valor conocido como referencia, **sin poder confirmarlo de nuevo hoy**. | WebSearch (sin cifra nueva en snippets; WebFetch directo bloqueado) |
| Éxito | Sin precio confirmado hoy | Los snippets de hoy muestran páginas de producto distintas a las de ayer (`consola-playstation-5-pro-2tb-digital-2-mandos-cargador-dobe-103972507-mp` y `playstation-5-pro-2tb-104366926-mp`), pero ninguno trae el precio en el snippet. No se puede confirmar si el precio de ayer ($4.299.900) sigue vigente. **No se registra cifra nueva — no inventada.** | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Snippet confirma nuevamente "no hay unidades disponibles en este momento" para el mismo código de producto (711719595700). **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Enjoy VideoGames | Sin precio confirmado hoy | Los snippets de hoy no devolvieron precio ni disponibilidad específicos de Enjoy VideoGames para este producto (solo resultados genéricos de otras tiendas). No se puede confirmar si el precio de ayer ($3.699.000, agotado/preventa) sigue vigente. **No se registra cifra nueva — no inventada.** | WebSearch |
| Falabella | Sin precio confiable confirmado (Colombia) | Los snippets de hoy listan al menos 4 páginas de producto distintas en Falabella Colombia (bundle 139040647, variante 73119842, variante 145535455, y la vitrina `shop/ps5-pro`), pero ninguna trae el precio de Colombia en el snippet. Un snippet sí trae una cifra concreta, pero es de **Falabella Perú** (S/ 3.899,90 con 22% de descuento), **no de Colombia** — se descarta por no ser el mercado correcto. **No se registra cifra — no inventada.** | WebSearch |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (`MCO43294311`, `MCO41975964`) mencionan "cuotas sin interés" y envío gratis, igual que en entradas anteriores, pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |

**Comparación con la entrada anterior (2026-09-17, retailer por retailer):**
- Sony Store Colombia: $4.199.000 → no se pudo reconfirmar hoy (sin cifra nueva en snippets); se trata como **sin cambio** ya que no hay evidencia de variación.
- Éxito: $4.299.900 → no se pudo reconfirmar hoy; se trata como **sin cambio** (sin evidencia de variación).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Enjoy VideoGames: $3.699.000 (agotado/preventa) → no se pudo reconfirmar hoy; se trata como **sin cambio** (sin evidencia de variación).
- Falabella: sin cifra confiable para Colombia → sigue sin cifra confiable para Colombia (**sin cambio**).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer (no hubo cifras nuevas que comparar, solo confirmaciones de "sin cambio" o falta de dato). Ningún retailer alcanza la meta del usuario con disponibilidad real. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo. Se obtuvo al menos un dato confiable hoy (Alkosto: agotado, confirmado), por lo que no aplica la condición de "2 días seguidos sin datos confiables". **No se cumplió ninguna condición de notificación.**

---

## 2026-09-19

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt) → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co` y `www.alkosto.com` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y dirigidas por retailer (Sony Store, Éxito, Falabella, Alkosto, Mercado Libre, Enjoy VideoGames) para intentar reconstruir precios a partir de los snippets.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | **$4.199.000** (aprox., sin confirmar hoy) | Los snippets de hoy siguen repitiendo la financiación de 24 cuotas de $183.325/mes (oferta 1–30 sep 2026), ya conocida. No se encontró un precio de contado nuevo en los snippets. Se mantiene el último valor conocido como referencia, **sin poder confirmarlo de nuevo hoy**. | WebSearch (sin cifra nueva en snippets; WebFetch directo bloqueado) |
| Éxito | Sin precio confirmado hoy | Los snippets de hoy muestran dos páginas de producto (`consola-playstation-5-pro-2tb-digital-2-mandos-cargador-dobe-103972507-mp` — bundle con 2 mandos, y `consola-ps5-pro-2-tb-blanco-3192604/p` — consola sola), pero ninguna trae el precio en el snippet. No se puede confirmar si el último precio conocido ($4.299.900, registrado el 2026-09-16) sigue vigente. **No se registra cifra nueva — no inventada.** | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Snippet confirma nuevamente "en este momento el producto no cuenta con unidades disponibles para la venta en nuestra tienda online" para el mismo código de producto (711719595700), también reflejado en Ktronix y Alkomprar. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Enjoy VideoGames | **$3.699.000** | Snippet confirma nuevamente el precio de $3.699.000 COP, pero el producto sigue **agotado / sin stock** — no es una compra inmediata real. **Sin cambio** respecto a las entradas del 2026-09-16 y 2026-09-17 (ayer 09-18 no se había podido reconfirmar). | WebSearch (`enjoyvideogames.com.co/product/sony-playstation-5-pro-2tb/`) |
| Falabella | Sin precio confiable confirmado | Los snippets de hoy listan varias páginas de producto en Falabella Colombia (bundle 139040647, variante 73119842, variante 145535455, variante 139051769, y las vitrinas `shop/ps5-pro` y `shop/playstation-5-pro`), pero ninguna trae el precio en el snippet. **No se registra cifra — no inventada.** | WebSearch |
| Mercado Libre | Sin cifra confirmada en snippets | Listado activo (`MCO43294311` — "PlayStation PS5 PRO HW 2TB Digital Standard color Blanco") menciona "cuotas sin interés" y envío gratis, igual que en entradas anteriores, pero el precio no aparece en el snippet. **Sin cambio** respecto a la entrada anterior. | WebSearch |

**Comparación con la entrada anterior (2026-09-18, retailer por retailer):**
- Sony Store Colombia: ~$4.199.000 (sin confirmar) → ~$4.199.000 (sin confirmar hoy tampoco) (**sin cambio**).
- Éxito: sin cifra nueva desde el 09-16 ($4.299.900) → sigue sin poder reconfirmarse (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Enjoy VideoGames: no se pudo reconfirmar ayer → hoy se reconfirma $3.699.000 (agotado), igual que el último valor conocido del 09-17 (**sin cambio real**).
- Falabella: sin cifra confiable para Colombia → sigue sin cifra confiable (**sin cambio**).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer. Ningún retailer alcanza la meta del usuario con disponibilidad real (Enjoy VideoGames sigue en $3.699.000, que cumpliría el umbral de precio, pero continúa agotado — se trata como referencia, no como oportunidad de compra real, igual que en entradas anteriores). No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo. Se obtuvo al menos un dato confiable hoy (Alkosto y Enjoy VideoGames confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables". **No se cumplió ninguna condición de notificación.**

---

## 2026-09-20

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y dirigidas por retailer (Sony Store, Éxito, Falabella, Alkosto, Mercado Libre, Enjoy VideoGames) para intentar reconstruir precios a partir de los snippets.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | **$4.199.000** (aprox., sin confirmar hoy) | Los snippets de hoy solo repiten la financiación de 24 cuotas de $183.325/mes, ya conocida; no aparece un precio de contado nuevo. Se detectó además una nota internacional (PlayStation.Blog, 27 mar 2026) sobre una subida global de precios de PS5/PS5 Pro efectiva el 2 abr 2026 y una posterior baja en EE. UU. el 21 ago 2026 — ambas son noticias antiguas (no de hoy) y no específicas de Colombia, por lo que **no se cuentan como novedad**. Se mantiene el último valor conocido como referencia, sin poder confirmarlo de nuevo hoy. | WebSearch (sin cifra nueva en snippets; WebFetch directo bloqueado) |
| Éxito | Sin precio confirmado hoy | Los snippets de hoy muestran tres páginas de producto (`consola-playstation-5-pro-2tb-digital-2-mandos-cargador-dobe-103972507-mp`, `playstation-5-pro-2tb-104366926-mp` y `consola-ps5-pro-2-tb-blanco-3192604/p`), pero ninguna trae el precio en el snippet. No se puede confirmar si el último precio conocido ($4.299.900, registrado el 2026-09-16) sigue vigente. **No se registra cifra nueva — no inventada.** | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Snippet confirma nuevamente que el producto (código 711719595700) no cuenta con unidades disponibles, mismo estado reflejado en Alkomprar. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Enjoy VideoGames | Sin precio confirmado hoy (agotado / disponibilidad estimada ~21 días) | Los snippets de hoy confirman que el producto sigue agotado/en backorder, pero no repitieron la cifra exacta ($3.699.000) dentro del snippet. Se mantiene ese valor como última referencia conocida (2026-09-19), **sin poder reconfirmarlo hoy**. | WebSearch |
| Falabella | Sin precio confiable confirmado | Los snippets de hoy listan las mismas variantes/páginas de siempre en Falabella Colombia (bundle 139040647, variante 73119842, variante 145535455, variante 139051769, y las vitrinas `shop/ps5-pro` y `shop/playstation-5-pro`, esta última promocionando "PS5 Pro en Aniversario Falabella"), pero ninguna trae el precio en el snippet. **No se registra cifra — no inventada.** | WebSearch |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (`MCO43294311`, `MCO41975964`) mencionan "cuotas sin interés" y envío gratis, igual que en entradas anteriores, pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |

**Comparación con la entrada anterior (2026-09-19, retailer por retailer):**
- Sony Store Colombia: ~$4.199.000 (sin confirmar) → ~$4.199.000 (sin confirmar hoy tampoco) (**sin cambio**).
- Éxito: sin cifra nueva desde el 09-16 ($4.299.900) → sigue sin poder reconfirmarse (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Enjoy VideoGames: $3.699.000 (agotado, reconfirmado) → agotado/backorder, cifra exacta no reconfirmada hoy en snippet (**sin cambio real**; se mantiene la última cifra conocida como referencia).
- Falabella: sin cifra confiable para Colombia → sigue sin cifra confiable (**sin cambio**).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Retailers nuevos: ninguno confirmado con precio (aparecieron en los snippets nombres ya vistos como Gameplay, Colombian UP, Play For Fun y Puntos Colombia en búsquedas previas de días anteriores, pero hoy no trajeron precio ni son nuevos respecto al radar del tracker). Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer (no hubo cifras nuevas que comparar). Ningún retailer alcanza la meta del usuario con disponibilidad real. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo (la noticia de subida/bajada global de precios de Sony es antigua, no de Colombia, y no constituye novedad de hoy). Se obtuvo al menos un dato confiable hoy (Alkosto: agotado, confirmado), por lo que no aplica la condición de "2 días seguidos sin datos confiables". **No se cumplió ninguna condición de notificación.**

---

## 2026-09-21

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales, dirigidas por retailer, y búsquedas `site:` específicas.

**Nota de calidad de datos:** hoy WebSearch devolvió, para Enjoy VideoGames, **tres cifras distintas y contradictorias** en respuesta a consultas ligeramente distintas sobre la misma URL de producto: $3.699.000, $3.099.000 (rebajado de $3.180.000), y un rango $1.620.000–$1.990.000. Ninguna de las tres pudo confirmarse con texto de snippet real al repetir la búsqueda con `site:enjoyvideogames.com.co`. Ante esta contradicción, y siguiendo la regla de nunca inventar cifras, **no se registra ninguna de las tres como precio de hoy** para Enjoy VideoGames — se trata como dato no confiable hoy (distinto de días anteriores, donde $3.699.000 sí se pudo reconfirmar de forma consistente en los snippets).

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | **$4.199.000** (aprox., sin confirmar hoy) | Un resumen de WebSearch general repite la cifra ya conocida de $4.199.000, pero una búsqueda `site:store.sony.com.co` dirigida no trajo precio en el snippet. Se mantiene el último valor conocido como referencia, sin poder confirmarlo de forma fiable hoy. | WebSearch (cifra no confirmada en snippet directo; WebFetch directo bloqueado) |
| Éxito | Sin precio confirmado hoy | Los snippets de hoy muestran las mismas páginas de producto ya conocidas (`consola-ps5-pro-2-tb-blanco-3192604/p`, `playstation-5-pro-2tb-104366926-mp`), pero ninguna trae el precio. No se puede confirmar si el último precio conocido ($4.299.900, registrado el 2026-09-16) sigue vigente. **No se registra cifra nueva — no inventada.** | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Snippet confirma nuevamente que el producto (código 711719595700) no cuenta con unidades disponibles para la venta en la tienda online. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Falabella | **$4.999.800** (antes $5.599.800, ~11% dcto.) — **pero corresponde a un bundle distinto**, no al producto base | Este precio es del bundle "Consola Playstation 5 Pro 2Tb Digital + 2 Mandos + Cargador Dobe" (producto 139040647): incluye 2 controles DualSense adicionales y un cargador, por lo que **no es comparable** al precio de la consola sola que se viene intentando rastrear en entradas anteriores. Los productos base (73119842, 145535455, 139051769) y la vitrina "PS5 Pro en Aniversario Falabella" siguen sin mostrar precio en los snippets. Este bundle ya se conocía de días anteriores (sin precio); hoy es la primera vez que se logra ver una cifra para él, pero al ser un SKU distinto no se trata como novedad de precio del producto rastreado. | WebSearch |
| Enjoy VideoGames | **Sin cifra confiable hoy** (ver nota de calidad de datos arriba) | Tres cifras contradictorias en distintos resúmenes de WebSearch ($3.699.000 / $3.099.000 / $1.620.000–$1.990.000), ninguna confirmada en snippet real vía `site:` search. Se descarta reportar cualquiera de ellas. Producto sigue apareciendo como agotado en los resultados generales. | WebSearch (no confiable — descartado) |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (`MCO43294311`, `MCO41975964`) mencionan "cuotas sin interés" y envío gratis, igual que en entradas anteriores, pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |

**Comparación con la entrada anterior (2026-09-20, retailer por retailer):**
- Sony Store Colombia: ~$4.199.000 (sin confirmar) → ~$4.199.000 (sin confirmar hoy tampoco) (**sin cambio**).
- Éxito: sin cifra nueva desde el 09-16 ($4.299.900) → sigue sin poder reconfirmarse (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Enjoy VideoGames: $3.699.000 (última cifra confiable, del 09-19) → hoy la cifra es **no confiable** por contradicción entre búsquedas; no se puede afirmar bajada, subida ni "sin cambio" con confianza — se marca como dato perdido, no como variación real.
- Falabella: sin cifra confiable para el producto base → sigue sin cifra confiable para el producto base (**sin cambio**); se obtuvo por primera vez una cifra para un bundle distinto (2 controles + cargador), que no es comparable.
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Retailers nuevos: ninguno con precio confiable nuevo. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% confiable en ningún retailer (la única cifra "nueva" fiable, la del bundle de Falabella, corresponde a un producto distinto al rastreado y por tanto no es comparable). Ningún retailer alcanza la meta del usuario con disponibilidad real. No apareció ningún retailer, bundle nuevo, cupón o cambio de disponibilidad genuinamente nuevo (el bundle de Falabella ya se conocía de entradas previas). Se obtuvo al menos un dato confiable hoy (Alkosto: agotado, confirmado; Falabella: precio de bundle confirmado), por lo que no aplica la condición de "2 días seguidos sin datos confiables". **No se cumplió ninguna condición de notificación.**

---

## 2026-09-22

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y dirigidas por retailer (Sony Store, Éxito, Alkosto, Enjoy VideoGames, Falabella, Mercado Libre), incluyendo dos búsquedas adicionales dirigidas para intentar resolver la contradicción de precios de Enjoy VideoGames.

**Nota de calidad de datos:** al igual que ayer (2026-09-21), Enjoy VideoGames vuelve a mostrar **cifras contradictorias** en los resúmenes de WebSearch para el mismo producto: $3.699.000 en un listado, y $3.180.000 rebajado a $2.960.000 en otro (además de $3.730.000 para el bundle con unidad de disco, que es un producto distinto). Dos búsquedas adicionales dirigidas a confirmar cuál cifra es la vigente no devolvieron el precio en snippet real (solo resultados de retailers estadounidenses no relevantes). Siguiendo la regla de nunca inventar cifras, **no se registra ninguna cifra de Enjoy VideoGames hoy** — segundo día consecutivo con esta contradicción sin resolver.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | Sin precio confirmado hoy | El snippet solo confirma que la página del producto existe (`store.sony.com.co/ps5-pro-hw-2tb/p`), sin precio visible en el resumen. No se puede reconfirmar si el último valor conocido ($4.199.000, del 2026-09-16) sigue vigente. **No se registra cifra — no inventada.** | WebSearch (WebFetch directo bloqueado) |
| Éxito | **$4.299.900** | 12 cuotas sin interés. Página: `exito.com/consola-ps5-pro-2-tb-blanco-3192604/p`. **Sin cambio** respecto a la última cifra confirmada (2026-09-16). | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Snippet confirma nuevamente que el producto (código 711719595700) está agotado / sin unidades disponibles. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Enjoy VideoGames | **Sin cifra confiable hoy** (ver nota de calidad de datos arriba) | Segundo día consecutivo con cifras contradictorias ($3.699.000 / $3.180.000→$2.960.000) sin poder confirmarse en snippet real. Se descarta reportar cualquiera de ellas. | WebSearch (no confiable — descartado) |
| Falabella | Sin precio confiable confirmado para el producto base | Los snippets de hoy listan las mismas páginas ya conocidas (producto base 145535455, variante 73119842, variante 139051769, bundle 139040647, vitrinas `shop/ps5-pro` y `shop/playstation-5-pro`), pero ninguna trae el precio en el snippet. **No se registra cifra — no inventada.** | WebSearch |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (`MCO43294311`, `MCO41975964`) mencionan "cuotas sin interés", igual que en entradas anteriores, pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |

**Comparación con la entrada anterior (2026-09-21, retailer por retailer):**
- Sony Store Colombia: ~$4.199.000 (sin confirmar) → sin poder reconfirmarse hoy tampoco (**sin cambio**).
- Éxito: $4.299.900 → $4.299.900 (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Enjoy VideoGames: cifra no confiable (contradictoria) → sigue siendo no confiable (contradictoria), segundo día consecutivo (**sin cambio real**, dato perdido ambos días).
- Falabella: sin cifra confiable para el producto base → sigue sin cifra confiable (**sin cambio**).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% confiable en ningún retailer (no hubo cifras nuevas que comparar). Ningún retailer alcanza la meta del usuario con disponibilidad real y datos confiables. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo. Se obtuvo al menos un dato confiable hoy (Éxito y Alkosto confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer" (solo Enjoy VideoGames tiene 2 días seguidos sin dato, no todos los retailers). **No se cumplió ninguna condición de notificación.**

---

## 2026-09-23

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales, dirigidas por retailer (Sony Store, Alkosto, Éxito, Falabella, Mercado Libre, Enjoy VideoGames, Ktronix), incluyendo búsquedas `site:` dirigidas a Sony Store y Enjoy VideoGames.

**Nota de calidad de datos:** Enjoy VideoGames no devolvió ningún resultado propio hoy ni con la consulta general ni con `site:enjoyvideogames.com.co` (los resultados fueron de otros sitios internacionales). Es el tercer día consecutivo (09-21, 09-22, 09-23) sin poder confirmar una cifra confiable para este retailer, tras la contradicción de precios detectada el 09-21. Se detectó además, en el snippet de Sony Store, una mención genérica a una promoción "Days of Play" con financiación al 0% de interés, pero sin precio ni porcentaje de descuento concreto asociado a la PS5 Pro específicamente — **no se cuenta como novedad confirmada** por no incluir cifra verificable.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | Sin precio confirmado hoy (~$4.199.000 como última referencia, sin reconfirmar) | El snippet solo confirma que la página del producto existe (`store.sony.com.co/ps5-pro-hw-2tb/p`) y menciona una promoción genérica "Days of Play" con financiación 0% interés, sin precio ni descuento concreto en el snippet. **No se registra cifra nueva — no inventada.** | WebSearch (WebFetch directo bloqueado) |
| Éxito | **$4.299.900** | 12 cuotas sin interés. Página: `exito.com/consola-ps5-pro-2-tb-blanco-3192604/p`. **Sin cambio** respecto a la última cifra confirmada (2026-09-16, reconfirmada 2026-09-22). | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Snippet confirma nuevamente que el producto (código 711719595700) está agotado / sin unidades disponibles para la venta en la tienda online. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Ktronix | Sin precio confirmado (producto agotado / sin stock) | Retailer nuevo en el radar del tracker (mismo código de producto 711719595700 que Alkosto). El snippet indica que el producto no cuenta con unidades disponibles y no muestra precio. Al no traer cifra ni oferta concreta, **no se cuenta como novedad confirmada** — se deja registrado para seguimiento en próximas entradas. | WebSearch |
| Enjoy VideoGames | **Sin cifra confiable hoy** (ver nota de calidad de datos arriba) | Tercer día consecutivo sin poder confirmar precio para este retailer (contradicción el 09-21, contradicción el 09-22, sin resultados propios el 09-23). | WebSearch (no confiable — descartado) |
| Falabella | **$4.999.800** (antes $5.599.800, ~10,7% dcto.) — bundle "2 Mandos + Cargador Dobe" (SKU 139040647), no el producto base | Misma cifra ya registrada el 2026-09-21 para este bundle; **sin cambio**. Los productos base (73119842, 145535455, 139051769) y la vitrina "PS5 Pro en Aniversario Falabella" siguen sin mostrar precio en los snippets. | WebSearch |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (`MCO43294311`, `MCO41975964`) mencionan "cuotas sin interés", igual que en entradas anteriores, pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |

**Comparación con la entrada anterior (2026-09-22, retailer por retailer):**
- Sony Store Colombia: ~$4.199.000 (sin confirmar) → sin poder reconfirmarse hoy tampoco (**sin cambio**); se detectó mención genérica a promoción "Days of Play" sin cifra concreta (no cuenta como novedad).
- Éxito: $4.299.900 → $4.299.900 (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Enjoy VideoGames: no confiable (09-22) → sigue no confiable, ahora sin ningún resultado propio (09-23) (**sin cambio real**, tercer día de dato perdido).
- Falabella: sin cifra confiable para el producto base → sigue sin cifra confiable para el producto base (**sin cambio**); el bundle de 2 mandos + cargador repite exactamente el mismo precio del 09-21 ($4.999.800), sin cambio.
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Retailers nuevos: **Ktronix** aparece por primera vez en el radar (mismo producto que Alkosto, código 711719595700), pero sin precio ni disponibilidad — no se cuenta como novedad de precio real, solo se agrega al radar de retailers a seguir. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer (Éxito y el bundle de Falabella repiten exactamente los mismos valores previos). Ningún retailer alcanza la meta del usuario (≤$3.700.000 o ≥20% dcto.) con disponibilidad real y datos confiables. No hubo novedad concreta y confirmada (el retailer nuevo Ktronix no trae precio, y la promoción de Sony no trae cifra). Se obtuvo al menos un dato confiable hoy (Éxito, Alkosto y Falabella-bundle confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer" (solo Enjoy VideoGames acumula 3 días sin dato, no todos los retailers). **No se cumplió ninguna condición de notificación.**

---

## 2026-09-24

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y `site:` dirigidas por retailer (Sony Store, Éxito, Alkosto, Falabella, Mercado Libre, Enjoy VideoGames), más una búsqueda general de ofertas del mes.

**Nota de calidad de datos:** Enjoy VideoGames devolvió hoy una cuarta cifra distinta y aún más alejada de las anteriores: **$1.990.000 COP**, muy por debajo de cualquier valor visto antes para este producto ($3.699.000 el 09-16/09-17/09-19, y el rango contradictorio $3.699.000/$3.180.000–$2.960.000 del 09-21 y 09-22, y sin resultado propio el 09-23). Esta cifra es implausible para el producto rastreado (es más baja que casi cualquier oferta vista de cualquier retailer) y probablemente corresponde a un resumen mal formado o a un producto/accesorio distinto mezclado en el snippet. Siguiendo la regla de nunca inventar ni reportar cifras no confiables, **se descarta también hoy** — cuarto día consecutivo (09-21 a 09-24) sin poder confirmar un precio fiable y consistente para Enjoy VideoGames.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | Sin precio confirmado hoy (~$4.199.000 como última referencia, sin reconfirmar) | El snippet solo confirma que la página del producto existe (`store.sony.com.co/ps5-pro-hw-2tb/p`); no trae precio ni descuento concreto. **No se registra cifra nueva — no inventada.** | WebSearch (WebFetch directo bloqueado) |
| Éxito | Sin precio confirmado hoy | Los snippets de hoy muestran las mismas páginas de producto ya conocidas (`consola-ps5-pro-2-tb-blanco-3192604/p`, `playstation-5-pro-2tb-104366926-mp`, `consola-playstation-5-pro-2tb-digital-2-mandos-cargador-dobe-103972507-mp`), pero ninguna trae el precio en el snippet. No se puede confirmar si el último precio conocido ($4.299.900, reconfirmado el 2026-09-22) sigue vigente. **No se registra cifra nueva — no inventada.** | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Snippet confirma nuevamente que el producto (código 711719595700) está agotado / sin unidades disponibles para la venta en la tienda online. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Falabella | **$4.999.800** (antes $5.599.800, ~10,7% dcto.) — bundle "2 Mandos + Cargador Dobe" (SKU 139040647), no el producto base | Misma cifra ya registrada el 09-21 y 09-23 para este bundle; **sin cambio**. Los productos base (73119842, 145535455, 139051769, 137865821) y la vitrina "PS5 Pro en Aniversario Falabella" siguen sin mostrar precio en los snippets. | WebSearch |
| Enjoy VideoGames | **Sin cifra confiable hoy** (ver nota de calidad de datos arriba) | Cuarto día consecutivo con cifras contradictorias/implausibles para este retailer. Se descarta reportar la cifra de hoy ($1.990.000, considerada no fiable). | WebSearch (no confiable — descartado) |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (`MCO43294311`, `MCO41975964`, `MCO-2711196168`, `MCOU2945331578`, `MCO43432698`) mencionan "cuotas sin interés" y envío gratis, igual que en entradas anteriores, pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Ktronix | Sin precio confirmado hoy | No se repitió una búsqueda dirigida a Ktronix hoy; se mantiene el estado del 09-23 (agotado, sin precio) como última referencia, sin reconfirmar. | — (sin búsqueda dirigida hoy) |

**Comparación con la entrada anterior (2026-09-23, retailer por retailer):**
- Sony Store Colombia: sin confirmar → sin confirmar hoy tampoco (**sin cambio**).
- Éxito: $4.299.900 (confirmado 09-22) → sin poder reconfirmarse hoy (**sin cambio**, sin evidencia de variación).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Falabella (bundle): $4.999.800 → $4.999.800 (**sin cambio**).
- Enjoy VideoGames: no confiable (3er día, 09-23) → sigue no confiable, con una cuarta cifra distinta e implausible (**sin cambio real**, dato perdido cuarto día).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Ktronix: agotado (09-23) → sin reconfirmar hoy (se mantiene como referencia).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% confiable en ningún retailer (Falabella-bundle repite exactamente el mismo valor). Ningún retailer alcanza la meta del usuario (≤$3.700.000 COP o ≥20% dcto.) con disponibilidad real y datos confiables — la cifra de Enjoy VideoGames que técnicamente cumpliría la meta ($1.990.000) se descarta explícitamente por no ser fiable. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo y confirmado. Se obtuvo al menos un dato confiable hoy (Alkosto y Falabella-bundle confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer" (solo Enjoy VideoGames acumula 4 días sin dato fiable, no todos los retailers). **No se cumplió ninguna condición de notificación.**

---

## 2026-09-25

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y `site:` dirigidas por retailer (Sony Store, Éxito, Alkosto, Falabella, Mercado Libre, Enjoy VideoGames, Ktronix).

**Nota de calidad de datos:** un resumen de WebSearch general recalculó el precio de Sony Store a partir de la financiación ya conocida (24 cuotas de $183.325/mes ≈ $4.399.800 en total), cifra distinta a la referencia habitual de ~$4.199.000 registrada en entradas anteriores. Esta es una recombinación aritmética del propio resumen de búsqueda, no una cifra nueva confirmada en un snippet de la página de producto — la financiación en sí (24x$183.325) es la misma que ya se venía registrando sin cambios desde el 2026-09-16. **No se trata como cambio de precio real**, se mantiene como referencia no reconfirmada. Además, un resumen mencionó "Pepe Ganga" como posible retailer adicional junto con Alkosto y Sony Store a ~$4.199.000, pero sin snippet propio de Pepe Ganga que lo confirme — se anota para seguimiento, sin registrar cifra. Enjoy VideoGames sigue sin cifra confiable y consistente (quinto día consecutivo, 09-21 a 09-25); el único valor que apareció hoy ($3.730.000) corresponde al bundle con unidad de disco (producto distinto), como ya se había identificado en entradas previas.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | Sin precio confirmado hoy (~$4.199.000 como última referencia, sin reconfirmar) | El snippet solo confirma que la página del producto existe (`store.sony.com.co/ps5-pro-hw-2tb/p`); no trae precio de contado ni descuento concreto. Ver nota de calidad de datos sobre la recombinación aritmética de $4.399.800 (no usada). **No se registra cifra nueva — no inventada.** | WebSearch (WebFetch directo bloqueado) |
| Éxito | **$4.299.900** | 12 cuotas sin interés. Página: `exito.com/consola-ps5-pro-2-tb-blanco-3192604/p`. **Sin cambio** respecto a la última cifra confirmada (reconfirmada el 2026-09-22). | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Snippet confirma nuevamente que el producto (código 711719595700) no cuenta con unidades disponibles para la venta en la tienda online. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Falabella | **$4.999.800** (antes $5.599.800, ~10,7% dcto.) — bundle "2 Mandos + Cargador Dobe" (SKU 139040647), no el producto base | Misma cifra ya registrada el 09-21, 09-23 y 09-24 para este bundle; **sin cambio**. Los productos base (73119842, 145535455, 139051769) y la vitrina "PS5 Pro en Aniversario Falabella" siguen sin mostrar precio en los snippets. | WebSearch |
| Enjoy VideoGames | **Sin cifra confiable hoy** (ver nota de calidad de datos arriba) | Quinto día consecutivo sin poder confirmar un precio fiable y consistente para el producto base (Digital 2TB); el único valor visto hoy ($3.730.000) corresponde al bundle con unidad de disco. | WebSearch (no confiable — descartado) |
| Mercado Libre | Sin cifra confirmada en snippets | Listado activo (`MCO43294311` — "PlayStation PS5 PRO HW 2TB Digital Standard color Blanco") menciona "cuotas sin interés", igual que en entradas anteriores, pero el precio no aparece en el snippet. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Ktronix | Sin precio confirmado hoy | No se repitió una búsqueda dirigida exitosa a Ktronix hoy (el snippet solo confirma que la página de producto existe, sin precio); se mantiene el estado del 09-23 (agotado, sin precio) como última referencia, sin reconfirmar. | WebSearch |

**Comparación con la entrada anterior (2026-09-24, retailer por retailer):**
- Sony Store Colombia: sin confirmar → sin confirmar hoy tampoco (**sin cambio**); ver nota sobre la recombinación aritmética descartada.
- Éxito: sin confirmar el 09-24 → hoy se reconfirma $4.299.900, mismo valor que el 09-22 (**sin cambio real**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Falabella (bundle): $4.999.800 → $4.999.800 (**sin cambio**).
- Enjoy VideoGames: no confiable (4to día, 09-24) → sigue no confiable (5to día, 09-25) (**sin cambio real**, dato perdido).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Ktronix: sin reconfirmar (09-24) → sin reconfirmar hoy tampoco (se mantiene como referencia).
- Retailers nuevos: se mencionó "Pepe Ganga" en un resumen general sin snippet propio que lo confirme — no se cuenta como retailer nuevo confirmado, solo se anota para seguimiento en próximas entradas. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% confiable en ningún retailer (Éxito y Falabella-bundle repiten exactamente los mismos valores previos). Ningún retailer alcanza la meta del usuario (≤$3.700.000 COP o ≥20% dcto.) con disponibilidad real y datos confiables. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo y confirmado (la mención de "Pepe Ganga" no se pudo confirmar con snippet propio). Se obtuvo al menos un dato confiable hoy (Éxito, Alkosto y Falabella-bundle confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer" (solo Enjoy VideoGames acumula 5 días sin dato fiable, no todos los retailers). **No se cumplió ninguna condición de notificación.**

---

## 2026-09-26

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y `site:` dirigidas por retailer (Sony Store, Éxito, Alkosto, Falabella, Mercado Libre, Enjoy VideoGames, Ktronix), más una búsqueda dirigida a "Pepe Ganga" para dar seguimiento a la mención del día anterior.

**Nota de calidad de datos:** Enjoy VideoGames volvió a mostrar hoy la cifra **$3.699.000** (agotado) de forma consistente en el resumen general, sin contradicción con otras cifras en esta ocasión — termina así la racha de 5 días (09-21 a 09-25) sin dato fiable para este retailer. Es la misma cifra ya vista los días 09-16, 09-17 y 09-19, por lo que **no se trata como cambio de precio**, solo como reconfirmación tras la interrupción. Pepe Ganga aparece de nuevo en los resultados (página de producto propia, `pepeganga.com/consola-ps5-pro-hw-2tb-playstation-711719595700/p`), pero de nuevo **sin precio ni disponibilidad confirmados en el snippet** — se mantiene como retailer en seguimiento, no como novedad confirmada.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | Sin precio confirmado hoy (~$4.199.000 como última referencia, sin reconfirmar) | El snippet solo confirma que la página del producto existe (`store.sony.com.co/ps5-pro-hw-2tb/p`); no trae precio de contado ni descuento concreto. **No se registra cifra nueva — no inventada.** | WebSearch (WebFetch directo bloqueado) |
| Éxito | Sin precio confirmado hoy (~$4.299.900 como última referencia, reconfirmada el 2026-09-25) | Los snippets de hoy muestran las páginas ya conocidas (`exito.com/t/ps5-pro`, `playstation-5-pro-2tb-104366926-mp`), pero ninguna trae el precio en el snippet. **No se registra cifra nueva — no inventada.** | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | El resumen de WebSearch confirma nuevamente "currently out of stock and not available for purchase" para el mismo código de producto (711719595700). **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Falabella | **$4.999.800** (antes $5.599.800, ~10,7% dcto.) — bundle "2 Mandos + Cargador Dobe" (SKU 139040647), no el producto base | Misma cifra ya registrada el 09-21, 09-23, 09-24 y 09-25 para este bundle; **sin cambio**. Los productos base (73119842, 139051769, 145535455) y la vitrina "PS5 Pro en Aniversario Falabella" siguen sin mostrar precio en los snippets. | WebSearch |
| Enjoy VideoGames | **$3.699.000** (**producto agotado / sin stock**) | Cifra reconfirmada de forma consistente hoy (ver nota de calidad de datos). Idéntica al último valor confiable conocido (2026-09-19); sigue sin disponibilidad real, por lo que **no** se trata como oportunidad de compra ni como meta alcanzada, igual que en entradas anteriores donde esta cifra ya se había visto. | WebSearch (`enjoyvideogames.com.co/product/sony-playstation-5-pro-2tb/`) |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (`MCO43294311`, `MCO41975964`, `MCO-2711196168`, `MCOU2945331578`) mencionan "cuotas sin interés", igual que en entradas anteriores, pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Ktronix | Sin precio confirmado hoy | El snippet solo confirma que la página de producto existe (`ktronix.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700`), sin precio. Se mantiene el estado del 09-23 (agotado, sin precio) como última referencia, sin reconfirmar. | WebSearch |
| Pepe Ganga | Sin precio confirmado hoy | Segundo día que aparece en el radar (mencionado ayer sin snippet propio; hoy se confirma su propia página de producto `pepeganga.com/consola-ps5-pro-hw-2tb-playstation-711719595700/p`, incluyendo una variante `idsku=291443`), pero **sin precio ni disponibilidad en el snippet**. Se agrega al radar de retailers a seguir; **no se cuenta como novedad de precio real** por no traer cifra. | WebSearch |

**Comparación con la entrada anterior (2026-09-25, retailer por retailer):**
- Sony Store Colombia: sin confirmar → sin confirmar hoy tampoco (**sin cambio**).
- Éxito: $4.299.900 (reconfirmado 09-25) → sin poder reconfirmarse hoy (**sin cambio**, sin evidencia de variación).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Falabella (bundle): $4.999.800 → $4.999.800 (**sin cambio**).
- Enjoy VideoGames: no confiable (5to día, 09-25) → hoy se reconfirma $3.699.000 (agotado), mismo valor que la última cifra fiable conocida del 09-19 (**sin cambio real**, termina la racha de datos no fiables).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Ktronix: sin reconfirmar (09-25) → sin reconfirmar hoy tampoco (se mantiene como referencia).
- Retailers nuevos: **Pepe Ganga** aparece por segunda vez en los resultados, ahora con página de producto propia confirmada, pero sigue sin precio — no se cuenta como novedad de precio real, solo se refuerza su presencia en el radar. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer (todas las cifras confirmadas hoy repiten valores ya conocidos: Falabella-bundle y Enjoy VideoGames). Ningún retailer alcanza la meta del usuario (≤$3.700.000 COP o ≥20% dcto.) con disponibilidad real: Enjoy VideoGames iguala el umbral de precio ($3.699.000) pero sigue agotado, exactamente igual que en las entradas del 09-16, 09-17 y 09-19 — no es una oportunidad de compra nueva ni real. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo y confirmado (Pepe Ganga sigue sin precio ni disponibilidad, igual que Ktronix). Se obtuvo al menos un dato confiable hoy de varios retailers, por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

---

## 2026-09-27

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y dirigidas por retailer (Sony Store, Éxito, Alkosto, Falabella, Enjoy VideoGames, Mercado Libre, Ktronix, Pepe Ganga).

**Nota de calidad de datos:** Enjoy VideoGames volvió a mostrar hoy una cifra distinta y no consistente con su última cifra confiable ($3.699.000, reconfirmada el 09-26): el resumen de hoy menciona un **rango de $1.620.000 a $1.990.000 COP**, muy por debajo de cualquier valor razonable visto antes para este producto y sin snippet propio verificable que lo respalde línea por línea (patrón ya visto el 09-24 con la cifra aislada de $1.990.000, entonces descartada por implausible). Siguiendo la regla de nunca inventar ni reportar cifras no confiables, **se descarta también hoy** esta cifra — se mantiene $3.699.000 (agotado) como última referencia confiable de Enjoy VideoGames, sin reconfirmar hoy. Pepe Ganga sigue sin precio ni disponibilidad confirmados en snippet. No se encontró ninguna mención nueva de retailers adicionales a los ya conocidos.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | Sin precio confirmado hoy (~$4.199.000 como última referencia, sin reconfirmar) | El resumen general repite la cifra habitual de ~$4.199.000 atribuida a "plataformas de e-commerce incluyendo Sony Store", pero sin snippet propio de la página de producto que la confirme hoy. **No se registra cifra nueva — no inventada.** | WebSearch (WebFetch directo bloqueado) |
| Éxito | Sin precio confirmado hoy (~$4.299.900 como última referencia, reconfirmada el 2026-09-25) | Los snippets de hoy muestran las mismas páginas de producto ya conocidas (`consola-ps5-pro-2-tb-blanco-3192604/p`, `playstation-5-pro-2tb-104366926-mp`, `consola-playstation-5-pro-2tb-digital-2-mandos-cargador-dobe-103972507-mp`), pero ninguna trae el precio en el snippet. **No se registra cifra nueva — no inventada.** | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | El resumen de WebSearch confirma nuevamente que el producto (código 711719595700) está agotado y no disponible para compra. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Falabella | **$4.999.800** (antes $5.599.800, ~10,7% dcto.) — bundle "2 Mandos + Cargador Dobe" (SKU 139040647), no el producto base | Misma cifra ya registrada desde el 09-21 para este bundle; **sin cambio**. Los productos base (73119842, 139051769, 145535455) y las vitrinas "PS5 Pro en Aniversario Falabella" y "Playstation 5 Pro" siguen sin mostrar precio en los snippets. | WebSearch |
| Enjoy VideoGames | **Sin cifra confiable hoy** (ver nota de calidad de datos arriba) | Cifra de hoy ($1.620.000–$1.990.000) descartada por implausible; se mantiene $3.699.000 (agotado) como última referencia confiable del 09-26, sin reconfirmar hoy. | WebSearch (no confiable — descartado) |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (`MCO43294311`, `MCO41975964`, `MCO-2711196168`) mencionan "cuotas sin interés", igual que en entradas anteriores, pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Ktronix | Sin precio confirmado hoy | El snippet solo confirma que la página de producto existe (`ktronix.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700`), sin precio. Se mantiene el estado del 09-23 (agotado, sin precio) como última referencia, sin reconfirmar. | WebSearch |
| Pepe Ganga | Sin precio confirmado hoy | El snippet de hoy solo repite las páginas de producto ya conocidas (`pepeganga.com/consola-ps5-pro-hw-2tb-playstation-711719595700/p`, variante `idsku=291443`) y una nota histórica sobre el periodo de preventa de 2024, sin precio actual. **Sin cambio** respecto a la entrada anterior. | WebSearch |

**Comparación con la entrada anterior (2026-09-26, retailer por retailer):**
- Sony Store Colombia: sin confirmar → sin confirmar hoy tampoco (**sin cambio**).
- Éxito: sin confirmar → sin confirmar hoy tampoco (**sin cambio**, sin evidencia de variación desde $4.299.900).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Falabella (bundle): $4.999.800 → $4.999.800 (**sin cambio**).
- Enjoy VideoGames: $3.699.000 (agotado, reconfirmado 09-26) → hoy solo aparece una cifra implausible descartada ($1.620.000–$1.990.000); no se puede reconfirmar ni refutar el valor de referencia (**sin cambio real**, dato no confiable hoy).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Ktronix: sin reconfirmar → sin reconfirmar hoy tampoco (se mantiene como referencia).
- Pepe Ganga: sin precio (09-26) → sin precio hoy tampoco (**sin cambio**).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% confiable en ningún retailer (la única cifra "nueva", la de Enjoy VideoGames, se descarta por implausible y no comparable con su última referencia confiable). Ningún retailer alcanza la meta del usuario (≤$3.700.000 COP o ≥20% dcto.) con disponibilidad real y datos confiables hoy. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo y confirmado. Se obtuvo al menos un dato confiable hoy (Alkosto y Falabella-bundle confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

---

## 2026-09-28

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p`, `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700`, `www.falabella.com.co` y `enjoyvideogames.com.co` → todos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y `site:` dirigidas por retailer (Éxito, Alkosto, Falabella, Sony Store, Mercado Libre, Enjoy VideoGames), más una búsqueda general de ofertas/cupones del mes.

**Nota de calidad de datos:** Enjoy VideoGames reapareció hoy con la cifra ya conocida **$3.699.000** (agotado), consistente con la última referencia confiable (2026-09-26). Apareció una mención nueva a "Colombian UP" como posible retailer adicional en un resumen general de ofertas, pero sin snippet propio con precio que lo confirme — se anota para seguimiento, sin registrar cifra, igual que se hizo en su momento con Pepe Ganga y Ktronix.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | Sin precio confirmado hoy (~$4.199.000 como última referencia, sin reconfirmar) | El resumen repite la financiación ya conocida (24 cuotas de $183.325/mes, oferta 1–30 sep 2026), sin precio de contado nuevo en snippet. **No se registra cifra nueva — no inventada.** | WebSearch (WebFetch directo bloqueado) |
| Éxito | **$4.299.900** | 12 cuotas sin interés. Página: `exito.com/consola-ps5-pro-2-tb-blanco-3192604/p`. **Sin cambio** respecto a la última cifra confirmada (reconfirmada el 2026-09-25). | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | El resumen de WebSearch confirma nuevamente que el producto (código 711719595700) no cuenta con unidades disponibles para la venta en la tienda online. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Falabella | **$4.999.800** (antes $5.599.800, ~10,7% dcto.) — bundle "2 Mandos + Cargador Dobe" (SKU 139040647), no el producto base | Misma cifra ya registrada desde el 09-21 para este bundle; **sin cambio**. Los productos base (73119842, 139051769, 145535455) siguen sin mostrar precio en los snippets. | WebSearch |
| Enjoy VideoGames | **$3.699.000** (**producto agotado / sin stock**) | Cifra reconfirmada hoy, idéntica al último valor confiable conocido (2026-09-26). Sigue sin disponibilidad real, por lo que **no** se trata como oportunidad de compra ni meta alcanzada. | WebSearch (`enjoyvideogames.com.co/product/sony-playstation-5-pro-2tb/`) |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (`MCO43294311`, `MCO41975964`) mencionan "cuotas sin interés", igual que en entradas anteriores, pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Ktronix | Sin precio confirmado hoy | No se repitió búsqueda dirigida hoy; se mantiene el estado del 09-23 (agotado, sin precio) como última referencia, sin reconfirmar. | — (sin búsqueda dirigida hoy) |
| Pepe Ganga | Sin precio confirmado hoy | No se repitió búsqueda dirigida hoy; se mantiene el estado del 09-27 (sin precio) como última referencia, sin reconfirmar. | — (sin búsqueda dirigida hoy) |
| Colombian UP | Sin precio confirmado | Mencionado por primera vez en un resumen general de ofertas del mes como posible vendedor de la consola, pero sin snippet propio con precio ni disponibilidad. Se agrega al radar de retailers a seguir; **no se cuenta como novedad de precio real**. | WebSearch |

**Comparación con la entrada anterior (2026-09-27, retailer por retailer):**
- Sony Store Colombia: sin confirmar → sin confirmar hoy tampoco (**sin cambio**).
- Éxito: sin confirmar (09-27) → hoy se reconfirma $4.299.900, mismo valor que el 09-25 (**sin cambio real**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Falabella (bundle): $4.999.800 → $4.999.800 (**sin cambio**).
- Enjoy VideoGames: no confiable (09-27, cifra implausible descartada) → hoy se reconfirma $3.699.000 (agotado), mismo valor que el 09-26 (**sin cambio real**).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Ktronix: sin reconfirmar → sin reconfirmar hoy tampoco (se mantiene como referencia).
- Pepe Ganga: sin precio → sin precio hoy tampoco (**sin cambio**).
- Retailers nuevos: **Colombian UP** mencionado por primera vez, pero sin precio ni disponibilidad confirmados — no se cuenta como novedad real. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer (todas las cifras confirmadas hoy repiten valores ya conocidos: Éxito, Falabella-bundle y Enjoy VideoGames). Ningún retailer alcanza la meta del usuario (≤$3.700.000 COP o ≥20% dcto.) con disponibilidad real: Enjoy VideoGames iguala el umbral de precio pero sigue agotado, igual que en entradas anteriores — no es una oportunidad de compra nueva ni real. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo y confirmado (Colombian UP se menciona pero sin precio ni disponibilidad, igual que Ktronix y Pepe Ganga en su momento). Se obtuvo al menos un dato confiable hoy (Éxito, Alkosto, Falabella-bundle y Enjoy VideoGames confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

---

## 2026-09-29

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y dirigidas por retailer (Sony Store, Éxito, Alkosto, Falabella, Enjoy VideoGames, Mercado Libre, Ktronix, Pepe Ganga, Colombian UP).

**Nota de calidad de datos:** ningún retailer nuevo apareció hoy más allá de los ya conocidos (Colombian UP, mencionado desde el 09-28, sigue sin precio confirmado). Ktronix confirmó hoy explícitamente estado "agotado / sin stock" (antes solo se mantenía como referencia sin reconfirmar desde el 09-23). No se detectaron cifras contradictorias ni implausibles hoy.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | Sin precio confirmado hoy (~$4.199.000 como última referencia, sin reconfirmar) | Un resumen general repite la cifra habitual de ~$4.199.000 atribuida a "principales e-commerce de Colombia", y la financiación ya conocida (24 cuotas de $183.325/mes), sin snippet propio de la página de producto que lo confirme hoy. **No se registra cifra nueva — no inventada.** | WebSearch (WebFetch directo bloqueado) |
| Éxito | Sin precio confirmado hoy (~$4.299.900 como última referencia, reconfirmada el 2026-09-28) | Los snippets de hoy muestran las mismas páginas de producto ya conocidas (`exito.com/consola-ps5-pro-2-tb-blanco-3192604/p`, `playstation-5-pro-2tb-104366926-mp`), pero ninguna trae el precio en el snippet. **No se registra cifra nueva — no inventada.** | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | El resumen de WebSearch confirma nuevamente que el producto (código 711719595700) no cuenta con unidades disponibles para la venta en la tienda online. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Falabella | Sin precio confiable confirmado hoy (bundle "2 Mandos + Cargador Dobe" con última cifra conocida de $4.999.800, sin reconfirmar hoy) | Los snippets de hoy listan las mismas páginas ya conocidas (producto base 73119842, 139051769, 145535455, vitrina "PS5 Pro en Aniversario Falabella"), pero ninguna trae el precio en el snippet. **No se registra cifra nueva — no inventada.** | WebSearch |
| Enjoy VideoGames | **$3.699.000** (**producto agotado / sin stock**) | Cifra reconfirmada hoy, idéntica al último valor confiable conocido (2026-09-28). Sigue sin disponibilidad real, por lo que **no** se trata como oportunidad de compra ni meta alcanzada. | WebSearch (`enjoyvideogames.com.co/product/sony-playstation-5-pro-2tb/`) |
| Mercado Libre | Sin cifra confirmada en snippets | Listados activos (`MCO43294311`, `MCO41975964`) mencionan "cuotas sin interés", igual que en entradas anteriores, pero el precio no aparece en los snippets. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Ktronix | Sin precio (**producto agotado / sin stock**, confirmado hoy) | El resumen de WebSearch confirma explícitamente hoy que el producto (código 711719595700) no cuenta con unidades disponibles, igual que en Alkosto y Alkomprar (retailers relacionados). Coincide con el estado de referencia del 09-23, ahora reconfirmado directamente. | WebSearch |
| Pepe Ganga | Sin precio confirmado hoy | No se repitió búsqueda con snippet nuevo; se mantiene el estado del 09-27 (sin precio) como última referencia, sin reconfirmar. | WebSearch |
| Colombian UP | Sin precio confirmado | Segundo día que aparece en el radar (mencionado el 09-28), con página de producto propia confirmada (`colombianup.com/tienda/consolas/consola-playstation-5-digital-pro-2tb/`), pero **sin precio ni disponibilidad en el snippet**. Se mantiene en el radar de retailers a seguir; **no se cuenta como novedad de precio real**. | WebSearch |

**Comparación con la entrada anterior (2026-09-28, retailer por retailer):**
- Sony Store Colombia: sin confirmar → sin confirmar hoy tampoco (**sin cambio**).
- Éxito: $4.299.900 (reconfirmado 09-28) → sin poder reconfirmarse hoy (**sin cambio**, sin evidencia de variación).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Falabella (bundle): $4.999.800 → sin reconfirmar hoy (**sin cambio**, sin evidencia de variación).
- Enjoy VideoGames: $3.699.000 (agotado, reconfirmado 09-28) → $3.699.000 (agotado, reconfirmado hoy) (**sin cambio**).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Ktronix: sin reconfirmar desde el 09-23 → hoy se reconfirma explícitamente "agotado/sin stock" (**sin cambio real**, solo se refuerza el dato de referencia).
- Pepe Ganga: sin precio → sin precio hoy tampoco (**sin cambio**).
- Colombian UP: mencionado por primera vez (09-28) → sigue en el radar hoy, aún sin precio (**sin cambio**).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer (las únicas cifras confirmadas hoy, Enjoy VideoGames y el estado de Alkosto/Ktronix, repiten valores ya conocidos). Ningún retailer alcanza la meta del usuario (≤$3.700.000 COP o ≥20% dcto.) con disponibilidad real: Enjoy VideoGames iguala el umbral de precio pero sigue agotado, igual que en entradas anteriores. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo (Colombian UP sigue sin precio ni disponibilidad, igual que Pepe Ganga). Se obtuvo al menos un dato confiable hoy (Alkosto, Ktronix y Enjoy VideoGames confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

---

## 2026-09-30

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y `site:` dirigidas por retailer (Sony Store, Éxito, Alkosto, Falabella, Enjoy VideoGames).

**Nota de calidad de datos:** ningún retailer nuevo apareció hoy. No se hicieron búsquedas dirigidas hoy a Ktronix, Pepe Ganga ni Colombian UP (se mantienen sus últimas referencias sin reconfirmar). No se detectaron cifras contradictorias ni implausibles hoy.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Sony Store Colombia | Sin precio confirmado hoy (~$4.199.000 como última referencia, sin reconfirmar) | El snippet solo confirma que la página del producto existe (`store.sony.com.co/ps5-pro-hw-2tb/p`); no trae precio ni descuento concreto en el resumen. **No se registra cifra nueva — no inventada.** | WebSearch (WebFetch directo bloqueado) |
| Éxito | Sin precio confirmado hoy (~$4.299.900 como última referencia, reconfirmada el 2026-09-28) | Los snippets de hoy muestran las mismas páginas ya conocidas (`exito.com/t/ps5-pro`, `consola-ps5-pro-2-tb-blanco-3192604/p`, `playstation-5-pro-2tb-104366926-mp`), pero ninguna trae el precio en el snippet. **No se registra cifra nueva — no inventada.** | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | El resumen de WebSearch confirma nuevamente que el producto (código 711719595700) no cuenta con unidades disponibles para la venta en la tienda online. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Falabella | Sin precio confiable confirmado hoy (bundle "2 Mandos + Cargador Dobe", última cifra conocida $4.999.800, sin reconfirmar hoy) | Los snippets de hoy listan las mismas páginas ya conocidas (bundle 139040647, producto base 73119842 y 145535455, vitrinas "PS5 Pro en Aniversario Falabella"), pero ninguna trae el precio en el snippet. **No se registra cifra nueva — no inventada.** | WebSearch |
| Enjoy VideoGames | **$3.699.000** (**producto agotado / sin stock**) | Cifra reconfirmada hoy, idéntica al último valor confiable conocido (2026-09-29). Sigue sin disponibilidad real, por lo que **no** se trata como oportunidad de compra ni meta alcanzada. | WebSearch (`enjoyvideogames.com.co/product/sony-playstation-5-pro-2tb/`) |
| Mercado Libre | Sin cifra confirmada en snippets | Listado activo (`MCO43294311` — "PlayStation PS5 PRO HW 2TB Digital Standard color Blanco") menciona "cuotas sin interés", igual que en entradas anteriores, pero el precio no aparece en el snippet. **Sin cambio** respecto a la entrada anterior. | WebSearch |
| Ktronix | Sin reconfirmar hoy | No se repitió búsqueda dirigida hoy; se mantiene el estado del 2026-09-29 (agotado/sin stock, confirmado explícitamente) como última referencia. | — (sin búsqueda dirigida hoy) |
| Pepe Ganga | Sin reconfirmar hoy | No se repitió búsqueda dirigida hoy; se mantiene el estado del 2026-09-27 (sin precio) como última referencia. | — (sin búsqueda dirigida hoy) |
| Colombian UP | Sin reconfirmar hoy | No se repitió búsqueda dirigida hoy; se mantiene el estado del 2026-09-29 (sin precio) como última referencia. | — (sin búsqueda dirigida hoy) |

**Comparación con la entrada anterior (2026-09-29, retailer por retailer):**
- Sony Store Colombia: sin confirmar → sin confirmar hoy tampoco (**sin cambio**).
- Éxito: sin confirmar (09-29) → sin confirmar hoy tampoco (**sin cambio**, sin evidencia de variación desde $4.299.900).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Falabella (bundle): sin reconfirmar (09-29) → sin reconfirmar hoy tampoco (**sin cambio**, sin evidencia de variación desde $4.999.800).
- Enjoy VideoGames: $3.699.000 (agotado, reconfirmado 09-29) → $3.699.000 (agotado, reconfirmado hoy) (**sin cambio**).
- Mercado Libre: sin cifra → sin cifra (**sin cambio**).
- Ktronix: agotado (confirmado 09-29) → sin reconfirmar hoy (se mantiene como referencia).
- Pepe Ganga: sin precio → sin reconfirmar hoy (se mantiene como referencia).
- Colombian UP: sin precio (09-29) → sin reconfirmar hoy (se mantiene como referencia).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer (la única cifra confirmada hoy, Enjoy VideoGames, repite exactamente el valor ya conocido). Ningún retailer alcanza la meta del usuario (≤$3.700.000 COP o ≥20% dcto.) con disponibilidad real: Enjoy VideoGames iguala el umbral de precio pero sigue agotado, igual que en entradas anteriores. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo. Se obtuvo al menos un dato confiable hoy (Alkosto y Enjoy VideoGames confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

---

## 2026-10-02

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p`, `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700`, `www.mercadolibre.com.co/.../MCO43294311` y `colombianup.com/.../consola-playstation-5-digital-pro-2tb/` → todos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y dirigidas por retailer (Sony Store, Éxito, Alkosto, Falabella, Mercado Libre, Enjoy VideoGames, Ktronix, Pepe Ganga, Colombian UP).

**Nota de calidad de datos:** la cifra de Mercado Libre ($3.589.900, 28% dcto.) se reconfirmó de forma **idéntica** en 3 consultas WebSearch independientes (mismo precio original $5.014.143, mismas cuotas de $1.196.633 x3, misma calificación 5/5 con 56 reseñas), lo que da buena confianza de que es una cifra real indexada hoy y no una invención del resumen — aunque no se pudo verificar con WebFetch directo (bloqueado). La cifra de Éxito ($8.397.687 → $4.798.678) es **implausible** (muy por encima de cualquier referencia histórica de esta consola) y **se descarta explícitamente — no se registra como válida**, probablemente una mezcla de productos/bundle distinto en el snippet. Sony Store y Pepe Ganga aparecen con precio confirmado por primera vez en varios días.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Mercado Libre | **$3.589.900** (precio de lista $5.014.143, **28% dcto.**) | Producto exacto: "PlayStation PS5 PRO HW 2TB Digital Standard color Blanco" (MCO43294311). 3 cuotas de $1.196.633 sin interés, envío gratis, 5/5 con 56 reseñas — parece disponible para compra (no agotado). **Cumple AMBAS condiciones de la meta del usuario** (≤$3.700.000 y ≥20% dcto.). | WebSearch (WebFetch directo bloqueado) |
| Sony Store Colombia | $4.399.804 (precio de lista $4.599.900, ~4,3% dcto.) | Confirmado **en stock (10 unidades)**. Primera reconfirmación de precio en varios días (antes solo había referencia sin confirmar de ~$4.199.000). No alcanza la meta. | WebSearch (WebFetch directo bloqueado) |
| Falabella | $4.139.900 (precio de lista $4.299.900, 17% dcto.) — producto base 73119842/145535456, distinto del bundle "2 Mandos + Cargador Dobe" seguido antes | Primera reconfirmación de precio del producto base en varios días. No alcanza la meta (17% < 20%, y precio > $3.700.000). | WebSearch (WebFetch directo bloqueado) |
| Éxito | **Cifra descartada por implausible** ($8.397.687 → $4.798.678 no es creíble; ref. histórica ~$4.299.900 sin reconfirmar hoy) | El snippet mezcla cifras que no corresponden a este producto. **No se registra cifra nueva — no inventada.** | WebSearch (descartado) |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Confirma nuevamente que el producto (código 711719595700) no tiene unidades disponibles. **Sin cambio.** | WebSearch |
| Enjoy VideoGames | $3.699.000 (**producto agotado / sin stock**) | Cifra reconfirmada hoy, idéntica a la última conocida. Sigue sin disponibilidad real — **no** se trata como oportunidad de compra. | WebSearch |
| Pepe Ganga | $4.199.900 (**pre-order**) | Primera cifra confirmada para este retailer (antes "sin precio"/sin reconfirmar). No alcanza la meta. | WebSearch |
| Ktronix | Sin precio (**producto agotado / sin stock**) | Confirmado nuevamente agotado. **Sin cambio.** | WebSearch |
| Colombian UP | $3.999.000 (precio de lista $4.500.000, ~11% dcto.) | Primera cifra confirmada en varios días (antes "sin precio"). No alcanza la meta (11% < 20%, precio > $3.700.000). | WebSearch |

**Comparación con la entrada anterior (2026-09-30, retailer por retailer):**
- Mercado Libre: sin cifra confirmada → **$3.589.900 (28% dcto.) — ¡retailer alcanza la meta del usuario por primera vez!**
- Sony Store Colombia: sin confirmar (~$4.199.000 ref.) → $4.399.804 confirmado, en stock (**reconfirmación, no comparable como "bajada" por falta de cifra previa confiable**).
- Falabella: sin reconfirmar (bundle $4.999.800) → $4.139.900 confirmado para el producto base, listing distinto al bundle seguido antes (**no comparable directamente, nuevo listing identificado**).
- Éxito: sin confirmar → cifra de hoy descartada por implausible (**sin cambio real registrable**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Enjoy VideoGames: $3.699.000 (agotado) → $3.699.000 (agotado) (**sin cambio**).
- Pepe Ganga: sin reconfirmar → $4.199.900 confirmado (pre-order) (**reconfirmación, nueva cifra**).
- Ktronix: sin reconfirmar → agotado confirmado (**sin cambio**).
- Colombian UP: sin reconfirmar → $3.999.000 confirmado (11% dcto.) (**reconfirmación, nueva cifra**).
- Retailers nuevos: ninguno (todos ya se seguían). Retailers desaparecidos: ninguno.

**Conclusión de hoy:** **¡META ALCANZADA!** Mercado Libre (listing MCO43294311, "PlayStation PS5 PRO HW 2TB Digital Standard color Blanco") ofrece hoy la PS5 Pro Digital 2TB a **$3.589.900 COP**, un **28% de descuento** sobre su precio de lista de $5.014.143 COP, y el producto parece disponible para compra (no agotado, con envío gratis y cuotas sin interés). Esto cumple **ambas** condiciones de la meta del usuario (≤$3.700.000 COP y ≥20% de descuento). Es la primera vez que este retailer muestra un precio confirmado en el tracker, y es además el primer hallazgo de meta alcanzada en una tienda con disponibilidad real (a diferencia de Enjoy VideoGames, que iguala el precio pero sigue agotado). Dato verificado de forma idéntica en 3 búsquedas WebSearch independientes, aunque no se pudo confirmar con WebFetch directo (bloqueado por `EGRESS_BLOCKED`). **Se cumple la condición de notificación.**

---

## 2026-10-03

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo (modo estándar y extendido) con consultas generales y dirigidas por retailer (Sony Store, Éxito, Falabella, Alkosto, Mercado Libre, Enjoy VideoGames, Ktronix, Pepe Ganga, Colombian UP).

**Nota de calidad de datos:** la mayoría de las consultas de hoy devolvieron únicamente la cifra genérica de lanzamiento (~$4.199.900) repetida en artículos de prensa antiguos (Xataka, El País, ADN40) que **no son snippets de página de producto de ningún retailer específico** — por lo tanto **no se registran como precio confirmado de Sony Store, Éxito, Falabella, Pepe Ganga ni Colombian UP hoy**, para evitar atribuir una cifra genérica a una tienda concreta sin evidencia directa. La única cifra con confirmación sólida y específica hoy fue **Mercado Libre** (listing MCO43294311), reconfirmada en una búsqueda extendida con el mismo detalle exacto que el 2026-10-02 (precio de lista $5.014.143, 28% dcto., 3 cuotas de $1.196.633 sin interés). Alkosto y Ktronix reconfirmaron explícitamente su estado de agotado/sin stock. Enjoy VideoGames no devolvió snippet propio hoy (no reconfirmado). No se detectaron cifras contradictorias o implausibles hoy (no se repitió el error de Éxito del 10-02).

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Mercado Libre | **$3.589.900** (precio de lista $5.014.143, **28% dcto.**) | Listing MCO43294311, "PlayStation PS5 PRO HW 2TB Digital Standard color Blanco". Cifra idéntica a la del 2026-10-02 (3 cuotas de $1.196.633 sin interés). **Sigue cumpliendo la meta del usuario**, pero sin cambio frente a la entrada anterior. | WebSearch (extendido; WebFetch directo bloqueado) |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Reconfirmado nuevamente hoy que el producto (código 711719595700) no tiene unidades disponibles. **Sin cambio.** | WebSearch |
| Ktronix | Sin precio (**producto agotado / sin stock**) | Reconfirmado nuevamente hoy, mismo estado que Alkosto. **Sin cambio.** | WebSearch |
| Sony Store Colombia | Sin precio confirmado hoy (última cifra confiable: $4.399.804, 2026-10-02) | Los snippets de hoy solo repiten la cifra genérica de lanzamiento (~$4.199.900) de artículos de prensa antiguos, no un snippet propio de `store.sony.com.co` con precio actual. **No se registra cifra nueva — no inventada.** | WebSearch (descartado por no ser específico) |
| Éxito | Sin precio confirmado hoy (sin referencia confiable previa; el 10-02 se descartó por implausible) | Mismo problema que Sony Store: solo cifra genérica de prensa, sin snippet propio de Éxito. **No se registra cifra nueva — no inventada.** | WebSearch (descartado) |
| Falabella | Sin precio confirmado hoy (última cifra confiable: $4.139.900, 17% dcto., 2026-10-02) | Sin snippet propio de Falabella hoy, solo la cifra genérica de prensa. **No se registra cifra nueva — no inventada.** | WebSearch (descartado) |
| Pepe Ganga | Sin precio confirmado hoy (última cifra confiable: $4.199.900 pre-order, 2026-10-02) | La búsqueda de hoy no devolvió ningún snippet propio de Pepe Ganga (solo resultados internacionales irrelevantes). **No se registra cifra nueva — no inventada.** | WebSearch (sin snippet propio) |
| Colombian UP | Sin precio confirmado hoy (última cifra confiable: $3.999.000, 11% dcto., 2026-10-02) | La búsqueda de hoy no devolvió snippet propio de colombianup.com con precio, solo la cifra genérica de prensa. **No se registra cifra nueva — no inventada.** | WebSearch (descartado) |
| Enjoy VideoGames | Sin reconfirmar hoy (última cifra conocida: $3.699.000, agotado, 2026-09-30) | La búsqueda dirigida no devolvió snippet propio de `enjoyvideogames.com.co` hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |

**Comparación con la entrada anterior (2026-10-02, retailer por retailer):**
- Mercado Libre: $3.589.900 (28% dcto.) → $3.589.900 (28% dcto.) (**sin cambio**, sigue cumpliendo la meta pero ya se notificó esta oportunidad ayer).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Ktronix: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Sony Store Colombia: $4.399.804 confirmado → sin reconfirmar hoy (se mantiene como última referencia, **sin evidencia de variación**).
- Éxito: descartado por implausible → sin confirmar hoy tampoco (**sin cambio registrable**).
- Falabella: $4.139.900 (17% dcto.) → sin reconfirmar hoy (se mantiene como última referencia, **sin evidencia de variación**).
- Pepe Ganga: $4.199.900 (pre-order) → sin reconfirmar hoy (se mantiene como última referencia, **sin evidencia de variación**).
- Colombian UP: $3.999.000 (11% dcto.) → sin reconfirmar hoy (se mantiene como última referencia, **sin evidencia de variación**).
- Enjoy VideoGames: $3.699.000 (agotado) → sin reconfirmar hoy (se mantiene como última referencia, **sin evidencia de variación**).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer (la única cifra confirmada hoy con detalle propio, Mercado Libre, es idéntica a la de ayer). Mercado Libre sigue cumpliendo la meta del usuario (≤$3.700.000 COP y ≥28% dcto.), pero esto **ya fue reportado el 2026-10-02** y no constituye una novedad nueva hoy. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo. Se obtuvo al menos un dato confiable hoy (Mercado Libre, Alkosto y Ktronix confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

---

## 2026-10-04

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo (modo estándar y extendido) con consultas generales y dirigidas por retailer (Mercado Libre, Sony Store, Falabella, Alkosto, Éxito, Ktronix, Pepe Ganga, Colombian UP, Enjoy VideoGames), más búsquedas adicionales para intentar verificar nombres nuevos detectados en resúmenes agregados.

**Nota de calidad de datos:** una búsqueda extendida con resumen agregado mencionó **cuatro hallazgos nuevos** que **no se pudieron reproducir** en búsquedas `site:`/dirigidas de seguimiento (cada intento de verificación devolvió resultados genéricos no relacionados, sin snippet propio del sitio en cuestión): (1) un listing de **"tienda oficial" de PlayStation en Mercado Libre** a $3.944.000 (22% dcto. desde $5.059.890) — distinto del listing ya conocido MCO43294311 ($3.589.900, 28% dcto.); (2) **Tu360Compras** (marketplace de Bancolombia) vendiendo "Sony Store" a $4.170.903 (3% dcto. desde $4.299.900); (3) **Operación Sistémica** a $4.148.900 (30% dcto. desde $5.927.000); (4) **Audio Color** a $4.149.900 (sin desglose de descuento). Dado que ninguna de estas cuatro cifras pudo confirmarse con un snippet propio e independiente del sitio correspondiente (a diferencia de Mercado Libre MCO43294311, Falabella y Colombian UP, que sí se reconfirmaron con el mismo detalle exacto que en entradas anteriores), **no se registran como datos confirmados ni se usan para evaluar bajadas de precio o la meta del usuario** — siguiendo la regla de nunca inventar/reportar cifras no confiables. Se anotan aquí únicamente para seguimiento en próximos días, por si se logran confirmar de forma independiente. En particular, el listing "tienda oficial" de Mercado Libre (22% dcto.) y el de Operación Sistémica (30% dcto.) **cumplirían la meta del usuario por descuento si se confirman** — algo a vigilar con prioridad. **Gameplay Colombia** ($4.299.900), detectado por primera vez el 2026-10-02 y visto de nuevo hoy en un resumen agregado con la misma cifra, tampoco pudo reproducirse con snippet propio (`site:gameplay.com.co` no devolvió resultados del dominio); se mantiene en el radar sin registrar como confirmado.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Mercado Libre (MCO43294311) | **$3.589.900** (precio de lista $5.014.143, **28% dcto.**) | Listing "PlayStation PS5 PRO HW 2TB Digital Standard color Blanco". Cifra idéntica a la de 2026-10-02 y 2026-10-03 (3 cuotas de $1.196.633 sin interés). **Sigue cumpliendo la meta del usuario**, pero sin cambio frente a la entrada anterior y ya notificado el 10-02. | WebSearch (estándar y extendido; WebFetch directo bloqueado) |
| Falabella | **$4.139.900** (precio de lista $4.299.900, **17% dcto.**) | Producto base 145535455/145535456. Cifra idéntica a la de 2026-10-02, reconfirmada hoy con el mismo desglose exacto. **Sin cambio.** No alcanza la meta (17% < 20%). | WebSearch |
| Colombian UP | **$3.999.000** (precio de lista $4.500.000, **~11% dcto.**) | Cifra idéntica a la de 2026-10-02. **Sin cambio.** No alcanza la meta. | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Reconfirmado nuevamente hoy que el producto (código 711719595700) no tiene unidades disponibles. **Sin cambio.** | WebSearch |
| Sony Store Colombia | Sin precio confirmado hoy (última cifra confiable: $4.399.804, 2026-10-02) | Los snippets de hoy solo repiten la cifra genérica de lanzamiento (~$4.199.900) de artículos de prensa antiguos, no un snippet propio de `store.sony.com.co`. **No se registra cifra nueva — no inventada.** | WebSearch (descartado por no ser específico) |
| Éxito | Sin precio confiable (sin referencia previa válida; el 10-02 se descartó por implausible) | Mismo problema que Sony Store: solo cifra genérica de prensa, sin snippet propio de Éxito. **No se registra cifra — no inventada.** | WebSearch (descartado) |
| Ktronix | Sin reconfirmar hoy (última cifra conocida: agotado, 2026-10-03) | No se obtuvo snippet propio dirigido a Ktronix hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Pepe Ganga | Sin reconfirmar hoy (última cifra conocida: $4.199.900 pre-order, 2026-10-02) | La búsqueda de hoy no devolvió snippet propio de Pepe Ganga. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Enjoy VideoGames | Sin reconfirmar hoy (última cifra conocida: $3.699.000, agotado, 2026-09-30) | La búsqueda dirigida no devolvió snippet propio de `enjoyvideogames.com.co` hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| *Gameplay Colombia (sin confirmar), Mercado Libre "tienda oficial" (sin confirmar), Tu360Compras (sin confirmar), Operación Sistémica (sin confirmar), Audio Color (sin confirmar)* | *Ver nota de calidad de datos arriba* | *Nombres detectados en resúmenes agregados de WebSearch, no reproducibles con snippet propio independiente hoy. No se registran como datos confirmados.* | *WebSearch (no confiable — descartado hoy)* |

**Comparación con la entrada anterior (2026-10-03, retailer por retailer):**
- Mercado Libre (MCO43294311): $3.589.900 (28% dcto.) → $3.589.900 (28% dcto.) (**sin cambio**).
- Falabella: $4.139.900 (17% dcto., sin reconfirmar el 10-03) → $4.139.900 (17% dcto., reconfirmado hoy) (**sin cambio**).
- Colombian UP: $3.999.000 (11% dcto., sin reconfirmar el 10-03) → $3.999.000 (11% dcto., reconfirmado hoy) (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Sony Store Colombia: $4.399.804 (última referencia) → sin reconfirmar hoy tampoco (**sin evidencia de variación**).
- Éxito: sin confirmar → sin confirmar hoy tampoco (**sin cambio registrable**).
- Ktronix: agotado (confirmado 10-03) → sin reconfirmar hoy (se mantiene como referencia).
- Pepe Ganga: sin reconfirmar → sin reconfirmar hoy tampoco (**sin evidencia de variación**).
- Enjoy VideoGames: sin reconfirmar → sin reconfirmar hoy tampoco (**sin evidencia de variación**).
- Retailers nuevos: ninguno **confirmado** (los cinco nombres detectados hoy en resúmenes agregados — Gameplay Colombia, Mercado Libre "tienda oficial", Tu360Compras, Operación Sistémica, Audio Color — no pudieron verificarse de forma independiente y no se cuentan como novedad real por ahora; quedan en el radar para intentar confirmar en próximas ejecuciones). Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% **confirmada** en ningún retailer (Falabella y Colombian UP reconfirman exactamente las mismas cifras del 10-02; Mercado Libre repite la cifra del 10-03). Mercado Libre (MCO43294311) sigue cumpliendo la meta del usuario, pero sin cambio y ya reportado el 10-02. Ningún otro retailer con dato confiable alcanza la meta hoy. Los posibles hallazgos de interés (el listing "tienda oficial" de Mercado Libre con 22% dcto. y Operación Sistémica con 30% dcto., que de confirmarse cumplirían la meta por descuento) **no se pudieron verificar de forma independiente hoy** y por tanto, siguiendo la regla de nunca reportar cifras no confiables, **no constituyen una novedad confirmada ni activan notificación** — quedan señalados para intentar confirmar en los próximos días. Se obtuvo al menos un dato confiable hoy (Mercado Libre, Falabella, Colombian UP y Alkosto confirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

---

## 2026-10-05

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo con consultas generales y dirigidas por retailer (`site:`) para cada tienda ya conocida, más verificación dirigida de los nombres nuevos detectados el 2026-10-04 que no se habían podido reproducir ese día.

**Nota de calidad de datos — retailers nuevos confirmados hoy:** a diferencia del 2026-10-04 (donde varios nombres solo aparecían en resúmenes agregados no reproducibles), hoy se logró **confirmar de forma independiente con `site:` dirigido a la página exacta del producto** tres retailers nuevos:
- **Cadena Multi** (`cadenamulti.co/products/playstation-5-pro-2tb-1-control`): $3.850.000 (precio de lista $4.400.000, ~12,5% dcto.).
- **Gameplay Colombia** (`gameplay.com.co/products/playstation-5-pro-digital-2tb`): $4.299.900 (precio de lista $4.499.900, ~4,4% dcto.). Este nombre ya se había visto sin confirmar el 2026-10-02 y 2026-10-04.
- **Tu360Compras** (marketplace de Bancolombia, `tu360compras.grupobancolombia.com`): $4.170.903 (precio de lista $4.299.900, 3% dcto.; +10% dcto. adicional pagando con tarjeta Bancolombia). Ya se había visto sin confirmar el 2026-10-04 bajo el nombre genérico de "Sony Store" en un resumen agregado.

**Hallazgo a verificar con cautela — Operación Sistémica:** también se confirmó hoy, con `site:` dirigido a la página exacta (`operacionsistemica.com/comprar/ps5-pro/`), el retailer **Operación Sistémica** (tienda colombiana real con puntos físicos en Barrancabermeja, Cartagena, Valledupar, Montería, Aguachica y Pereira, envíos a toda Colombia — verificado independientemente que no es una tienda extranjera) a **$4.148.900** con "todos los medios de pago", frente a un precio de lista de **$5.927.000**, lo que da un **~30% de descuento**. Esta cifra fue mencionada sin confirmar el 2026-10-04 con el mismo valor exacto, y hoy se reconfirmó con fuente directa. Numéricamente **supera el umbral de descuento de la meta del usuario (≥20%)**. Sin embargo, se reporta con una **salvedad importante**: el precio de lista de $5.927.000 es considerablemente más alto que la referencia de lista de cualquier otro retailer (que rondan $4.3M–$4.6M, salvo Mercado Libre con $5.014.143), lo cual podría ser un precio de lista "ancla" inflado con fines de marketing en lugar de un precio de lista real — un patrón distinto al de Éxito (que se descartó por mostrar cifras de producto distinto/implausibles), pero que de todos modos amerita verificación manual antes de considerarlo una oportunidad de compra confirmada al 100%. No se pudo confirmar disponibilidad/stock exacto (la consulta de stock del sitio dio error). **Se registra con esta advertencia explícita, no como cifra 100% verificada.**

No se pudo confirmar hoy: **Audio Color** (`audiocolor.co`, mencionado el 10-04, la búsqueda dirigida no devolvió resultados del dominio) y el listado de "tienda oficial" de PlayStation en Mercado Libre con 22%/30% dcto. mencionado el 10-04 (las búsquedas de hoy devolvieron varias cifras distintas e inconsistentes entre sí para listados "oficiales" de ML, sin una cifra única reproducible — se descarta por ahora, se mantiene en el radar).

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Mercado Libre (MCO43294311) | **$3.589.900** (precio de lista $5.014.143, **28% dcto.**) | Listing "PlayStation PS5 PRO HW 2TB Digital Standard color Blanco". Cifra idéntica a la de 2026-10-02/03/04 (3 cuotas de $1.196.633 sin interés). **Sigue cumpliendo la meta del usuario**, pero sin cambio y ya notificado el 10-02. | WebSearch (`site:mercadolibre.com.co`; WebFetch directo bloqueado) |
| Sony Store Colombia | $4.399.803 | Confirmado en stock. Cifra esencialmente idéntica a la de 2026-10-02 ($4.399.804). **Sin cambio.** | WebSearch (`site:store.sony.com.co`) |
| Falabella | $4.139.900 (precio de lista $4.299.900, **17% dcto.**) | Producto base 145535455/145535456. Cifra idéntica a la de 2026-10-02 y 2026-10-04. **Sin cambio.** No alcanza la meta. | WebSearch (`site:falabella.com.co`) |
| Colombian UP | $3.999.000 (precio de lista $4.500.000, **~11% dcto.**) | Cifra idéntica a la de 2026-10-02 y 2026-10-04. **Sin cambio.** No alcanza la meta. | WebSearch |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Reconfirmado nuevamente hoy, código 711719595700. **Sin cambio.** | WebSearch (`site:alkosto.com`) |
| Ktronix | Sin precio (**producto agotado / sin stock**) | Reconfirmado nuevamente hoy. **Sin cambio.** | WebSearch (`site:ktronix.com`) |
| Enjoy VideoGames | $3.699.000 (**producto agotado / sin stock**) | Cifra idéntica a la última conocida (2026-09-30). Sigue sin disponibilidad real — **no** se trata como oportunidad de compra. | WebSearch (`site:enjoyvideogames.com.co`) |
| **Cadena Multi** 🆕 | **$3.850.000** (precio de lista $4.400.000, **~12,5% dcto.**) | **Retailer nuevo confirmado hoy por primera vez** con fuente directa (`cadenamulti.co/products/playstation-5-pro-2tb-1-control`). No alcanza la meta (precio > $3.700.000, dcto. < 20%). | WebSearch (`site:cadenamulti.co`) |
| **Gameplay Colombia** 🆕 | $4.299.900 (precio de lista $4.499.900, ~4,4% dcto.) | **Retailer nuevo confirmado hoy por primera vez** (mencionado sin confirmar el 10-02 y 10-04). No alcanza la meta. | WebSearch (`site:gameplay.com.co`) |
| **Tu360Compras (Bancolombia)** 🆕 | $4.170.903 (precio de lista $4.299.900, 3% dcto. + 10% adicional con tarjeta Bancolombia) | **Retailer nuevo confirmado hoy por primera vez** con fuente directa. No alcanza la meta. | WebSearch (`site:tu360compras.grupobancolombia.com`) |
| **Operación Sistémica** 🆕 ⚠️ | $4.148.900 (precio de lista $5.927.000, **~30% dcto.**) | **Retailer nuevo confirmado hoy por primera vez** con fuente directa, tienda colombiana real verificada (Barrancabermeja y otras 5 ciudades). Numéricamente supera el umbral de descuento de la meta (≥20%), **pero el precio de lista es inusualmente alto comparado con el resto del mercado — se reporta con advertencia de posible precio "ancla" inflado, pendiente de verificación manual**. Disponibilidad/stock no confirmada. | WebSearch (`site:operacionsistemica.com`) |
| Éxito | **Cifras descartadas por implausibles de nuevo** (valores de $8M+→$4.8M que no corresponden de forma clara a este producto específico) | Mismo patrón que el 2026-10-02. **No se registra cifra — no inventada.** | WebSearch (descartado) |
| Pepe Ganga | Sin reconfirmar hoy (última cifra conocida: $4.199.900 pre-order, 2026-10-02) | La búsqueda dirigida no devolvió snippet propio de Pepe Ganga hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| *Audio Color, "tienda oficial" PS5 Pro en Mercado Libre* | *Ver nota de calidad de datos arriba* | *No reproducibles de forma consistente hoy. No se registran como datos confirmados.* | *WebSearch (no confiable — descartado hoy)* |

**Comparación con la entrada anterior (2026-10-04, retailer por retailer):**
- Mercado Libre (MCO43294311): $3.589.900 (28% dcto.) → $3.589.900 (28% dcto.) (**sin cambio**).
- Sony Store Colombia: $4.399.804 (10-02) → $4.399.803 hoy (**sin cambio real**, diferencia de redondeo).
- Falabella: $4.139.900 (17% dcto.) → $4.139.900 (17% dcto.) (**sin cambio**).
- Colombian UP: $3.999.000 (11% dcto.) → $3.999.000 (11% dcto.) (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Ktronix: sin reconfirmar el 10-04 → agotado reconfirmado hoy (**sin cambio real**).
- Enjoy VideoGames: sin reconfirmar el 10-04 → $3.699.000 agotado reconfirmado hoy (**sin cambio real**).
- Pepe Ganga: sin reconfirmar → sin reconfirmar hoy tampoco (**sin evidencia de variación**).
- Éxito: descartado por implausible → descartado por implausible de nuevo hoy (**sin cambio registrable**).
- **Retailers nuevos confirmados hoy: Cadena Multi, Gameplay Colombia y Tu360Compras (Bancolombia)** — los tres mencionados sin confirmar en días anteriores (o nunca vistos, en el caso de Cadena Multi), hoy verificados con fuente directa (`site:` a la página exacta del producto). **Esto constituye una novedad real** (nuevos retailers vendiendo la consola que no estaban confirmados antes).
- **Operación Sistémica** también se confirma hoy por primera vez con fuente directa (mencionado sin confirmar el 10-04 con la misma cifra), y su descuento del ~30% **numéricamente alcanza la meta del usuario**, aunque con la advertencia de precio de lista inusualmente alto señalada arriba.
- Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer ya conocido (todos los valores confirmados hoy en Mercado Libre, Sony Store, Falabella, Colombian UP, Alkosto, Ktronix y Enjoy VideoGames son idénticos a sus últimas cifras conocidas). **Sí hay novedad real confirmada hoy: tres retailers nuevos** (Cadena Multi, Gameplay Colombia, Tu360Compras/Bancolombia) se confirman por primera vez con fuente directa, ampliando el catálogo de tiendas monitoreadas. Adicionalmente, **Operación Sistémica** se confirma como retailer nuevo con un descuento (~30%) que numéricamente supera el umbral de la meta del usuario (≥20% dcto.), aunque se reporta con cautela por su precio de lista atípicamente alto frente al resto del mercado (posible precio "ancla" de marketing) — se recomienda verificación manual directa en el sitio antes de tratarlo como una oportunidad de compra confirmada. Mercado Libre (MCO43294311) sigue cumpliendo la meta de forma sólida y ya reportada (28% dcto., $3.589.900, disponible), sin cambios hoy. **Se cumple la condición de notificación** por la aparición de retailers nuevos confirmados y por el hallazgo (con advertencia) de un segundo caso que numéricamente alcanza la meta de descuento.

---

## 2026-10-06

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo (modo estándar y extendido) con consultas generales, `site:` dirigidas por retailer (Mercado Libre, Sony Store, Falabella, Alkosto, Ktronix, Enjoy VideoGames, Cadena Multi, Operación Sistémica, Tu360Compras, Gameplay Colombia) y una búsqueda extendida general de ofertas de octubre.

**Nota de calidad de datos:** la mayoría de las búsquedas `site:` dirigidas por retailer no devolvieron hoy ningún snippet propio del dominio exacto (solo resultados genéricos de otros países o retailers no relacionados), salvo Alkosto (confirmado agotado vía `site:alkosto.com`). Sin embargo, una búsqueda extendida general ("PS5 Pro 2TB Colombia oferta descuento nueva tienda octubre") sí devolvió un resumen agregado citando las URLs exactas de producto ya conocidas de Falabella, Sony Store, Gameplay Colombia y Colombian UP, con cifras **idénticas a las de la entrada anterior (2026-10-05)** en los cuatro casos — se tratan como reconfirmadas. Éxito repitió el mismo patrón de cifras implausibles ya visto en entradas previas ($4.798.678–$4.846.740, rango que no corresponde claramente a este producto) y se descarta de nuevo. No se logró reconfirmar hoy, ni de forma general ni con `site:` dirigido: Mercado Libre (listing MCO43294311 específico), Ktronix, Enjoy VideoGames, Cadena Multi, Tu360Compras, ni Operación Sistémica — se mantienen con su último valor conocido como referencia, sin evidencia de variación.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Mercado Libre (MCO43294311) | Sin reconfirmar hoy (última cifra conocida: $3.589.900, precio de lista $5.014.143, 28% dcto., 2026-10-05) | Ni la búsqueda `site:mercadolibre.com.co` ni la general devolvieron el snippet exacto de este listing hoy (solo resultados de otros países y un resumen genérico de "hasta 30% dcto." sin cifra específica). Se mantiene como referencia sin reconfirmar. **Sigue siendo, de no haber cambiado, la oferta que ya cumple la meta del usuario** (reportada el 10-02). | — (sin snippet propio hoy) |
| Sony Store Colombia | **$4.399.804** (precio de lista $4.599.900) | Reconfirmado hoy en un resumen agregado que cita la URL exacta `store.sony.com.co/ps5-pro-hw-2tb/p`. Cifra idéntica a la de 2026-10-02 y 2026-10-05. **Sin cambio.** | WebSearch (extendido; WebFetch directo bloqueado) |
| Falabella | **$4.139.900** (precio de lista $4.299.900, **17% dcto.**) | Reconfirmado hoy en el mismo resumen, citando la URL exacta del producto base 145535455/145535456. Cifra idéntica a entradas anteriores. **Sin cambio.** No alcanza la meta (17% < 20%). | WebSearch (extendido) |
| Gameplay Colombia | $4.299.900 (precio de lista $4.499.900, ~4,4% dcto.) | Reconfirmado hoy citando la URL exacta `gameplay.com.co/products/playstation-5-pro-digital-2tb`. Cifra idéntica a la de 2026-10-05. **Sin cambio.** No alcanza la meta. | WebSearch (extendido) |
| Colombian UP | $3.999.000 (precio de lista $4.500.000, **~11% dcto.**) | Reconfirmado hoy citando la URL exacta `colombianup.com/tienda/consolas/consola-playstation-5-digital-pro-2tb/`. Cifra idéntica a entradas anteriores. **Sin cambio.** No alcanza la meta. | WebSearch (extendido) |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Reconfirmado hoy vía `site:alkosto.com`, mismo código de producto (711719595700). **Sin cambio.** | WebSearch (`site:alkosto.com`) |
| Ktronix | Sin reconfirmar hoy (última cifra conocida: agotado, 2026-10-05) | La búsqueda `site:ktronix.com` dirigida no devolvió snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Enjoy VideoGames | Sin reconfirmar hoy (última cifra conocida: $3.699.000, agotado, 2026-10-05) | La búsqueda `site:enjoyvideogames.com.co` dirigida no devolvió snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Cadena Multi | Sin reconfirmar hoy (última cifra conocida: $3.850.000, precio de lista $4.400.000, ~12,5% dcto., 2026-10-05) | La búsqueda `site:cadenamulti.co` dirigida no devolvió snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Tu360Compras (Bancolombia) | Sin reconfirmar hoy (última cifra conocida: $4.170.903, precio de lista $4.299.900, 3% dcto. + 10% adicional con tarjeta Bancolombia, 2026-10-05) | La búsqueda `site:tu360compras.grupobancolombia.com` dirigida no devolvió snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Operación Sistémica ⚠️ | Sin reconfirmar hoy (última cifra conocida: $4.148.900, precio de lista $5.927.000, ~30% dcto., 2026-10-05 — con advertencia de posible precio "ancla" inflado, pendiente de verificación manual) | La búsqueda `site:operacionsistemica.com` dirigida no devolvió snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar, con la misma advertencia de cautela de la entrada anterior. | — (sin snippet propio hoy) |
| Éxito | **Cifras descartadas por implausibles de nuevo** (rango $4.798.678–$4.846.740, no corresponde claramente a este producto) | Mismo patrón de descarte que entradas previas. **No se registra cifra — no inventada.** | WebSearch (descartado) |

**Comparación con la entrada anterior (2026-10-05, retailer por retailer):**
- Mercado Libre (MCO43294311): $3.589.900 (28% dcto.) → sin reconfirmar hoy (**sin evidencia de variación**; se mantiene como referencia).
- Sony Store Colombia: $4.399.803 → $4.399.804 (**sin cambio real**, diferencia de redondeo/formato).
- Falabella: $4.139.900 (17% dcto.) → $4.139.900 (17% dcto.) (**sin cambio**).
- Gameplay Colombia: $4.299.900 → $4.299.900 (**sin cambio**).
- Colombian UP: $3.999.000 (11% dcto.) → $3.999.000 (11% dcto.) (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Ktronix: agotado (confirmado 10-05) → sin reconfirmar hoy (**sin evidencia de variación**).
- Enjoy VideoGames: $3.699.000 agotado (confirmado 10-05) → sin reconfirmar hoy (**sin evidencia de variación**).
- Cadena Multi: $3.850.000 (12,5% dcto., confirmado 10-05) → sin reconfirmar hoy (**sin evidencia de variación**).
- Tu360Compras: $4.170.903 (confirmado 10-05) → sin reconfirmar hoy (**sin evidencia de variación**).
- Operación Sistémica: $4.148.900 (~30% dcto., confirmado 10-05, con advertencia) → sin reconfirmar hoy (**sin evidencia de variación**).
- Éxito: descartado por implausible → descartado por implausible de nuevo hoy (**sin cambio registrable**).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer con dato confiable hoy (los cuatro valores reconfirmados — Sony Store, Falabella, Gameplay Colombia, Colombian UP — son idénticos a sus últimas cifras conocidas). Ningún retailer con dato reconfirmado hoy alcanza la meta del usuario (≤$3.700.000 COP o ≥20% dcto.); los dos casos que sí la alcanzarían o se acercan (Mercado Libre al 28% y Operación Sistémica al ~30%, este último con advertencia) no se pudieron reconfirmar hoy, por lo que se mantienen como referencia de días anteriores, ya reportados, sin novedad nueva que notificar. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo hoy. Se obtuvo al menos un dato confiable hoy (Sony Store, Falabella, Gameplay Colombia, Colombian UP y Alkosto reconfirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

---

## 2026-10-07

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo (modo estándar y extendido) con consultas generales, dirigidas por retailer (`site:` para Mercado Libre, Sony Store, Falabella, Alkosto, Ktronix, Colombian UP, Gameplay Colombia, Cadena Multi, Tu360Compras, Operación Sistémica, Enjoy VideoGames) y una búsqueda extendida general de ofertas de octubre.

**Nota de calidad de datos:** la mayoría de las búsquedas `site:` dirigidas no devolvieron hoy snippets propios del dominio exacto (solo resultados internacionales o genéricos). Una búsqueda extendida general ("PS5 Pro 2TB Colombia oferta descuento octubre 2026") sí devolvió resultados citando URLs exactas de Colombian UP, Éxito, Falabella, Enjoy VideoGames y Mercado Libre, pero en varios casos (Falabella, Mercado Libre) las cifras citadas fueron **rangos agregados o contradictorios entre búsquedas** (dos consultas distintas dieron a Falabella $4.699.900/22% dcto. y $4.599.900/23% dcto. en la misma sesión, ninguna coincide con la última cifra confiable conocida de $4.139.900/17% dcto., y ninguna se confirmó con un snippet que citara directamente las URLs del producto base 145535455/145535456) — siguiendo el mismo criterio de cautela de entradas anteriores, **se descartan estas cifras de Falabella y de Mercado Libre por hoy**, no se registran como actualización. Éxito repitió de nuevo el mismo patrón de cifras implausibles ya visto en días previos ($4.798.678 desde una lista de $8.397.687) y se descarta igual que siempre. Sony Store, Gameplay Colombia, Cadena Multi, Tu360Compras y Operación Sistémica no se pudieron reconfirmar hoy con ninguna búsqueda (ni general ni `site:`); se mantienen con su último valor conocido como referencia, sin evidencia de variación.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Colombian UP | **$3.950.000** (precio de lista $4.500.000, **~12,2% dcto.**) | Confirmado hoy citando la URL exacta `colombianup.com/tienda/consolas/consola-playstation-5-digital-pro-2tb/`. Leve baja frente a los $3.999.000 (11% dcto.) de entradas anteriores, pero la variación (~1,2%) es muy inferior al umbral de notificación (≥10%). No alcanza la meta. | WebSearch (extendido) |
| Enjoy VideoGames | $3.699.000 (**producto agotado / sin stock**) | Reconfirmado hoy citando la URL exacta `enjoyvideogames.com.co/product-category/consolas-de-videojuegos/playstation/playstation-5/`. Cifra idéntica a la última conocida. Sigue sin disponibilidad real — **no** se trata como oportunidad de compra. **Sin cambio.** | WebSearch (extendido) |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Reconfirmado hoy, mismo código de producto (711719595700). **Sin cambio.** | WebSearch |
| Ktronix | Sin precio (**producto agotado / sin stock**) | Reconfirmado hoy, mismo código de producto (711719595700). **Sin cambio.** | WebSearch |
| Mercado Libre (MCO43294311) | Sin reconfirmar hoy (última cifra conocida: $3.589.900, precio de lista $5.014.143, 28% dcto., 2026-10-05) | Las búsquedas de hoy solo devolvieron un rango agregado y no reproducible ("$3.480.000 a $4.399.999") sin citar el listing exacto MCO43294311 — se descarta por no ser confiable, siguiendo el criterio de cautela habitual. Se mantiene el último valor conocido como referencia. **Sigue siendo, de no haber cambiado, la oferta que ya cumple la meta del usuario** (reportada el 10-02). | — (dato de hoy descartado por no confiable) |
| Falabella | Sin reconfirmar hoy (última cifra conocida: $4.139.900, precio de lista $4.299.900, 17% dcto., 2026-10-06) | Dos búsquedas distintas de hoy dieron cifras diferentes entre sí ($4.699.900/22% dcto. y $4.599.900/23% dcto. desde una lista de $5.999.000), ninguna coincide con la última cifra confiable ni cita directamente la URL del producto base — se descartan ambas por contradictorias/no confiables. | — (dato de hoy descartado por no confiable) |
| Sony Store Colombia | Sin reconfirmar hoy (última cifra conocida: $4.399.804, precio de lista $4.599.900, 2026-10-06) | Ninguna búsqueda de hoy (general ni `site:`) devolvió un snippet propio de `store.sony.com.co` con precio. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Gameplay Colombia | Sin reconfirmar hoy (última cifra conocida: $4.299.900, precio de lista $4.499.900, ~4,4% dcto., 2026-10-06) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Cadena Multi | Sin reconfirmar hoy (última cifra conocida: $3.850.000, precio de lista $4.400.000, ~12,5% dcto., 2026-10-05) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Tu360Compras (Bancolombia) | Sin reconfirmar hoy (última cifra conocida: $4.170.903, precio de lista $4.299.900, 3% dcto. + 10% adicional con tarjeta Bancolombia, 2026-10-05) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Operación Sistémica ⚠️ | Sin reconfirmar hoy (última cifra conocida: $4.148.900, precio de lista $5.927.000, ~30% dcto., 2026-10-05 — con advertencia de posible precio "ancla" inflado, pendiente de verificación manual) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar, con la misma advertencia de cautela de entradas anteriores. | — (sin snippet propio hoy) |
| Éxito | **Cifras descartadas por implausibles de nuevo** ($4.798.678 desde una lista de $8.397.687, no corresponde de forma clara a este producto) | Mismo patrón de descarte que entradas previas. **No se registra cifra — no inventada.** | WebSearch (descartado) |

**Comparación con la entrada anterior (2026-10-06, retailer por retailer):**
- Colombian UP: $3.999.000 (11% dcto.) → $3.950.000 (~12,2% dcto.) (**baja leve, ~1,2%** — muy por debajo del umbral de notificación del 10%).
- Enjoy VideoGames: $3.699.000 agotado → $3.699.000 agotado (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Ktronix: sin reconfirmar el 10-06 → agotado reconfirmado hoy (**sin cambio real**).
- Mercado Libre: sin reconfirmar el 10-06 → sin reconfirmar hoy tampoco (dato de hoy descartado por no confiable) (**sin evidencia de variación**; se mantiene como referencia).
- Falabella: $4.139.900 (17% dcto., última cifra confiable del 10-06) → cifras de hoy contradictorias y descartadas (**sin evidencia de variación confiable**; se mantiene la última cifra conocida como referencia).
- Sony Store, Gameplay Colombia, Cadena Multi, Tu360Compras, Operación Sistémica: sin reconfirmar hoy (**sin evidencia de variación**; se mantienen como referencia).
- Éxito: descartado por implausible → descartado por implausible de nuevo hoy (**sin cambio registrable**).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** La única variación de precio con dato confiable fue Colombian UP, con una baja leve de ~1,2% ($3.999.000 → $3.950.000), muy por debajo del umbral de notificación (≥10%). Ningún retailer con dato confiable hoy alcanza la meta del usuario (≤$3.700.000 COP o ≥20% dcto.); los casos que sí la alcanzan (Mercado Libre al 28%, Operación Sistémica al ~30% con advertencia) no se pudieron reconfirmar hoy y siguen siendo los mismos ya reportados en entradas anteriores, sin novedad nueva. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo hoy. Se obtuvo al menos un dato confiable hoy (Colombian UP, Enjoy VideoGames, Alkosto y Ktronix reconfirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

---

## 2026-10-08

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo (modo estándar y extendido) con una consulta general y dirigidas por retailer (`site:` para Mercado Libre, Sony Store, Falabella, Colombian UP, Alkosto, Ktronix, Operación Sistémica, Gameplay Colombia, Cadena Multi, Tu360Compras, Éxito).

**Nota de calidad de datos:** la búsqueda extendida general ("PS5 Pro Digital 2TB precio Colombia octubre 2026") devolvió, entre sus resultados, la URL exacta del listing de Mercado Libre (MCO43294311) y citó la misma cifra ya conocida ($3.589.900, 28% dcto.), por lo que se trata como reconfirmada. La misma búsqueda también mencionó una oferta de "tienda oficial" de Mercado Libre a $3.944.000, pero sin una URL exacta propia que la respalde (igual que en días anteriores con nombres similares) — **no se registra como cifra confirmada**, queda en el radar. Falabella no devolvió resultado con la búsqueda `site:` dirigida al SKU exacto, pero la búsqueda general sí citó la cifra ya conocida ($4.139.900, -17%) para el producto "Pro Digital 2TB" de la tienda Usaquén (marcada sin stock en esa sede puntual), por lo que se trata como reconfirmada; aparte, se detectó una oferta distinta de un vendedor marketplace ("Rxggames") a $4.699.900 (desde $5.999.000) para un listado separado "Digital 2TB" — se registra por separado y con cautela, sin mezclarla con la cifra de la SKU ya monitoreada, siguiendo el mismo criterio de días anteriores ante cifras contradictorias de Falabella. Colombian UP fue reconfirmado por la búsqueda general citando la URL exacta, con la misma cifra de la entrada anterior ($3.950.000). Gameplay Colombia fue mencionado en la búsqueda general con su precio ya conocido ($4.299.900) pero ahora indicado como **agotado** (antes no se había señalado explícitamente este estado) — se registra como posible cambio de disponibilidad, aunque sin una segunda fuente que lo confirme de forma independiente hoy. Sony Store, Operación Sistémica, Cadena Multi, Tu360Compras y Éxito no devolvieron ningún snippet propio del dominio exacto hoy (ni con `site:` ni en la búsqueda general) — se mantienen con su último valor conocido como referencia, sin evidencia de variación.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Mercado Libre (MCO43294311) | **$3.589.900** (precio de lista $5.014.143, **28% dcto.**) | Reconfirmado hoy citando la URL exacta del listing en la búsqueda general. Cifra idéntica a entradas anteriores. **Sin cambio.** **Sigue cumpliendo la meta del usuario**, ya reportada el 10-02. | WebSearch (extendido; WebFetch directo bloqueado) |
| Falabella | **$4.139.900** (precio de lista $4.299.900, **17% dcto.**) | Reconfirmado hoy en la búsqueda general para el producto "Pro Digital 2TB" (tienda Usaquén, sin stock en esa sede puntual). Cifra idéntica a entradas anteriores. **Sin cambio.** No alcanza la meta. | WebSearch (extendido) |
| Colombian UP | $3.950.000 (precio de lista $4.500.000, **~12,2% dcto.**) | Reconfirmado hoy citando la URL exacta `colombianup.com/tienda/consolas/consola-playstation-5-digital-pro-2tb/`. Cifra idéntica a la de 2026-10-07. **Sin cambio.** No alcanza la meta. | WebSearch (extendido) |
| Enjoy VideoGames | $3.699.000 (**producto agotado / sin stock**) | Reconfirmado hoy. Cifra idéntica a la última conocida. Sigue sin disponibilidad real. **Sin cambio.** | WebSearch (extendido) |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Reconfirmado hoy vía `site:alkosto.com`, mismo código de producto (711719595700). **Sin cambio.** | WebSearch (`site:alkosto.com`) |
| Ktronix | Sin precio (**producto agotado / sin stock**) | Reconfirmado hoy vía `site:ktronix.com`, mismo código de producto. **Sin cambio.** | WebSearch (`site:ktronix.com`) |
| Gameplay Colombia | $4.299.900 (precio de lista $4.499.900, ~4,4% dcto.) | Precio idéntico al conocido, pero mencionado hoy como **agotado** — posible cambio de disponibilidad frente a entradas previas donde no se señalaba este estado explícitamente. Sin segunda fuente independiente hoy que lo confirme; se registra con cautela. No alcanza la meta en todo caso. | WebSearch (extendido) |
| *Falabella Marketplace ("Rxggames", listado "Digital 2TB" separado)* | $4.699.900 (precio de lista $5.999.000, ~21,7% dcto.) | **No es la SKU 145535455/145535456 ya monitoreada** — es un listado de marketplace distinto. Numéricamente su descuento superaría la meta (≥20%), pero no se mezcla con el dato ya confirmado de Falabella por tratarse de un vendedor y listado diferentes, siguiendo el mismo criterio de cautela de entradas anteriores ante cifras de Falabella contradictorias entre sí. Pendiente de verificación manual antes de considerarlo una oportunidad real. | WebSearch (extendido) |
| Sony Store Colombia | Sin reconfirmar hoy (última cifra conocida: $4.399.804, precio de lista $4.599.900, 2026-10-06) | Ninguna búsqueda de hoy (general ni `site:`) devolvió snippet propio de `store.sony.com.co`. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Cadena Multi | Sin reconfirmar hoy (última cifra conocida: $3.850.000, precio de lista $4.400.000, ~12,5% dcto., 2026-10-05) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Tu360Compras (Bancolombia) | Sin reconfirmar hoy (última cifra conocida: $4.170.903, precio de lista $4.299.900, 3% dcto. + 10% adicional con tarjeta Bancolombia, 2026-10-05) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Operación Sistémica ⚠️ | Sin reconfirmar hoy (última cifra conocida: $4.148.900, precio de lista $5.927.000, ~30% dcto., 2026-10-05 — con advertencia de posible precio "ancla" inflado, pendiente de verificación manual) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar, con la misma advertencia de cautela de entradas anteriores. | — (sin snippet propio hoy) |
| Éxito | Sin precio confiable hoy (sin reconfirmar) | Ninguna búsqueda de hoy (general ni `site:exito.com`) devolvió snippet propio del dominio. **No se registra cifra — no inventada.** | — (sin snippet propio hoy) |

**Comparación con la entrada anterior (2026-10-07, retailer por retailer):**
- Mercado Libre (MCO43294311): $3.589.900 (28% dcto.) → $3.589.900 (28% dcto.) (**sin cambio**).
- Falabella: última cifra confiable $4.139.900 (17% dcto.) → $4.139.900 (17% dcto.) reconfirmado hoy (**sin cambio**).
- Colombian UP: $3.950.000 (~12,2% dcto.) → $3.950.000 (~12,2% dcto.) (**sin cambio**).
- Enjoy VideoGames: $3.699.000 agotado → $3.699.000 agotado (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Ktronix: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Gameplay Colombia: $4.299.900 (sin estado de disponibilidad señalado) → $4.299.900 (hoy señalado como agotado) (**posible cambio de disponibilidad, no confirmado de forma independiente**).
- Sony Store, Cadena Multi, Tu360Compras, Operación Sistémica: sin reconfirmar hoy (**sin evidencia de variación**; se mantienen como referencia).
- Éxito: sin reconfirmar (ya se venía descartando por implausible en entradas previas) → sin reconfirmar hoy tampoco (**sin cambio registrable**).
- Retailers nuevos confirmados: ninguno (el listado de marketplace "Rxggames" en Falabella y la "tienda oficial" de Mercado Libre a $3.944.000 no se consideran retailers/listados nuevos confirmados de forma independiente, siguiendo el criterio de cautela habitual). Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer con dato confiable hoy (Mercado Libre, Falabella, Colombian UP, Enjoy VideoGames, Alkosto y Ktronix reconfirman exactamente sus últimas cifras conocidas). Ningún retailer con dato confiable hoy alcanza por primera vez la meta del usuario; Mercado Libre sigue cumpliéndola pero sin cambio y ya reportado el 10-02. El posible cambio de disponibilidad de Gameplay Colombia (pasaría a agotado) y la oferta de marketplace "Rxggames" en Falabella (~21,7% dcto., sin verificación independiente ni coincidencia con la SKU ya monitoreada) no se consideran novedades confirmadas lo bastante sólidas para notificar — quedan señaladas para intentar confirmar en próximas ejecuciones. Se obtuvo al menos un dato confiable hoy (Mercado Libre, Falabella, Colombian UP, Enjoy VideoGames, Alkosto y Ktronix reconfirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

## 2026-10-09

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado con `EGRESS_BLOCKED`. WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados con `EGRESS_BLOCKED`. Se usó **WebSearch** de respaldo (modo estándar y extendido) con una consulta general y dirigidas por retailer (`site:` para Mercado Libre, Colombian UP, Falabella, Alkosto, Ktronix, Sony Store, Éxito, Enjoy VideoGames, Cadena Multi).

**Nota de calidad de datos:** la búsqueda extendida general ("PS5 Pro Digital 2TB Colombia octubre 2026 precio oferta") citó directamente las URLs de Mercado Libre (MCO43294311), Colombian UP, Gameplay Colombia, Falabella y Tu360Compras, reconfirmando las mismas cifras ya conocidas. Las búsquedas dirigidas `site:` a Alkosto y Ktronix reconfirmaron de forma explícita el estado "Producto agotado" para el código 711719595700 en ambas tiendas (mismo código de producto que entradas previas). La búsqueda general también mostró, de la ficha oficial de Sony en Falabella ("Consola PlayStation 5® Digital PRO 2TB", producto 137865821/137865822, distinta del SKU 145535455/145535456 ya monitoreado), un estado de **agotado** con menciones ambiguas de $3.699.900 y $4.299.900 sin precisar cuál es el precio vigente ni el descuento — se descarta por no ser una cifra confiable y clara, siguiendo el mismo criterio de cautela de entradas anteriores ante datos contradictorios de Falabella. Para Operación Sistémica, el snippet de hoy sugiere que la oferta ($4.148.900 vs $5.927.000) podría haber finalizado el 30 de julio de 2026 según la página indexada; no se pudo confirmar de forma independiente si sigue vigente, así que se mantiene con la misma advertencia ⚠️ de entradas anteriores más esta nueva señal de posible vencimiento. Sony Store Colombia, Éxito, Enjoy VideoGames y Cadena Multi no devolvieron ningún snippet propio del dominio exacto hoy (ni con `site:` ni en la búsqueda general) — se mantienen con su último valor conocido como referencia, sin evidencia de variación.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Mercado Libre (MCO43294311) | **$3.589.900** (precio de lista $5.014.143, **28% dcto.**) | Reconfirmado hoy citando la URL exacta del listing. Cifra idéntica a entradas anteriores. **Sin cambio.** **Sigue cumpliendo la meta del usuario**, ya reportada el 10-02. | WebSearch (extendido; WebFetch directo bloqueado) |
| Falabella | **$4.139.900** (precio de lista $4.299.900, **17% dcto.**) | Reconfirmado hoy en la búsqueda general para el producto "Pro Digital 2TB" (SKU 145535455/145535456). Cifra idéntica a entradas anteriores. **Sin cambio.** No alcanza la meta. | WebSearch (extendido) |
| Colombian UP | $3.950.000 (precio de lista $4.500.000, **~12,2% dcto.**) | Reconfirmado hoy citando la URL exacta `colombianup.com/tienda/consolas/consola-playstation-5-digital-pro-2tb/`. Cifra idéntica a entradas anteriores. **Sin cambio.** No alcanza la meta. | WebSearch (extendido) |
| Gameplay Colombia | $4.299.900 (precio de lista $4.499.900, ~4,4% dcto.) | Reconfirmado hoy, mencionado nuevamente como **agotado** (igual que el 10-08). Cifra idéntica a la conocida. **Sin cambio.** No alcanza la meta. | WebSearch (extendido) |
| Tu360Compras (Bancolombia) | $4.170.903 (precio de lista $4.299.900, 3% dcto.) | Reconfirmado hoy citando la URL exacta de tu360compras.grupobancolombia.com. Cifra idéntica a entradas anteriores. **Sin cambio.** No alcanza la meta. | WebSearch (extendido) |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Reconfirmado hoy vía `site:alkosto.com`, mismo código de producto (711719595700). **Sin cambio.** | WebSearch (`site:alkosto.com`) |
| Ktronix | Sin precio (**producto agotado / sin stock**) | Reconfirmado hoy vía `site:ktronix.com`, mismo código de producto. **Sin cambio.** | WebSearch (`site:ktronix.com`) |
| Operación Sistémica ⚠️ | $4.148.900 (precio de lista $5.927.000, ~30% dcto.) | Cifra idéntica a la última conocida, pero el snippet de hoy sugiere que esta oferta podría haber vencido el 30-07-2026 — **sin confirmación independiente**, posible dato obsoleto. Se mantiene con la misma advertencia de precio "ancla" inflado de entradas anteriores, más esta nueva señal de posible vencimiento, pendiente de verificación manual. | WebSearch (extendido) |
| *Falabella (ficha oficial Sony, producto 137865821/137865822, "Digital PRO 2TB")* | Sin cifra confiable (**agotado**, con menciones ambiguas de $3.699.900 y $4.299.900 sin precisar cuál aplica) | **No es la SKU 145535455/145535456 ya monitoreada** — es una ficha de producto distinta. Se descarta por no ser una cifra clara/confiable, siguiendo el mismo criterio de cautela de entradas anteriores ante datos contradictorios de Falabella. No se registra como cambio. | WebSearch (extendido, descartado) |
| Sony Store Colombia | Sin reconfirmar hoy (última cifra conocida: $4.399.804, precio de lista $4.599.900, 2026-10-06) | Ninguna búsqueda de hoy (general ni `site:`) devolvió snippet propio de `store.sony.com.co`. WebFetch directo también bloqueado. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Enjoy VideoGames | Sin reconfirmar hoy (última cifra conocida: $3.699.000, producto agotado, 2026-10-08) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Cadena Multi | Sin reconfirmar hoy (última cifra conocida: $3.850.000, precio de lista $4.400.000, ~12,5% dcto., 2026-10-05) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Éxito | Sin precio confiable hoy (sin reconfirmar) | Ninguna búsqueda de hoy (general ni `site:exito.com`) devolvió snippet propio del dominio. **No se registra cifra — no inventada.** | — (sin snippet propio hoy) |

**Comparación con la entrada anterior (2026-10-08, retailer por retailer):**
- Mercado Libre (MCO43294311): $3.589.900 (28% dcto.) → $3.589.900 (28% dcto.) (**sin cambio**).
- Falabella (SKU 145535455/456): $4.139.900 (17% dcto.) → $4.139.900 (17% dcto.) (**sin cambio**).
- Colombian UP: $3.950.000 (~12,2% dcto.) → $3.950.000 (~12,2% dcto.) (**sin cambio**).
- Gameplay Colombia: $4.299.900 agotado → $4.299.900 agotado (**sin cambio**).
- Tu360Compras: $4.170.903 (3% dcto.) → $4.170.903 (3% dcto.) (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Ktronix: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Operación Sistémica: $4.148.900 (~30% dcto.) → $4.148.900 (~30% dcto.), con nueva señal no confirmada de posible vencimiento de la oferta (**sin cambio registrable, solo advertencia adicional**).
- Falabella ficha oficial Sony (137865821/137865822): no se había registrado antes como entrada separada → aparece hoy como agotada con cifras ambiguas, descartada por no confiable (**no se considera retailer/listado nuevo confirmado**, sigue el mismo SKU "Falabella" ya monitoreado por otra ficha).
- Sony Store, Enjoy VideoGames, Cadena Multi, Éxito: sin reconfirmar hoy (**sin evidencia de variación**; se mantienen como referencia).
- Retailers nuevos: ninguno. Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer con dato confiable hoy (Mercado Libre, Falabella, Colombian UP, Gameplay Colombia, Tu360Compras, Alkosto y Ktronix reconfirman exactamente sus últimas cifras conocidas). Ningún retailer con dato confiable hoy alcanza por primera vez la meta del usuario; Mercado Libre sigue cumpliéndola pero sin cambio y ya reportado el 10-02. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo y confirmado hoy — la ficha "oficial" distinta de Falabella y la posible expiración de la oferta de Operación Sistémica quedan señaladas pero sin confirmación independiente suficiente para considerarse novedades reales. Se obtuvo al menos un dato confiable hoy (Mercado Libre, Falabella, Colombian UP, Gameplay Colombia, Tu360Compras, Alkosto y Ktronix reconfirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**

---

## 2026-10-10

**Intentos de acceso:** Google Shopping (`udm=28`, ambas queries indicadas en el prompt: "PS5 Pro Digital 2TB Colombia" y "sony ps5 pro") → bloqueado (`getaddrinfo ENOTFOUND www.google.com`, mismo patrón que `EGRESS_BLOCKED` de días anteriores). WebFetch directo a `store.sony.com.co/ps5-pro-hw-2tb/p` y `www.alkosto.com/consola-ps5-pro-digital-2-tb-blanco-1-control-inalambrico/p/711719595700` → ambos bloqueados (`getaddrinfo ENOTFOUND`). Se usó **WebSearch** de respaldo (modo estándar y extendido) con una consulta general y dirigidas por retailer (`site:` para Mercado Libre, Falabella, Colombian UP, Sony Store, Alkosto, Ktronix, Enjoy VideoGames, Éxito) y búsquedas de nombre libre para Tu360Compras, Operación Sistémica, Cadena Multi y Gameplay Colombia.

**Nota de calidad de datos:** la búsqueda extendida general ("PS5 Pro Digital 2TB precio Colombia octubre 2026") reconfirmó con cifras idénticas a Mercado Libre (MCO43294311), Gameplay Colombia, Enjoy VideoGames y Cadena Multi, y mencionó un rango agregado y ambiguo ("COP 3.699.900 a COP 4.299.900") para "Sony Colombia (Falabella)" sin precisar a cuál de las dos fichas de Falabella (la SKU 145535455/145535456 ya monitoreada, o la ficha oficial Sony 137865821/137865822) corresponde — siguiendo el mismo criterio de cautela de entradas anteriores ante cifras ambiguas de Falabella, **se descarta esta cifra y se mantiene la última cifra confiable conocida de la SKU principal ($4.139.900, 17% dcto., 2026-10-09) como referencia sin reconfirmar**. La búsqueda `site:falabella.com.co` sí devolvió, de forma reproducible, el listado de marketplace ya visto el 10-08 del vendedor "Rxggames" para un listado separado "Digital 2TB", ahora a **$4.599.900** (antes $4.699.900 el 10-08) sobre un precio de lista de $5.999.000 (**23% dcto.**, antes 21,7%) — se registra con la misma cautela de entradas anteriores, sin mezclarlo con la SKU principal de Falabella por tratarse de un vendedor/listado distinto. Las búsquedas `site:alkosto.com` y `site:ktronix.com` reconfirmaron explícitamente el estado "Producto agotado" para el código 711719595700 en ambas tiendas (sin precio, mismo código que entradas previas). Colombian UP, Sony Store Colombia, Tu360Compras y Operación Sistémica no devolvieron ningún snippet propio del dominio exacto con precio hoy (ni con `site:` ni con búsqueda de nombre libre) — se mantienen con su último valor conocido como referencia, sin evidencia de variación. Éxito, como en entradas anteriores, no devolvió ningún snippet propio del dominio — no se registra cifra.

| Retailer | Precio COP | Oferta/nota | Fuente |
|---|---|---|---|
| Mercado Libre (MCO43294311) | **$3.589.900** (precio de lista $5.014.143, **28% dcto.**) | Reconfirmado hoy en la búsqueda general citando el listing exacto. Cifra idéntica a entradas anteriores. **Sin cambio.** **Sigue cumpliendo la meta del usuario**, ya reportada el 10-02. | WebSearch (extendido; WebFetch directo bloqueado) |
| Gameplay Colombia | $4.299.900 (precio de lista $4.499.900, ~4,4% dcto.) | Reconfirmado hoy, mencionado nuevamente como **agotado** (igual que el 10-08/10-09). Cifra idéntica a la conocida. **Sin cambio.** No alcanza la meta. | WebSearch (extendido) |
| Enjoy VideoGames | $3.699.000 (**producto agotado / sin stock**) | Reconfirmado hoy en la búsqueda general. Cifra idéntica a la última conocida. Sigue sin disponibilidad real. **Sin cambio.** | WebSearch (extendido) |
| Cadena Multi | $3.850.000 (oferta; precio de lista no reconfirmado hoy, último conocido $4.400.000, ~12,5% dcto.) | Reconfirmado hoy en la búsqueda general para la versión "+1 control". Cifra de oferta idéntica a la última conocida. **Sin cambio.** No alcanza la meta. | WebSearch (extendido) |
| Alkosto | Sin precio (**producto agotado / sin stock**) | Reconfirmado hoy vía `site:alkosto.com`, mismo código de producto (711719595700). **Sin cambio.** | WebSearch (`site:alkosto.com`) |
| Ktronix | Sin precio (**producto agotado / sin stock**) | Reconfirmado hoy vía `site:ktronix.com`, mismo código de producto. **Sin cambio.** | WebSearch (`site:ktronix.com`) |
| *Falabella Marketplace ("Rxggames", listado "Digital 2TB" separado)* | $4.599.900 (precio de lista $5.999.000, ~23% dcto.) | **No es la SKU 145535455/145535456 ya monitoreada** — listado de marketplace distinto, ya visto el 10-08 a $4.699.900/21,7% dcto. Baja hoy de ~2,1% frente al 10-08, muy por debajo del umbral de notificación. Pendiente de verificación manual antes de considerarlo una oportunidad real; no se mezcla con la cifra oficial de Falabella. | WebSearch (`site:falabella.com.co`) |
| Falabella (SKU 145535455/145535456) | Sin reconfirmar hoy (última cifra conocida: $4.139.900, precio de lista $4.299.900, 17% dcto., 2026-10-09) | La búsqueda general de hoy solo citó un rango ambiguo ($3.699.900–$4.299.900) sin precisar la ficha exacta; se descarta por no confiable, siguiendo el criterio de cautela habitual ante datos contradictorios de Falabella. Se mantiene el último valor conocido como referencia. | — (dato de hoy descartado por ambiguo) |
| Colombian UP | Sin reconfirmar hoy (última cifra conocida: $3.950.000, precio de lista $4.500.000, ~12,2% dcto., 2026-10-09) | El enlace del producto apareció en la búsqueda general, pero sin snippet de precio asociado. Se mantiene como referencia sin reconfirmar. | — (sin snippet de precio hoy) |
| Sony Store Colombia | Sin reconfirmar hoy (última cifra conocida: $4.399.804, precio de lista $4.599.900, 2026-10-06) | Ninguna búsqueda de hoy (general ni `site:store.sony.com.co`) devolvió snippet propio de `store.sony.com.co`. WebFetch directo también bloqueado. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Tu360Compras (Bancolombia) | Sin reconfirmar hoy (última cifra conocida: $4.170.903, precio de lista $4.299.900, 3% dcto., 2026-10-09) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar. | — (sin snippet propio hoy) |
| Operación Sistémica ⚠️ | Sin reconfirmar hoy (última cifra conocida: $4.148.900, precio de lista $5.927.000, ~30% dcto., 2026-10-09 — con advertencia de posible precio "ancla" inflado y posible vencimiento de la oferta, pendiente de verificación manual) | No se encontró snippet propio del dominio hoy. Se mantiene como referencia sin reconfirmar, con la misma advertencia de entradas anteriores. | — (sin snippet propio hoy) |
| Éxito | Sin precio confiable hoy (sin reconfirmar) | Ninguna búsqueda de hoy (general ni `site:exito.com`) devolvió snippet propio del dominio. **No se registra cifra — no inventada.** | — (sin snippet propio hoy) |

**Comparación con la entrada anterior (2026-10-09, retailer por retailer):**
- Mercado Libre (MCO43294311): $3.589.900 (28% dcto.) → $3.589.900 (28% dcto.) (**sin cambio**).
- Falabella (SKU 145535455/456): $4.139.900 (17% dcto.) → sin reconfirmar hoy, cifra general ambigua descartada (**sin evidencia de variación confiable**; se mantiene la última cifra conocida como referencia).
- Falabella Marketplace (Rxggames): $4.699.900 (~21,7% dcto., visto el 10-08, no mencionado el 10-09) → $4.599.900 (~23% dcto.) hoy (**baja de ~2,1%**, muy por debajo del umbral de notificación; listado no oficial, no monitoreado como SKU principal).
- Gameplay Colombia: $4.299.900 agotado → $4.299.900 agotado (**sin cambio**).
- Enjoy VideoGames: sin reconfirmar el 10-09 (última cifra 10-08: $3.699.000 agotado) → $3.699.000 agotado reconfirmado hoy (**sin cambio real**).
- Cadena Multi: sin reconfirmar desde el 10-05 ($3.850.000, ~12,5% dcto.) → $3.850.000 reconfirmado hoy (**sin cambio**).
- Alkosto: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Ktronix: agotado/sin precio → agotado/sin precio (**sin cambio**).
- Colombian UP: $3.950.000 (~12,2% dcto., confirmado 10-09) → sin reconfirmar hoy (**sin evidencia de variación**; se mantiene como referencia).
- Tu360Compras: $4.170.903 (3% dcto., confirmado 10-09) → sin reconfirmar hoy (**sin evidencia de variación**).
- Operación Sistémica: $4.148.900 (~30% dcto., confirmado 10-09) → sin reconfirmar hoy (**sin evidencia de variación**; se mantiene con la misma advertencia).
- Sony Store, Éxito: sin reconfirmar hoy (**sin evidencia de variación**; se mantienen como referencia).
- Retailers nuevos: ninguno confirmado de forma independiente (el listado de marketplace "Rxggames" en Falabella no es nuevo, ya visto el 10-08). Retailers desaparecidos: ninguno.

**Conclusión de hoy:** No se detectó ninguna bajada de precio ≥10% en ningún retailer con dato confiable hoy (Mercado Libre, Gameplay Colombia, Enjoy VideoGames, Cadena Multi, Alkosto y Ktronix reconfirman exactamente sus últimas cifras conocidas; la baja de ~2,1% del listado de marketplace "Rxggames" en Falabella no monitoreado como SKU principal queda muy por debajo del umbral). Ningún retailer con dato confiable hoy alcanza por primera vez la meta del usuario; Mercado Libre sigue cumpliéndola pero sin cambio y ya reportado el 10-02. No apareció ningún retailer, bundle, cupón o cambio de disponibilidad genuinamente nuevo y confirmado hoy. Se obtuvo al menos un dato confiable hoy (Mercado Libre, Gameplay Colombia, Enjoy VideoGames, Cadena Multi, Alkosto y Ktronix reconfirmados), por lo que no aplica la condición de "2 días seguidos sin datos confiables de NINGÚN retailer". **No se cumplió ninguna condición de notificación.**
