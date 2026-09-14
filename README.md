# Het Patel

AI systems engineer in training. M.Sc. Applied AI at TU Dresden (avg 1.5), working student at a Dresden AI startup. I build the layer around LLM and ML systems that decides whether you can trust them: retrieval, structured extraction, evaluation gates, tracing, and data pipelines that survive a handover.

Open to a **30-ECTS master's thesis in industry** (late 2026 / early 2027) in AI systems or ML infrastructure preferrably.

## Works I've done

**[EchoClaim](https://github.com/IamHetPatel/EchoClaim)** · voice claims-intake agent with grounded retrieval (Big Berlin Hack 2.0)
Python · FastAPI · LiveKit/Twilio · Gemini 2.5 Flash · GLiNER2 · Qdrant · GitHub Actions.
- Fine-tuned GLiNER2 chosen over Gemini for extraction on latency (69 ms / 0.61 F1 vs 2,729 ms / 0.86 F1). 
- Retrieval MRR 0.314 → 0.805 over BM25 on a 32-query adversarial golden set. 
- CI eval gate with tolerance bands, LLM-judge groundedness 0.703, content-hashed prompt registry, PII redaction. 
- Every number reproduces via [`docs/EVAL.md`](https://github.com/IamHetPatel/EchoClaim/blob/main/docs/EVAL.md).

**BINNVC** · structural-prior 3D EM segmentation (TU Dresden research project, team of 3)
PyTorch · MONAI · SLURM on the Capella cluster
- A differentiable adjacency-prior loss for a 3D U-Net cut floating-membrane violations from 0.41 to 0.03 with no Dice regression. 
- Component-level evaluation traced the real failure to fragmented topology; caught a duplicate-test-crop bug that was double-counting scores.

**[PatchCore anomaly detection](https://github.com/IamHetPatel/mvtec-anomaly-detection-model)** · training-free industrial defect localisation
- Frozen WideResNet-50-2, greedy coreset to ~1 % of patches, FastAPI heatmap endpoint, CPU-only. 
- 0.984–1.000 image AUROC on MVTec bottle, carpet and leather.

**[DataWhisper-AI](https://github.com/IamHetPatel/DataWhisper-AI)** · plain-English questions → MongoDB aggregation pipelines, each stage streamed over SSE (START Hack, St. Gallen)

**[API Gateway](https://github.com/IamHetPatel/API-Gateway)** · JWT auth, Redis rate limiting, response cache, Prometheus + Grafana · **[Retail Pulse](https://github.com/IamHetPatel/retail-pulse)** · Go + RabbitMQ async image processing

## Writing

- [Your RAG faithfulness check is measuring copy-paste, not faithfulness](https://dev.to/) (Jun 2026): why token-overlap faithfulness fails and what NLI entailment fixes.

## Elsewhere

Springer ACSS 2024 co-author (undergraduate NLP work) · 6+ hackathons, *Deploy on Scroll* award at EthIndia 2023 · 250+ LeetCode (Java)

hetp943@gmail.com · [LinkedIn](https://www.linkedin.com/in/iamhetpatel/)
