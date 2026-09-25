# Áurea · contenido

Textos que la app Áurea descarga para corregirse sin pasar por la App Store.

- `produccion/manifest.json` y `pruebas/manifest.json`: la publicación vigente de cada canal, firmada con Ed25519 (`manifest.json.sig`).
- `packs/`: los archivos de contenido, nombrados por su SHA-256.

Se genera con `tools/ota/publicar.py` en el repositorio de la app. No editar a mano: la firma dejaría de ser válida.
