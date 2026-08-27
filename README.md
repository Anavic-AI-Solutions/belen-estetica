# Belén Ojeda — Estética y Energía

Landing page estática (HTML/CSS/JS puro, sin build) lista para desplegar en Vercel.

## Estructura
```
belen-estetica-web/
├── index.html
└── images/
    ├── logo.jpg
    ├── ailu.jpg
    ├── ambiente-masajes.jpg
    └── ambiente-unas.jpg
```

## Deploy en Vercel
**Opción 1 — Drag & drop:** en vercel.com → "Add New Project" → arrastrá la carpeta `belen-estetica-web` completa. No requiere build command ni framework (dejar como "Other").

**Opción 2 — CLI:**
```bash
cd belen-estetica-web
vercel deploy --prod
```

## Pendientes para actualizar más adelante
- **Horarios:** hoy dice "Consultá disponibilidad por WhatsApp" (sección Contacto). Reemplazar cuando esté definida la grilla de días/horarios.
- **Dirección exacta:** intencionalmente no está publicada (solo "El Palomar, Morón, Buenos Aires"), tal como pide el negocio — se comparte por WhatsApp al confirmar el turno.
- **WhatsApp:** el número y el mensaje predefinido están centralizados en `index.html`, al final, dentro de `<script>` (`WA_NUMBER` y `WA_MESSAGE`).
- **Más fotos/equipo:** cuando sumen más profesionales o trabajos terminados, se pueden agregar a `images/` y sumar tarjetas en la sección "Equipo" o una galería.
