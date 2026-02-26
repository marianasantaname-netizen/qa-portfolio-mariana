# Bug Report – Login permite credenciais vazias

## Descrição
O sistema permite login mesmo quando os campos de usuário e senha estão vazios.

## Ambiente
- Navegador: Chrome
- Data: 25/02/2026

## Passos para Reproduzir
1. Acessar a página de login
2. Não preencher o campo de usuário
3. Não preencher o campo de senha
4. Clicar em Submit

## Resultado Esperado
O sistema deve impedir o login e exibir mensagem de erro informando que os campos são obrigatórios.

## Resultado Atual
O sistema permite acesso mesmo sem credenciais válidas e redireciona para a página autenticada.

## Severidade
Alta (High) – Falha crítica de autenticação

## Impacto no Negócio
Permite acesso não autorizado ao sistema, podendo resultar em exposição de dados sensíveis, comprometimento de segurança e riscos legais.
