# projet-test

Application FastAPI minimale, sans Dockerfile, pour vérifier la construction automatique de greenodes
(détection du framework et Cloud Native Buildpacks, ADR 0011 du dépôt greenodescloud).

Attendu dans la console : « FastAPI — Détection sûre », démarrage par
`uvicorn main:app --host 0.0.0.0 --port $PORT`, puis `GET /` qui répond
`{"message": "Bonjour depuis greenodes, sans Dockerfile"}`.
