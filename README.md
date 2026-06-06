# Sistema Integral de Adquisiciones

Aplicacion web local para el control de expedientes de contratacion y requisiciones.

## Uso

Abre `index.html` en el navegador.

El sistema guarda informacion en el almacenamiento local del navegador (`localStorage`). Para trabajar desde distintas maquinas, exporta el respaldo JSON desde el sistema y despues importalo en la otra maquina.

## Publicacion en GitHub Pages

1. Sube el contenido de esta carpeta al repositorio `HakfuGames/Sistema-Integral-de-Adquisiciones`.
2. En GitHub, entra a `Settings > Pages`.
3. En `Build and deployment`, selecciona `Deploy from a branch`.
4. Elige la rama `main` y la carpeta `/root`.
5. Guarda los cambios.

GitHub publicara el sistema usando `index.html`.

## Archivos principales

- `index.html`: sistema completo.
- `FORMATO_DE_REQUISICION_2026.docx`: plantilla de requisicion.
- `FORMATO_CARGA_PARTIDAS.xml` y `formato_carga_masiva_partidas_requisicion.xml`: formatos de carga.
- Catalogos y documentos de apoyo incluidos en la carpeta raiz.
