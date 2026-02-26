# Test Summary Report – Guru99 Newtours

## Objetivo do Projeto
Executar testes manuais e cenários em BDD para validar o fluxo de login do sistema.

---

## Escopo Executado
- Testes manuais de login
- Cenários positivos e negativos
- Escrita de cenários em BDD
- Registro de bugs encontrados

---

## Casos de Teste Executados
Total de testes: 3

- TC-01 – Login com campos vazios → Fail
- TC-02 – Login com credenciais inválidas → Pass
- TC-03 – Login com credenciais válidas → Pass

---

## Bugs Encontrados

1. Login permite credenciais vazias  
   Severidade: Alta  

2. Erros gramaticais nas mensagens de login  
   Severidade: Baixa  

---

## Análise

Foi identificada uma falha crítica de autenticação, permitindo acesso ao sistema sem credenciais válidas.

Esse tipo de falha representa alto risco em sistemas reais, podendo comprometer segurança e integridade de dados.

---

## Conclusão

O sistema apresenta vulnerabilidade grave no fluxo de autenticação que deve ser corrigida antes de um possível deploy em produção.
