# GoutteEau
Ce dépôt est consacré au projet Goutte d'eau, développé dans le cadre de l'alternance professionnelle.

# Architecture

```mermaid
```mermaid
flowchart TD
    A[API météo] --> B[Collecte]
    B --> C[Nettoyage]
    C --> D[(CSV / Parquet / SQLite)]
    C --> E[Modèles ML]
    E --> F[XGBoost]
    F --> G[Inférence]
    G --> H[Risque de pluie]
```
