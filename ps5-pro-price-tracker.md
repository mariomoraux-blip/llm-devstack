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
