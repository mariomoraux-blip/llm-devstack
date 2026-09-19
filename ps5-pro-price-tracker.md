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
