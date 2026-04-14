# Notas

## Métricas

| Métrica | Propósito | Justificación en benchmarks |
| :-- | :-- | :-- |
| nDCG@10 | Calidad del ranking (primaria) | BEIR, MTEB, MIRACL, MessIRve, TREC DL |
| Recall@100 | Cobertura de la etapa de recuperación | MIRACL, MessIRve, Mr. TyDi |
| MRR@10 | Utilidad del primer resultado | MS MARCO, Mr. TyDi |
| MAP | Calidad del reranking | MTEB (tarea de reranking) |
| P@k para k∈{10,50}k \in \{10, 50\} | Análisis de decaimiento de precisión | TREC DL, TREC-COVID |

## Citas

| Alias en el .bib | Referencia real |
| :-- | :-- |
| thakur2021beirheterogenousbenchmarkzeroshot | Thakur et al., BEIR: A Heterogeneous Benchmark for Zero-shot Evaluation of Information Retrieval Models, NeurIPS 2021 — ya lo tienes |
| muennighoff2023mteb | Muennighoff et al., MTEB: Massive Text Embedding Benchmark, EACL 2023 |
| zhang2023miracl | Zhang et al., MIRACL: A Multilingual Retrieval Dataset Covering 18 Diverse Languages, TACL 2023 |
| valentini-etal-2025-messirve | Valentini et al., 2025 — ya lo tienes |
| craswell2020overview | Craswell et al., Overview of the TREC 2019 Deep Learning Track, TREC 2020 |
| nguyen2016msmarco | Nguyen et al., MS MARCO: A Human Generated MAchine Reading COmprehension Dataset, NeurIPS Workshop 2016 |
| zhang2021mrtydi | Zhang et al., Mr. TyDi: A Multi-lingual Benchmark for Dense Retrieval, 2021 |
| voorhees2021treccovid | Voorhees et al., TREC-COVID: Constructing a Pandemic Information Retrieval Test Collection, SIGIR Forum 2021 |
