# netflix-architecture-diagram

# Arquitetura Simplificada de um Serviço de Streaming (Estilo Netflix)

Este repositório contém um **diagrama simples** feito no [draw.io](https://app.diagrams.net/) representando a arquitetura básica de um serviço de streaming (inspirado na Netflix).

## 📂 Estrutura
- `netflix.drawio` → Arquivo editável (abrir no draw.io).
- `netflix.png` → Exportação para visualização rápida.

## 🚀 Fluxo principal
1. **Clients (Web / Mobile / TV)** → Usuários acessam via app ou navegador.
2. **CDN / Edge Cache** → Entrega rápida de vídeos e imagens.
3. **API Gateway / Load Balancer** → Entrada de requisições, autenticação inicial.
4. **Microservices (Auth, Catálogo, Recomendações, Playback)** → Lógica do negócio.
5. **Object Storage / Transcoder** → Armazena e adapta os vídeos.
6. **Databases / Cache** → Persistência e performance.

## 📝 Observações
- O objetivo é **didático**, não representa a arquitetura oficial da Netflix.
- Pode ser expandido com detalhes de mensageria, analytics e billing.
