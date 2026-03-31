# Casos de Teste

## CT01 - Login sem credenciais

Passos:
1. Acessar o site
2. Não preencher os campos
3. Clicar em login

Resultado esperado:
Mensagem de erro informando que o usuário é obrigatório

Resultado atual:
"Username is required"

Status: Aprovado


## CT02 - Login com password vazio

Passos:
1. Inserir username válido
2. Deixar password vazio
3. Clicar em login

Resultado esperado:
Mensagem informando que password é obrigatório

Resultado atual:
"Password is required"

Status: Aprovado
