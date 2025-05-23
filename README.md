# plataforma-prestadores-api

Este projeto nasceu a partir de um repositório antigo focado em operações básicas de CRUD — [`crud-api-dotnet5`](https://github.com/talithaSouza/WepApi---NETCore) — desenvolvido originalmente com .NET 5 e sem utilização de contêineres ou práticas modernas de deploy.

Com o objetivo de torná-lo mais robusto, profissional e alinhado com práticas modernas de desenvolvimento backend, esta nova versão foi criada para aplicar:

- 🔄 **Atualização do framework**: evolução da stack do .NET 5 para versões mais recentes (como .NET 8).
- 🐳 **Dockerização da aplicação**: incluindo o uso de **Docker** e **Docker Compose** para orquestração local da API e banco de dados.
- ⚙️ **Pipeline CI/CD**: estrutura pensada para ser integrada com **GitHub Actions**, com foco em automação de testes, build e futuramente deploy.
- 💡 **Refatoração e ampliação da arquitetura**: com vistas a evoluir o projeto para algo mais próximo de aplicações reais, como uma **plataforma de prestadores de serviços**.

## 🚧 Em desenvolvimento

Este projeto está em evolução contínua. Futuras etapas incluem:

- Conexão com banco de dados relacional (MySQL).
- Versionamento de API.
- Implementação de autenticação JWT.
- Estrutura de serviços e repositórios.
- Deploy automatizado para ambiente **local de desenvolvimento**.
- (Futuramente) Deploy automatizado para ambientes externos como **EC2** e **Kubernetes**.

## 📦 Tecnologias iniciais

- .NET 8 (em migração)
- Docker / Docker Compose
- MySQL (em container)
- GitHub Actions (pipeline em construção)

---

> Este repositório representa uma evolução prática de um projeto antigo, com foco no aprendizado e aplicação de boas práticas de backend moderno.
