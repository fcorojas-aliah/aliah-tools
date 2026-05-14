# Aliah Lomas Verdes — Herramientas de Showroom

Dos herramientas interactivas para el equipo comercial de Aliah Lomas Verdes.

## Herramientas

### 📊 Calculadora de Rentabilidad
- Precios Mappen reales con 10% descuento
- Cap rate vs CETES, S&P 500, zona
- Proyección 1, 3 y 5 años (plusvalía 7% + renta)
- Caso documentado: C2 Torre A a $23,000/mes

### 🔍 Decide con Todo
- 28 proyectos de la zona (EDM Monopolio, marzo 2026)
- Tabla interactiva con ordenamiento y filtros
- Comparativa automática vs Aliah
- Absorción, precio/m², plusvalía, inventario

## Instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/TU-USUARIO/aliah-tools.git
cd aliah-tools

# 2. Instalar dependencias
npm install

# 3. Desarrollo local
npm run dev

# 4. Build para producción
npm run build

# 5. Deploy a GitHub Pages
npm run deploy
```

## Configuración GitHub Pages

1. En GitHub, ve a Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: `gh-pages` / `/ (root)`
4. La URL será: `https://TU-USUARIO.github.io/aliah-tools/`

## Uso en iPad (PWA)

1. Abrir la URL en Safari
2. Tap en el ícono de compartir (cuadrado con flecha)
3. "Agregar a pantalla de inicio"
4. Se instala como app nativa con ícono de Aliah
5. Funciona offline después de la primera carga

## Actualizar precios

Los precios están en `src/data/prototypes.js`. Para actualizar:

1. Editar el archivo con los nuevos precios Mappen
2. `git commit` + `git push`
3. `npm run deploy`

Los competidores están en `src/data/competitors.js`.

## Notas importantes

- Los precios Mappen están ~12% inflados vs precio real de cierre
- Se muestra 10% descuento como "precio promocional"
- NUNCA mencionar el 2% adicional de negociación del asesor
- No incluye esquemas financieros — eso lo maneja Mappen

## Fuentes

- EDM Monopolio/DD360, marzo 2026
- Opinión de Valor 4S Real Estate, marzo 2025
- MM Aliah LV v28.2 (pestaña MAPPEN 01mzo)

## Íconos PWA

Reemplazar `public/icon-192.png` y `public/icon-512.png` con el ícono de Aliah en esas resoluciones.

---
*Aliah Developments © 2026 — Uso exclusivo equipo comercial*
