# Projet Cat Nat IA — ISFA 2025/2026

## Description
Modélisation des catastrophes naturelles en France par apprentissage automatique
et simulation actuarielle de réassurance (LSTM, ARIMA, Monte Carlo, Excess of Loss).

## Données utilisées

### 1. GASPAR — Géorisques (Ministère de l'Intérieur)
Arrêtés de reconnaissance de l'état de catastrophe naturelle en France
- https://www.georisques.gouv.fr/donnees/bases-de-donnees/gaspar
- Fichiers : `catnat_gaspar.csv`

### 2. SWI — Indice d'humidité des sols (Météo France)
- https://donneespubliques.meteofrance.fr/?fond=produit&id_produit=301&id_rubrique=40
- Fichiers : `swi.200001-200912.csv`, `swi.201001-201912.csv`, `swj.202001-202512.csv`

### 3. Bilan Cat Nat par département
- https://www.georisques.gouv.fr/
- Fichiers : `D_Bilan global par département.csv`

### 4. Nombre d'arrêtés Cat Nat — Data.gouv
- https://www.data.gouv.fr/fr/datasets/
- Fichiers : `nombre-darretes-de-catastrophes-naturelles-copie.csv`

## Librairies principales
pandas, numpy, matplotlib, scikit-learn, tensorflow-macos, statsmodels


