# FilaClub

Maqueta de un marketplace chileno de compras con beneficios. **Demo · Sin pagos reales**. Los precios, los pedidos y las personas son ficticios.

## Abrir y probar

Abre `index.html` en el navegador. El avance queda guardado en `localStorage`. **Reiniciar demo**, al pie, restaura las salas y la cola inicial.

- **Compra.** Usa el producto de ejemplo y busca una sala. El sistema salta la sala CMR de Vale porque su límite no cubre el adelanto y asigna la de Nico. Usa **Cambiar perspectiva** para completar los pasos de ambas personas. Para probar la confirmación adicional, ingresa un máximo de $95.000 antes de buscar.
- **Anfitrión.** Abre una sala de **Mi Club Lider** con retiro o despacho y un límite de $50.000. Recibirás la primera solicitud compatible de la cola. Puedes aceptarla o dejarla pasar para recibir la siguiente.

## Publicar en GitHub Pages

1. Sube `index.html`, `assets/`, `.nojekyll` y este README a la rama `main` de un repositorio dedicado al piloto.
2. En **Settings → Pages → Deploy from a branch**, selecciona `main` y `/(root)`. Presiona **Save**.
3. Cuando termine el despliegue, abre la URL que muestra **Settings → Pages**.
