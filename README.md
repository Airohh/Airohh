# Sam Pondevie — Data / MLOps Engineer

Ingénieur Data & IA (EFREI Paris, 2026). Orienté production : chaque projet est déployé, testé et monitoré — rien ne reste en notebook.

## Projets par domaine

### Computer Vision (3D & 2D)

| Projet | Description | Stack |
|---|---|---|
| [PointNet — Classification 3D](https://github.com/Airohh/pointnet-3d-classifier) | Classe un objet 3D depuis sa seule géométrie (mesh CAO → nuage de points). PointNet **from scratch**, robustesse caractérisée (bruit/occlusion/rotation), ONNX + API | PyTorch, trimesh, FastAPI, ONNX, Docker |
| [Live Object Detector](https://github.com/Airohh/live-object-detector) · [démo](https://airohh.github.io/live-object-detector/) | Détection d'objets temps réel **dans le navigateur**, on-device (aucune image envoyée). PWA installable | TensorFlow.js, COCO-SSD, PWA |

### NLP / RAG / agents

| Projet | Description | Stack |
|---|---|---|
| [insight-mcp](https://github.com/Airohh/insight-mcp) | Serveur MCP retrieval-only : hybrid BM25 + dense (RRF), citations, Prometheus, Docker, CI. Pas d’inférence côté serveur | FastMCP, BM25, Fastembed, Docker |
| [Syro](https://github.com/Airohh/Syro) | Assistant RAG hybride multi-domaines — BM25 + vecteurs denses + reranking | Qdrant, FastAPI, Docker, Prometheus |
| [Fine-tuning Llama 3.3 70B](https://huggingface.co/Sam-Pdv) | QLoRA 4-bit NF4 sur A100 80GB — modèle + dataset FR publiés | Unsloth, bitsandbytes, HuggingFace |

### Time series / forecasting

| Projet | Description | Stack |
|---|---|---|
| [Prévision éolienne SDWPF](https://github.com/Airohh/sdwpf-ml-time-serie) | Séries temporelles, walk-forward, évaluation honnête vs baselines | XGBoost, MLflow, Docker, GitHub Actions |
| [Airport Forecasting](https://github.com/Airohh/airport-forecasting) | Prévision de trafic passagers (PAX) multi-aéroports | LightGBM, SARIMA, Python |

### MLOps

| Projet | Description | Stack |
|---|---|---|
| [Proths](https://github.com/Airohh/Proths) | Lab MLOps : AG News, F1 holdout 0.73, journal `/predict`, drift, promote si le F1 monte | MLflow, FastAPI, Prometheus, Grafana, Docker |

## Stack

`Python` · `SQL` · `MLflow` · `Docker` · `FastAPI` · `GitHub Actions` · `Prometheus / Grafana` · `Qdrant`

En mission (Accor / AKABI, pas de repo public) : `Snowflake` · `Terraform` · `GitLab CI` · `PySpark`

## Expérience

- **Data Engineer (mission Accor)** — AKABI, 2025 : pipelines Snowflake, SQL, Terraform, CI/CD GitLab
- **Data Analyst (stage)** — SAP Barcelone, 2023-24

📫 sam.pondevie@gmail.com · 🤗 [huggingface.co/Sam-Pdv](https://huggingface.co/Sam-Pdv)
