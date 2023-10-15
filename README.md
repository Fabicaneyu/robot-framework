# Robot Framework

É Keyword-driven = utiliza palavras-chave para descrever e implementar os passos do teste
Um conjunto de keywords de ação é chamada Library, caminho: Home > Resources > Library

Robot
https://robotframework.org/

Selenium Library
https://robotframework.org/SeleniumLibrary/SeleniumLibrary.html#Open%20Browser


Por que o Robot Framework é considerado um framework genérico de automação de testes de software?
Porque pode automatizar os testes de vários tipos de sistema (Web, API, desktop, mobile, etc) O Robot foi criado com o intuito de poder automatizar qualquer sistema, desde que haja uma library definida para tal fim, como a SeleniumLibrary, para testes de web, por exemplo.

Qual a principal característica e vantagem da abordagem keyword-driven?
A abordagem keyword-driven facilita a escrita de scripts de teste, uma vez que encapsula o desenvolvimento em baixo nível do script, assim não preciso me preocupar com a linguagem de programação a qual fora implementada.
Sim! A principal vantagem é que o automatizador não precisa se preocupar com a implementação da keyword (em baixo nível), apenas em aprender como usá-la!

Preciso, no meu teste, ler o conteúdo de um arquivo .txt existente em um determinado diretório da minha máquina. Qual library disponibiliza esse recurso? DICA: Pesquise nas Libraries citadas na seção BUILT-IN do site do Robot Framework para descobrir!
OperatingSystem, Isso! E a keyword correspondente é a "Get File" !!

Preciso ler dados de uma planilha Excel para os meus testes. Quero ler uma linha e armazenar todos os valores dela. A library que me disponibiliza esse recurso é a Excel Library (https://zero88.github.io/robotframework-excel/docs/ExcelRobot.html). Mas qual dos exemplos abaixo é a forma correta de utilizar a keyword que me traz esse resultado?

# Configs

Python
https://www.python.org/downloads/
