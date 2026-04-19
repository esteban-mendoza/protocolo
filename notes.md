# Notas

## Métricas

| Métrica                            | Propósito                             | Justificación en benchmarks           |
| :--------------------------------- | :------------------------------------ | :------------------------------------ |
| nDCG@10                            | Calidad del ranking (primaria)        | BEIR, MTEB, MIRACL, MessIRve, TREC DL |
| Recall@100                         | Cobertura de la etapa de recuperación | MIRACL, MessIRve, Mr. TyDi            |
| MRR@10                             | Utilidad del primer resultado         | MS MARCO, Mr. TyDi                    |
| MAP                                | Calidad del reranking                 | MTEB (tarea de reranking)             |
| P@k para k∈{10,50}k \in \{10, 50\} | Análisis de decaimiento de precisión  | TREC DL, TREC-COVID                   |

## Cambios

- Agrega estructura aproximada del apartado matemático. Discute con la Dra
  - Marco de relevancia probabilística
  - Pearson 1901
  - Hipótesis de la variedad
  - Johnson–Lindenstrauss lemma
  - Testing the manifold hypothesis CHARLES FEFFERMAN, SANJOY MITTER, AND HARIHARAN NARAYANAN
  - The Origins of Representation Manifolds in Large Language Models Alexander Modell, Patrick Rubin-Delanchy, Nick Whiteley
  - Statistical exploration of the Manifold Hypothesis Nick Whiteley, Annie Gray, Patrick Rubin-Delanchy
