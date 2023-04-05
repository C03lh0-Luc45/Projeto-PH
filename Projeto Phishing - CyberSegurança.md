# Projeto Phishing para captura de login do Facebook

### Ferramentas utilizadas

* Kali Linux
* setoolkit

### Configurando o Phishing no Kali Linux

* Acessar terminal CLI;
* Garantindo acesso root: ``` sudo su ```
* Iniciar o setoolkit: ``` setoolkit ```
* Ao apresentar as primeiras opções, selecionar tipo de ataque: ``` Social-Engineering Attacks ```
* Próximo, selecionar o vetor de ataque: ``` Web Site Attack Vectors ```
* Para o método de ataque, selecionar: ```Credential Harvester Attack Method ```
* Continuar com método de ataque: ``` Site Cloner ```
* Obtendo o endereço da máquina: ``` ifconfig ```
* URL para preencher solicitação para clone: http://www.facebook.com
* Utilizando o browser do host da VM, acessar o IP gerado para a página falsa

### Resutados

- Página falsa:
  ![9f3181cd-1dba-49d9-a797-a5764c05c2cd](file:///C:/Users/Lucas/Pictures/Typedown/9f3181cd-1dba-49d9-a797-a5764c05c2cd.png)

- Resultado na tela CLI do Kali Linux

![Projeto Phishing - Resultado](C:\Users\Lucas\OneDrive\Área%20de%20Trabalho\Projeto%20Phishing%20-%20Resultado.png)
