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
---

## Pós-exploração (Visão Educacional)

Após a exploração da vulnerabilidade, o laboratório permitiu observar os riscos associados
à obtenção de acesso remoto não autorizado, como:

- Possível execução de comandos com privilégios elevados
- Exposição do sistema a persistência maliciosa
- Potencial para movimentação lateral dentro da rede

Esta etapa reforça a importância de compreender não apenas como a exploração ocorre,
mas quais consequências práticas ela gera em ambientes corporativos.

---

## Mitigações Recomendadas

Para reduzir ou eliminar os riscos associados à vulnerabilidade MS17-010, recomenda-se:

- Aplicação dos patches de segurança fornecidos pela Microsoft
- Desativação do protocolo SMBv1
- Restrição de acesso à porta 445 através de firewall
- Monitoramento de tráfego SMB para detecção de atividades anômalas
- Segmentação de rede para limitar movimentação lateral
