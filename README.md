
# Security Check

Este projeto tem como objetivo validar a segurança do repositório efetuando testes de SAST, SCA, Secrets e DAST.

Os testes citados acima buscam bibliotecas com CVEs registradas, códigos desenvolvidos com vulnerabilidades na sua escrita, senhas e chaves armazenadas de forma fixa no código. Além de efetuarem um scan automatizado na aplicação após o processo de deploy, executando então uma análise dinâmica no código através do projeto OWASP ZAP.




## Funcionalidades Implementadas

- SAST (Análise Estática de código)
- SCA (Análise de Composição de Código)
- Secrets (Senhas, Chaves e Segredos HardCoded)
- DAST (Análise Dinâmica de Código)
## Autores

- [@FelipePeres](https://github.com/h4rdx0)


## Referência

 - [Checkmarx One](https://docs.checkmarx.com/en/34965-68643-scan.html#UUID-09d01a78-a3c7-eb8f-c131-58a4d4ecf026)
 - [GitLeaks](https://github.com/gitleaks/gitleaks)
 - [OWASP ZAP](https://www.zaproxy.org/blog/2020-05-15-dynamic-application-security-testing-with-zap-and-github-actions/)
