# Arquitetura do Sistema

Este documento descreve a arquitetura geral do sistema, apresentando os principais componentes e o fluxo de dados da aplicação.

---

## Visão Geral

O sistema segue uma arquitetura simples baseada em separação de responsabilidades, dividida em camadas:

- Interface do usuário (UI)
- Camada de processamento (Downloader)
- Integração externa (YouTube)
- Sistema de arquivos (Armazenamento)

---

## Fluxo da Aplicação

```text
Usuário → UI → Downloader → YouTube
                              ↓
                         File System
