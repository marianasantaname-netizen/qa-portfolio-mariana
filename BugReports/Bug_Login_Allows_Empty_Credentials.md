# Bug Report – Login permite credenciais vazias

## Descrição
O sistema permite login mesmo quando os campos de usuário e senha estão vazios.

Além disso, a mensagem exibida contém erros gramaticais.

Mensagem exibida:
"Login Successfully"
"Thank you for Loggin."

## Ambiente
- Navegador: Chrome
- Data: 25/02/2026

## Passos para Reproduzir
1. Acessar página de login
2. Não preencher usuário
3. Não preencher senha
4. Clicar em Submit

## Resultado Esperado
O sistema deve impedir login e exibir mensagem de erro.

## Resultado Atual
O sistema permite login mesmo sem credenciais válidas e exibe mensagem de sucesso.

## Severidade
Alta (High) – Falha crítica de autenticação

## Impacto no Negócio
Permite acesso não autorizado ao sistema, podendo resultar em exposição de dados sensíveis e falhas graves de segurança.
