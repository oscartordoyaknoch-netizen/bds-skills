# BDS Skills

Repositorio portable para distribuir skills del `Business Design System`.

## Skill incluida

- `skills/bds-core`

- ## Que es `bds-core`

- `bds-core` es la skill madre doctrinal y arquitectonica del BDS. Sirve para:

- - interpretar un negocio como sistema vivo
  - - clasificar problemas y oportunidades dentro de la arquitectura BDS
    - - distinguir documento madre, workspace, componentes, caso y agente
      - - decidir el artefacto minimo util que debe producirse
        - - proteger evidencia, trazabilidad y learning
         
          - ## Estructura
         
          - ```text
            skills/
              bds-core/
                SKILL.md
                agents/
                  openai.yaml
                references/
            ```

            ## Instalacion desde GitHub

            Si este repositorio se publica en GitHub y la skill queda en:

            `https://github.com/<owner>/<repo>/tree/main/skills/bds-core`

            la instalacion esperada es:

            ```text
            install-skill-from-github.py --url https://github.com/<owner>/<repo>/tree/main/skills/bds-core
            ```

            ## Compatibilidad

            `bds-core` funciona sola en modo conceptual y manual.

            Si existe una skill operativa complementaria como `bds-operator`, puede derivar hacia ella para:

            - ingestion documental
            - - automatizacion repetible
              - - generacion masiva
                - - auditoria operativa
                 
                  - ## Nota
                 
                  - Despues de instalar una skill nueva en Codex, conviene reiniciar la aplicacion para asegurar su deteccion.
                  - 
