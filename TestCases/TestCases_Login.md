# Casos de Teste – Login

## TC-01 – Login com campos vazios

**Passos:**
1. Acessar página de login
2. Não preencher usuário e senha
3. Clicar em Submit

**Resultado Esperado:**
O sistema deve impedir o login e exibir mensagem de erro.

**Resultado Obtido:**
O sistema permitiu login mesmo com campos vazios.

**Status:**
Fail


---

## TC-02 – Login com senha inválida / usuário incorreto

**Passos:**
1. Inserir usuário inválido
2. Inserir senha incorreta
3. Clicar em Submit

**Resultado Esperado:**
O sistema deve exibir mensagem de erro.

**Resultado Obtido:**
O sistema impediu o login quando o usuário e a senha estavam incorretos.

**Status:**
Pass


---

## TC-03 – Login com dados válidos (usuário recém cadastrado)

**Passos:**
1. Inserir usuário válido
2. Inserir senha válida
3. Clicar em Submit

**Resultado Esperado:**
O sistema deve permitir acesso e redirecionar corretamente.

**Resultado Obtido:**
O sistema permitiu login com sucesso utilizando as credenciais cadastradas.

**Status:**
Pass
