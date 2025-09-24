# <ins> AWS Step Functions </ins>
Este projeto tem por objetivo documentar e consolidar o aprendizado da ferramenta AWS Step Functions.  
Projeto **BootCamp Code Girls 2025** DIO em parceria com Santander.

O presente trabalho cria um fluxograma de um sistema de entrega de exames.

## <ins>Fluxograma criado a partir do **AWS Step Functions**</ins>

<img width="582" height="584" alt="stepfunctions_graph" src="https://github.com/user-attachments/assets/0eeb65e3-c1b8-427f-b9e6-559e76fed174" />

- ### Função Lambda: 
Realiza o login do usuário.

- ### Cognito:
Valida o usuário melhorando a segurança e a escalabilidade.

- ### Choice Status:
Cumpre a função de separação da autenticação pelo cognito do fluxo de decisão.

- ### DynamoDB Query:
Escolha do Dynamo para maior performace.

- ### S3 Glacier:
Armazena os exames mais antigos configurado com a política de ciclo de vida.

- ### Função Lambda:
Utilizada para crianção de usuário.
