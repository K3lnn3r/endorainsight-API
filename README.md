# Endora Insight API

API pública para triagem e classificação de risco psicossocial com base em linguagem natural, desenvolvida pelo Instituto Endora.

## Rotas simuladas

- `POST /analyze-text`
- `GET /get-score`
- `GET /docs`

Deploy: https://endorainsight-api.vercel.app
swagger.json


{
  "cleanUrls": true,
  "rewrites": [
    {
      "source": "/docs",
      "destination": "/index.html"
    }
  ]
}
