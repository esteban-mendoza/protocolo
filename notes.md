# Notas

## Métricas

| Métrica | Propósito | Justificación en benchmarks |
| :-- | :-- | :-- |
| nDCG@10 | Calidad del ranking (primaria) | BEIR, MTEB, MIRACL, MessIRve, TREC DL |
| Recall@100 | Cobertura de la etapa de recuperación | MIRACL, MessIRve, Mr. TyDi |
| MRR@10 | Utilidad del primer resultado | MS MARCO, Mr. TyDi |
| MAP | Calidad del reranking | MTEB (tarea de reranking) |
| P@k para k∈{10,50}k \in \{10, 50\} | Análisis de decaimiento de precisión | TREC DL, TREC-COVID |

## Cambios

- Agrega estructura aproximada del apartado matemático. Discute con la Dra.
- Explicar que vamos a comparar algoritmos de fusión contra rerankers (cross-encoders y late-interaction).
