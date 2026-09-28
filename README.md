# DC-LABORATORY — Catálogo OBD2 en español

Sitio estático React/Vite basado en la página de referencia de OBD2 PID Knowledge, personalizado para DC-LABORATORY con logo propio, imágenes adjuntas y paleta naranja/celeste.

## Incluye

- Catálogo completo de 252 PIDs en Mode 01, 02, 05, 06 y 09.
- Sección **Normas y servicios**: SAE J1962, J1979, J2012, J2190, ISO 15765, UDS y 19 modos/servicios OBD/UDS.
- Sección **Señales**: 35 señales semánticas de motor, batería HV, inversores, carga y operación.
- Sección **Plataformas**: 59 familias de vehículos HEV/PHEV.
- Sección **Adaptadores**: ELM327, OBDLink/STN, UniCarScan y Vgate/vLinker.
- Sección **Apps**: Car Scanner, Dr. Prius, Hybrid Assistant, OBD Fusion, OBDLink, PHEV Watchdog y Torque Pro.
- **Búsqueda global** por PIDs y secciones.
- Filtros, feedback, navegación responsive y estados vacíos.

## Ejecutar localmente

```bash
pnpm install
pnpm dev
```

## Compilar

```bash
pnpm build
pnpm start
```

Los cinco recursos visuales están en `client/public/assets/`. El código también conserva paths de almacenamiento de WebDev con fallback local, por lo que el paquete es autocontenido para GitHub.
