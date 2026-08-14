# FieldOps — Plataforma de Inspeção em Campo

> Projeto acadêmico integrado de desenvolvimento mobile, web e backend.

## 📋 Sobre o projeto

O **FieldOps** é uma plataforma digital para planejamento, execução, acompanhamento e revisão de inspeções técnicas realizadas em campo.

A solução substitui processos baseados em formulários impressos, planilhas e registros informais por um fluxo digital integrado. Técnicos de campo utilizam um **aplicativo mobile** para consultar inspeções atribuídas, identificar equipamentos por QR Code, responder checklists dinâmicos, registrar evidências fotográficas e concluir atividades — inclusive em locais sem conexão com a internet. Administradores e supervisores utilizam uma **interface administrativa web** para cadastrar informações, criar modelos de inspeção, agendar atividades, atribuir técnicos, acompanhar a execução e aprovar ou reprovar os resultados. Uma **API REST** centraliza as regras de negócio, a autenticação, a persistência e a auditoria.

### Componentes da solução

| Componente | Descrição | Stack |
|---|---|---|
| 📱 **App Mobile** | Execução de inspeções em campo, com suporte offline | Expo + React Native + TypeScript |
| 🖥️ **Interface Administrativa** | Cadastros, planejamento, acompanhamento e revisão | Angular + TypeScript |
| ⚙️ **API REST** | Regras de negócio, autenticação, persistência e sincronização | Java + Spring Boot + PostgreSQL |

### Principais características

- ✅ Modelos de inspeção reutilizáveis e **versionados de forma imutável**
- ✅ Checklists dinâmicos com múltiplos tipos de resposta
- ✅ Identificação de equipamentos por **QR Code**
- ✅ Registro de evidências fotográficas e não conformidades
- ✅ **Operação 100% offline** em campo, com sincronização posterior
- ✅ Sincronização por fila de operações **idempotentes**, sem duplicidade de dados
- ✅ Fluxo completo de revisão, aprovação e reprovação com histórico auditável

---

## 👥 Equipe

| Integrante | GitHub |
|---|---|
| Giovani Miamoto | [@giovanimiamotob](https://github.com/giovanimiamotob) |
| Glauco Todesco | [@glaucotodesco](https://github.com/glaucotodesco) |
| Jose Eduardo de O. Jr | [@JoseEduardodeOliveiraJunior](https://github.com/JoseEduardodeOliveiraJunior) |
| Luciano Júnior | [@lucianomenezesjr](https://github.com/lucianomenezesjr) |
| Tobias Perassi Alquezar | [@tobiasperassi](https://github.com/tobiasperassi) |
| Victor Geroto | [@victorgeroto](https://github.com/victorgeroto) |

---

## 📂 Estrutura da organização

> Preencher com os links dos repositórios do time conforme forem criados.

- `fieldops-mobile` — Aplicativo mobile (Expo/React Native)
- `fieldops-admin` — Interface administrativa web (Angular)
- `fieldops-api` — API REST (Java/Spring Boot)
- `fieldops-docs` — Documentação e especificação do projeto

---

## 🚀 Status

Projeto em desenvolvimento — fase de especificação e prototipação de interface concluídas.

---

<p align="center">Desenvolvido como projeto acadêmico integrado.</p>
