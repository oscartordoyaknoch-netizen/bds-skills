# Compatibility

## Con bds-operator

`bds-core` y `bds-operator` no compiten.

- `bds-core` piensa, clasifica, estructura y protege doctrina.
- - `bds-operator` ejecuta ingestiones, usa scripts, genera artefactos repetibles, audita y exporta.
 
  - Si la tarea requiere:
 
  - - preservacion sistematica de fuentes
    - - procesamiento repetible
      - - auditoria de salidas
        - - generacion en lote
          - - exportaciones operativas
           
            - entonces conviene derivar a `bds-operator` si esta disponible.
           
            - Si `bds-operator` no existe, `bds-core` debe seguir funcionando en modo conceptual y manual.
           
            - ## Con Obsidian y Horus
           
            - Si existe una memoria o vault activo:
           
            - - conectar outputs a evidencia, caso, nota madre o workspace cuando aporte valor
              - - evitar duplicados si ya hay nodo canonico
                - - mantener trazabilidad
                 
                  - Si no existe memoria o vault:
                 
                  - - operar igual como skill portable
                    - - producir estructura conceptual, clasificacion y artefactos sugeridos sin depender de rutas locales
                     
                      - ## Con skills de intake documental
                     
                      - Si el usuario pide absorcion completa a memoria, procesamiento documental o ingestion a vault:
                     
                      - - `bds-core` define criterio y artefactos
                        - - una skill de intake o sync puede encargarse de la entrada fisica y conexion en memoria
                         
                          - ## Limite de esta skill
                         
                          - Esta skill no debe depender de:
                         
                          - - una ruta fija local
                            - - scripts locales obligatorios
                              - - un repo local especifico
                                - - una sola instalacion de Obsidian
                                 
                                  - Debe poder instalarse desde GitHub y seguir teniendo sentido autonomo.
                                  - 
