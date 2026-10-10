# MiFlow — actualizaciones

Este repositorio solo sirve para que las copias instaladas de **MiFlow** se mantengan al día:

- `miflow.json`: configuración remota (textos de la web de Flow por idioma, avisos y la última versión disponible).
- `miflow.json.sig`: firma Ed25519 de `miflow.json`. MiFlow ignora cualquier configuración cuya firma no sea válida.
- **Releases**: cada versión de `MiFlow.exe`. MiFlow comprueba su SHA-256 antes de instalarla.

No contiene datos de ningún usuario.
