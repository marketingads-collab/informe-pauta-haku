# Informe de pauta — Haku

Informe de costo por lead por zona. Se regenera desde la API de Meta con los
scripts de `~/.local/bin/` (`pull_datos_pauta_haku.py` + `build_informe_html.py`).

`index.html` es un archivo autocontenido: no consulta ninguna API al abrirse.
Para actualizarlo se reemplaza el archivo y se hace push.
