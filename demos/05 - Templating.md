# DEMO 05 - Templating

1) Open Copilot in Azure Portal
2) Write the following prompt:

```
Generate the Azure Resource Manager template I need me to copy and paste to a file for an Azure Web App connected to an Azure SQL Database. The Web App should be on a Standard S1 Service Plan, and the SQL database should be on a Basic tier. Give me the template in JSON
```

3) The answer should be an ARM template
4) Copy the template in a VS Code file to check that all the resources are there
5) Write the following prompt in Copilot:

```
Convert it to bicep
```

6) The answer should be a Bicep template
7) Write the following prompt

```
and what about CLI?
```

8) The answer should be a CLI script