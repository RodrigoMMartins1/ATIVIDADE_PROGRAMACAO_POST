# ATIVIDADE_PROGRAMACAO_POST
# README

## Função Lambda de Exemplo
<img width="552" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO_POST/assets/99209230/624a11f0-eec3-4c7c-a3b6-ab9bff701969">


### Como Usar

Passo 1: Acesse o Console de Gerenciamento da AWS e vá para o serviço Lambda.

Passo 2: Clique em "Criar função" e selecione a opção "Autor do zero" para começar com uma função em branco.

Passo 3: Dê um nome para a função, selecione a linguagem de programação desejada (por exemplo, Python) e clique em "Criar função".

Passo 4: Na página de configuração da função, você verá um editor de código. Substitua o código da imagem.

Passo 5: Clique em adicionar gatilho e clique em API Gateway

Passo 6: Escolha requisição REST e Open.

Passo 7: Faça um header com a autenticação Bearer 1234

Passo 8: Body com Json que você queira enviar

### Endpoint
endpoint: https://ouetw2r06k.execute-api.us-east-1.amazonaws.com/default/autoestudofunction
### Testes
#### Mensagens
```json
{
    "body": "{\"name\": \"Alice\", \"age\": 30, \"city\": \"New York\"}"
}
````
#### Testes Unitários
- Autenticação aprovada
<br><br>
<img width="658" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO_POST/assets/99209230/36a39c2a-a1b1-47a0-8591-00a9c5ef2375">
<br><br>
- Autenticação rejeitada
<br><br>
<img width="572" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO_POST/assets/99209230/2496a7cb-b88f-4f5e-b6fe-26cf9c680e65">
<br><br>
- Autenticação ausente
<br><br>
<img width="643" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO_POST/assets/99209230/16cea17d-df08-45bd-ac1b-36d6ba4f7a9f">
<br><br>
- Autenticação aprovada, porém JSON não valido
<br><br>

````json
{
  "body": "Isso não é um JSON válido"
}
````
<br><br>
<img width="599" alt="image" src="https://github.com/RodrigoMMartins1/ATIVIDADE_PROGRAMACAO_POST/assets/99209230/14754081-545a-4294-a730-817f02d0b2ab">

  

