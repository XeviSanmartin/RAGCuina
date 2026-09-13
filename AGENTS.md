# Arnès del Projecte RAGCuina

## Objectiu

Construir un sistema RAG local sobre els llibres de cuina de la carpeta `docs/`.
El sistema ha d'utilitzar LanceDB mitjançant l'MCP `mcp-local-rag`, disposar d'un
agent especialitzat i oferir una interfície web estàtica local.

## Estructura prevista

- `docs/`: fonts originals dels llibres de cuina.
- `.rag/lancedb/`: base de dades vectorial de LanceDB.
- `.rag/models/`: memòria cau dels models d'embeddings.
- `.opencode/agent/`: agents especialitzats.
- `web/`: interfície web estàtica local.

## Normes de treball

1. No modificar ni esborrar mai els fitxers originals de `docs/`.
2. No sobreescriure configuracions existents: cal integrar-hi els canvis.
3. No tocar altres MCPs ni configuracions que ja existeixin.
4. Instal·lar només les dependències estrictament necessàries i no fer instal·lacions globals.
5. Verificar cada pas amb una comanda abans de donar-lo per acabat.
