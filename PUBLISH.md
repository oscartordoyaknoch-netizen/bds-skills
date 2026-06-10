# Publicacion de `bds-core`

## Carpeta lista para subir

Sube el contenido de esta carpeta como repositorio git:

`dist/bds-skills`

## Ruta esperada

La ruta final recomendada es:

```text
<repo>/
  skills/
    bds-core/
```

## Enlace de instalacion

Cuando el repositorio este publicado en GitHub, el enlace esperado para instalar la skill sera:

```text
https://github.com/<owner>/<repo>/tree/main/skills/bds-core
```

y el comando:

```text
install-skill-from-github.py --url https://github.com/<owner>/<repo>/tree/main/skills/bds-core
```

## Lo que ya esta resuelto aqui

- la skill es autocontenida
- - no depende de rutas locales para su funcionamiento base
  - - incluye metadata en `agents/openai.yaml`
    - - incluye referencias doctrinales internas en `references/`
     
      - ## Lo que falta fuera de Codex
     
      - - crear o elegir un repositorio remoto
        - - subir esta carpeta a ese repo
          - - compartir el link final de `skills/bds-core`
            - 
