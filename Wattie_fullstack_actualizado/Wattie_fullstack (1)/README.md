# Wattie

Proyecto demostrativo de lectura y escritura de historias.

## Frontend

- React + Vite
- Diseño oscuro con acentos rosados
- Autenticación demostrativa con `localStorage` (no es seguridad real ni debe usarse para cuentas reales)
- Registro, inicio/cierre de sesión y persistencia al recargar
- Historias de ejemplo, biblioteca/favoritos e historias creadas localmente
- Portadas con imagen de respaldo SVG local

### Ejecutar localmente

```bash
cd frontend
npm install
npm run dev
```

### Compilar para Vercel

Configura el Root Directory como `Wattie_fullstack (1)/frontend` si mantienes la carpeta contenedora en GitHub, Framework Preset `Vite`, Build Command `npm run build` y Output Directory `dist`.

La autenticación y el contenido creado se guardan únicamente en el navegador del usuario mediante `localStorage`. Los datos no se sincronizan entre dispositivos ni usuarios. El backend y el esquema SQL se conservan como material de referencia académica, pero el frontend de demostración no realiza peticiones a ellos.
