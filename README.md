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
# EndoraInsight API

API RESTful para suporte a dados clínicos, epidemiológicos e educacionais no contexto do projeto Endora.

## 📌 Funcionalidades

- Consulta de dados estruturados
- Integração com Swagger UI
- Endpoints seguros com autenticação opcional
- Deploy automático via Vercel

## 🚀 Acesso à Documentação Swagger

Acesse a interface interativa da documentação da API:

👉 [https://endorainsight-api.vercel.app](https://endorainsight-api.vercel.app)

## 🛠️ Tecnologias Utilizadas

- Node.js / Express
- Swagger UI
- JSON para descrição de endpoints (`swagger.json`)
- Vercel (hospedagem)

## 📂 Estrutura do Projeto

```plaintext
/
├── public/
│   └── index.html             # Interface Swagger UI
├── swagger.json               # Descrição da API em OpenAPI 3.0
├── vercel.json                # Configuração de deploy e rotas
└── README.md                  # Este arquivo


---

### Como corrigir o conflito

Se seu `README.md` atual tiver trechos assim:

```markdown

=======
 // outra versão
>>>>>>> a5ace4e0...
