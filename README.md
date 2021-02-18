# Deployment_GitHubActions-DotNet5-Docker-Selenium-Artifacts-AppService-Slack
Workflow do GitHub Actions para build de imagens de um site criado com .NET 5 + ASP.NET Core, testes com Selenium WebDriver, push no Docker Hub e deployment no Azure App Service através do uso de containers. Inclui ainda o envio ao Slack de notificações de sucesso no processamento do workflow ou falha na execução dos testes, além de Artifacts contendo o relatório dos testes que falharam e screenshots do Selenium.

Aplicação que serviu de base para a construção deste workflow:

https://github.com/renatogroffe/DotNet5-Site-xUnit-SpecFlow-Selenium-Screenshots-Docker_ConversorDistancias
