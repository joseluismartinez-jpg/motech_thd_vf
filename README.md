# The Home Depot · Marketplace vs Open Exchange

Reporte ejecutivo interactivo de desempeño programmatic en **DV360** para The Home Depot México, elaborado por **MOTECH by Havas**.

Analiza la evaluación del **Marketplace de Motech (PMP)** frente al **Open Exchange** durante abril–junio 2026, el impacto del periodo de **Hot Sale**, el **costo por sesión**, y propone una **reestructura de audiencias y de estructura de campañas**.

## 🔗 Ver el reporte

Una vez activado GitHub Pages (ver abajo), el reporte queda disponible en:

```
https://<tu-usuario>.github.io/<nombre-del-repo>/
```

## 📊 Contenido del reporte

1. **Resumen ejecutivo** — diagnóstico y KPIs clave (CPS, CPM ponderado, mezcla de audiencias).
2. **Consumo semanal y estabilidad del CPM ponderado** — tendencia semanal MP vs Open (Abr–Jun) y evolución del CPM ponderado total.
3. **¿Es más caro MP?** — CPM ponderado vs promedio por línea, viewability y optimización vía control de puja.
4. **Sesiones GA4 vs Floodlight** — señal de optimización y costo por sesión.
5. **Audiencias** — qué es "Other-Audiences", qué funciona y qué no.
6. **Plan de estructura de campañas y next steps** — arquitectura de 3 capas (Núcleo 1P · Intención · Volumen).

## 🚀 Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `thd-marketplace-reporte`).
2. Sube estos archivos a la rama `main`:
   - `index.html`
   - `README.md`
3. Ve a **Settings → Pages**.
4. En **Source**, selecciona la rama `main` y la carpeta `/ (root)`.
5. Guarda. En 1–2 minutos el sitio queda publicado en la URL de arriba.

> El archivo `index.html` es totalmente **self-contained**: incluye el logo, los estilos y los gráficos (SVG) embebidos. No requiere librerías, CDN ni conexión externa, por lo que carga instantáneo y funciona offline.

## 📁 Estructura

```
.
├── index.html      # Reporte ejecutivo (abrir en navegador)
└── README.md       # Este archivo
```

## 🗂️ Fuentes y metodología

- **DV360 Performance** (diario, Abr–Jun 2026, con viewability real) — comparativa Public vs Private Exchange.
- **Tabla dinámica TD_Resumen** — costos y CPM por inventario y mes.
- **Google Analytics 4** — sesiones, sesiones con interacción y eventos clave por IO/Line Item.
- **Audience Lists** (BNO · HRR · MSP · PNT · PSO) — composición de segmentos por categoría.

Notas de cálculo:
- **CPM ponderado** = costo / impresiones.
- **CPM promedio por línea** = promedio de eCPM a nivel línea (metodología de la tabla dinámica).
- La ventana de evaluación de MP (~10 días) coincidió con **Hot Sale**, periodo en el que toda la subasta se encarece.

## 🔒 Confidencialidad

Este documento contiene datos de inversión y desempeño de una cuenta de cliente. Si la información es sensible, considera usar un **repositorio privado** o **GitHub Pages con acceso restringido**, en lugar de un repositorio público.

---

Preparado para **The Home Depot** · **MOTECH by Havas México**
