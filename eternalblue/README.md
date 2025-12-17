# EternalBlue (MS17-010) — Writeup Educacional

## Contexto

Este writeup documenta um laboratório educacional realizado na plataforma TryHackMe,
com foco na compreensão da vulnerabilidade MS17-010 (EternalBlue) em ambiente controlado.

O objetivo do laboratório foi entender o fluxo de um ataque real, desde a identificação
da vulnerabilidade até o impacto gerado em um sistema vulnerável.

---

## Visão Geral da Vulnerabilidade

A vulnerabilidade MS17-010, conhecida como EternalBlue, afeta o protocolo SMBv1 em sistemas
Windows, permitindo execução remota de código devido a falhas no tratamento de pacotes.

Impactos possíveis:
- Execução remota de código
- Comprometimento total do sistema
- Risco elevado de movimentação lateral em redes corporativas

---

## Metodologia Utilizada

Durante o laboratório, foram aplicados conceitos fundamentais de testes de penetração,
incluindo:

- Identificação de hosts e serviços
- Enumeração de serviços SMB
- Análise de vulnerabilidade conhecida
- Exploração assistida por framework de testes de penetração

---

## Ferramentas

- Metasploit Framework (utilizado como ferramenta de apoio em laboratório educacional)
- Conhecimentos de redes e protocolos SMB

---

## Considerações Éticas

Toda a atividade descrita neste writeup foi realizada exclusivamente em ambiente controlado
e educacional, respeitando princípios éticos e legais de segurança da informação.
