
# Endora Insight API

API pública para triagem e classificação de risco psicossocial com base em linguagem natural, desenvolvida pelo Instituto Endora para Saúde, Justiça e Tecnologia.

## 🌐 Deploy público

https://endorainsight-api.vercel.app

## 📌 Rotas simuladas

| Método | Rota           | Descrição |
|--------|----------------|-----------|
| `POST` | `/analyze-text` | Recebe texto e retorna `risk_score`, `nível`, marcadores e justificativa |
| `GET`  | `/get-score`    | Retorna inferência armazenada por ID |
| `GET`  | `/docs`         | Redireciona para documentação Swagger UI |

## 📁 Arquivos

- `swagger.json`: especificação da API em OpenAPI 3.0
- `index.html`: carregador da documentação Swagger UI

## ⚠️ Aviso ético

Esta API tem finalidade exclusivamente educacional, experimental e científica.
Não deve ser utilizada para decisões clínicas, jurídicas ou institucionais automatizadas.

## 📞 Contato institucional

**Dr. Kelnner Portela Luz**  
Diretor Executivo – Instituto Endora  
📧 kelnner@endorainstitute.org  
🌐 https://www.endorainstitute.org
