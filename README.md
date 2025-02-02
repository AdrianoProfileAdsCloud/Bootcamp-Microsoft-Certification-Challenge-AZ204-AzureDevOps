# Bootcamp - Microsoft Certification Challenge AZ204 - Realizar Deploy de uma Api no Azure DevOps.

Criar um Pipeline(CI - CD) com os conhecimentos adquiridos sobre as ferramentas do Azure.

Cenário:
-  Desenvolvedor publica no repositório do Azure DevOps.
- Criar um Pipeline 
- Entregar no ACR(Registro de Contêiner do Azure) registrar as imagens dos contêiner.
- No ACR terá um WebHook que disparado cuja função será atualizar a versão do código, neste caso no Repósitorio d Azure Devops, mas poderia ser configurado para o GitHub ou outro com esta finalidade.

![Arquitetura](https://github.com/AdrianoProfileAdsCloud/Bootcamp-Microsoft-Certification-Challenge-AZ204-AzureDevOps/blob/main/Imagens/Arquitetura%20do%20Projeto.png))

### Clonar o Repositório do AzureDevOps para desenvolver localmente

![clone](https://github.com/AdrianoProfileAdsCloud/Bootcamp-Microsoft-Certification-Challenge-AZ204-AzureDevOps/blob/main/Imagens/Clonar%20o%20Reposit%C3%B3rio%20do%20AzureDevOps.png)

- Observação: Use as credenciais fornecidas nesta mesma página.
## Criação de Recursos necessparios no Azure

### Criar o Resource Group

![Resource Group](https://github.com/AdrianoProfileAdsCloud/Bootcamp-Microsoft-Certification-Challenge-AZ204-AzureDevOps/blob/main/Imagens/3%20passo%20-%20Criar%20o%20Resource%20Group.png)

## Criar um ACR(Container Registry)

![acr](https://github.com/AdrianoProfileAdsCloud/Bootcamp-Microsoft-Certification-Challenge-AZ204-AzureDevOps/blob/main/Imagens/4%20passo%20-%20Criar%20um%20acr-Container%20Registry.png)

## Criar um WebApp

![WebApp](https://github.com/AdrianoProfileAdsCloud/Bootcamp-Microsoft-Certification-Challenge-AZ204-AzureDevOps/blob/main/Imagens/criar%20um%20webapp.png)

## Criar um Pipeline no AzureDevOps

![pipeline](https://github.com/AdrianoProfileAdsCloud/Bootcamp-Microsoft-Certification-Challenge-AZ204-AzureDevOps/blob/main/Imagens/criar%20um%20pipeline.png)

- Este será o arquivo onde iremos descre o que o pipeline fára:

![Arquivo do pipeline](https://github.com/AdrianoProfileAdsCloud/Bootcamp-Microsoft-Certification-Challenge-AZ204-AzureDevOps/blob/main/Imagens/arquivo%20pipeline.png)

