# ATIVIDADE_PROGRAMACAO_POST
# README

## Função Lambda de Exemplo
<img width="464" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO_POST/assets/99209230/c3ed19b6-e960-48c1-8c17-de44e35077e0">


### Como Usar

Passo 1: Acesse o Console de Gerenciamento da AWS e vá para o serviço Lambda.

Passo 2: Clique em "Criar função" e selecione a opção "Autor do zero" para começar com uma função em branco.

Passo 3: Dê um nome para a função, selecione a linguagem de programação desejada (por exemplo, Python) e clique em "Criar função".

Passo 4: Na página de configuração da função, você verá um editor de código. Substitua o código da imagem.

Passo 5: Clique em adicionar gatilho e clique em API Gateway

Passo 6: Escolha requisição REST e Open.

### Endpoint
endpoint: https://ouetw2r06k.execute-api.us-east-1.amazonaws.com/default/autoestudofunction
### Testes

```json
{
    "body": "{\"name\": \"João\", \"age\": 30, \"city\": \"São Paulo\"}"
}
````
<img width="643" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO_POST/assets/99209230/c9c39a48-3030-4af5-9b7c-a70ad10314cd">

```json
{
    "body": "Isso não é um JSON válido"
}
````
<img width="647" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO_POST/assets/99209230/4cb10d6a-6d69-4c0e-bce4-42d39bb485f7">

```json
{
    "body": "{\"name\": \"Ana\", \"age\": \"não é um número\", \"city\": \"Curitiba\"}"
}
````
<img width="653" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO_POST/assets/99209230/73c9469b-4475-4745-8220-2b7fa2a490b4">




