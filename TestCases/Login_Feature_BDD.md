# Feature: Login no sistema Guru99

Como um usuário cadastrado
Eu quero realizar login no sistema
Para acessar a área autenticada

---

## Cenário 1: Login com credenciais válidas

Given que o usuário está na página de login
When ele insere um usuário válido
And insere uma senha válida
And clica em Submit
Then o sistema deve permitir acesso
And exibir mensagem de sucesso

---

## Cenário 2: Login com credenciais inválidas

Given que o usuário está na página de login
When ele insere um usuário incorreto
And insere uma senha incorreta
And clica em Submit
Then o sistema deve impedir o acesso
And exibir mensagem de erro

---

## Cenário 3: Login com campos vazios

Given que o usuário está na página de login
When ele não preenche usuário e senha
And clica em Submit
Then o sistema não deve permitir acesso
And deve exibir mensagem de erro
