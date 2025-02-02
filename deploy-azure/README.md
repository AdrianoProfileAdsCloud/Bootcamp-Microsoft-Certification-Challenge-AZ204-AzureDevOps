# Bootcamp - Microsoft Certification Challenge AZ204 - Realizar Deploy de uma Api no Azure DevOps.

Criar uma Pipeline(CI - CD) com os conhecimentos adquiridos sobre as ferramentas do Azure.

Cenário:
-  Desenvolvedor publica no repositório do Azure DevOps
- Criar um Pipeline 
- Entregar no ACR(Registro de Contêiner do Azure) registrar as imagens dos contêiners.
- No ACR terá um WebHook que disparado que terá como função atualizar as versão do código, neste caso no Repósitorio d Azure Devops, mas poderia ser confurado para o GitHub ou outro com esta finalidade.

![alt text](<../Imagens/Arquetetura do Projeto.png>)

## Criação de Recursos necessparios no Azure

### Criar o Resource Group

![alt text](<../Imagens/2 passo - Criação do Resource group.png>)

### Clonar o Repositório do AzureDevOps para desenvolver localmente

![alt text](<../Imagens/Clonar o Repositório do AzureDevOps.png>)

- Observação: Use as credenciais fornecidas nesta mesma página.

![alt text](<../Imagens/ 2 - Passo -Credenciais de acesso para clonar.png>)


## Crias os recursos necessários no Azure.

### Criar um Resource Group

![alt text](<../Imagens/3 passo - Criar o Resource Group.png>)

## Criar um ACR(Container Registry)

![alt text](<../Imagens/4 passo - Criar um acr(Container Registry.png>)

## Criar um WebApp

![WebApp](<../Imagens/5 passo - Criar um WebApp.png>)

## Criar um Pipeline no AzureDevOps

![pipeline](<../Imagens/6 passo - Criar um pipeline.png>)

- Este será o arquivo onde iremos descre o que o pipeline fára:

![Arquivo do pipeline](<../Imagens/7 passo - Arquivo do pipeline.png>)

