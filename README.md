# Teste-de-Desempenho
Este é um guia para a prática que iremos fazer juntos na apresentação de Teste de Verificação e Validação.

## Instalando a Ferramenta
Para a nossa prática utilizaremos a ferramenta Apache JMeter, que é uma ferramenta utilizada para variados tipos de testes de desempenho. Para a utilização do JMeter é necessário que você tenha o Java instalado na sua máquina. 

Depois, você pode baixar a ferramenta pelo link: [Download do Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi).

Depois de Acessar a página, procure pelos arquivos Binários e baixe o arquivo compatível com seu  sistema operacional.

Para acessar a ferramenta, siga os seguintes passos básicos:
- Faça a extração dos dados da pasta zipada;
- Procure pela pasta "Bin";
- Procure pelo arquivo com nome: "ApacheJMeter.jar" e o execute;

## Prática em Sala
A equipe explicará como fazer os passos seguintes, mas para conhecimento prévio, os passos seguintes serão:

- Crie um plano de teste no JMeter com as seguintes configurações:
    - Defina diferentes números de usuários simultâneos (cada equipe define um número. ex: equipe A: 10 usuários);
    - Use uma solicitação do tipo HTTPS para acessar a URL da escolha do grupo;
    - Adicione um ouvinte ao seu teste para monitorar os resultados do teste;     

- Cada equipe deverá observar os seguintes registros ao final do teste:
    - Taxa de requisições;
    - Tempo médio de resposta de cada requisição;
    - Número de erros (se houver);

Com isso, temos a demonstração dos testes de desempenho e os dados necessários para avaliar o sistema.
