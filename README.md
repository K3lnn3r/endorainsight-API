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
<<<<<<< HEAD
// uma versão
=======
 // outra versão
>>>>>>> a5ace4e0...
