# Slides — INFOESTE 2026 · Cyber Web Security

**Como Hackers Quebram Aplicações Web — Ataque & Defesa na Prática**

Material de apoio do minicurso de segurança de aplicações web apresentado na **INFOESTE 2026**. São 8 horas de laboratório: começa no HTTP e termina num mini CTF.

📄 **[INFOESTE_Cyber_Web_Security.pdf](./INFOESTE_Cyber_Web_Security.pdf)**

## Instrutores

- **Henrique Otsuka**, Head de Tecnologia da Informação · VLab Health
- **Marcos Santos**, Desenvolvedor Fullstack · VLab Health

## Conteúdo

| Módulo | Tema |
|---|---|
| 00 | Contexto: por que isso importa, panorama de ameaças e anatomia de um ataque |
| 01 | HTTP + Browser: da tela bonita ao protocolo real |
| 02 | Burp Suite: interceptar, modificar e reenviar requisições |
| 03 | IDOR / Broken Access Control |
| 04 | SQL Injection |
| 05 | Cross-Site Scripting (XSS) |
| 06 | Autenticação + Sessões |
| 07 | Falhas do dia a dia (upload inseguro e outras) |
| 08 | OWASP ZAP: do raciocínio manual ao apoio automatizado |
| 09 | Mini CTF |
| 10 | Defesa em profundidade + OWASP Top 10:2025 em detalhe |
| 11 | Segurança em Cloud |

## Laboratórios

Os exercícios práticos usam duas aplicações vulneráveis feitas para o curso. Elas rodam localmente via Docker:

- **NEON SHOP**, alvo dos módulos guiados: [HenriqueOtsuka/neon-shop-infoeste](https://github.com/HenriqueOtsuka/neon-shop-infoeste)
- **VAULT Banco Digital**, alvo do segundo CTF: [HenriqueOtsuka/vault-bank-infoeste](https://github.com/HenriqueOtsuka/vault-bank-infoeste)

```bash
git clone https://github.com/HenriqueOtsuka/vault-bank-infoeste.git
cd vault-bank-infoeste
docker compose up -d --build
```

**Ferramentas:** Windows 11, Docker Desktop, Burp Suite Community e OWASP ZAP.

## ⚠️ Aviso

Este material tem fins **exclusivamente educacionais**. Pratique as técnicas apenas nos laboratórios do curso, em `localhost`, ou em sistemas que você tem autorização explícita para testar. Atacar sistemas de terceiros sem permissão é crime (Lei 12.737/2012).
