
![GitHub top language](https://img.shields.io/github/languages/top/Andre-LSousa/workshop-javafx-jdbc?style=plastic)
![GitHub language count](https://img.shields.io/github/languages/count/Andre-LSousa/workshop-javafx-jdbc?style=plastic)

SOBRE O PROJETO

MyApp é uma aplicação full stack desktop, construída durante o curso JAVA COMPLETO, aplicado pela DevSuperior por meio da plataforma Udemy.

A aplicação consiste no desenvolvimento de um aplicativo de sistema de gerenciamento para pequenos comércios, apresenta modelo de interface gráfica e permite executar consultas e manipular resultados com conexão a base de dados.

FUNCIONALIDADES

Cria, Atualiza, e Exclui vendedores e departamentos

LAYOUT DESKTOP

![Image](https://github.com/user-attachments/assets/43badf12-d144-4b19-9d94-f3620c4dd124)
![Image](https://github.com/user-attachments/assets/0dbacff1-0c4d-43ba-bdaa-5cdd4c6842ac)
![Image](https://github.com/user-attachments/assets/fe5c2e52-5b03-402e-aae0-91d8b0859b49)
![Image](https://github.com/user-attachments/assets/a7f6b21f-76d7-4120-8408-af1e80acac02)




TECNOLOGIAS UTILIZADAS

Back end:
Java
MySQL
Jdbc

Front end: 
JavaFX
FXML
SceneBuilder


COMO EXECUTAR O PROJETO

Pré requisitos: JAVA 21
#clonar repositório: https://github.com/Andre-LSousa/MyApp-installation-package

Instale Java: https://www.oracle.com/technetwork/java/javase/downloads/index.html
*extrair os arquivos do arquivo ZIP para a pasta C:\Program Files\Java 
*configure a variavel de ambiente JAVA_HOME (ex: C:\Program Files\Java\"SEU JDK"), verique junto a este procedimento, em "editar a variavel de ambiente" se a variavel de ambiente %JAVA_HOME%\bin está relacionada na lista, caso não esteja, crie uma nova variavel. 

Extraia o arquivo openjfx-21.0.6_windows-x64_bin-sdk.zip e copie para a pasta "C:\java-libs"
*configure a variavel de ambiente: PATH_TO_FX (ex: C:\java-libs\javafx-sdk\lib)
*copie o "mysql-connector" da pasta "workshop-javafx-jdbc_lib" e cole em "C:\java-libs\javafx-sdk\lib"
*copie o arquivo JAR & db.properties para uma nova pasta (ex. MyApp)
*no prompt de comando utilize o comando cd\MyApp para acessar os arquivos instalados na pasta e utilize o comando java --module-path %PATH_TO_FX% --add-modules javafx.controls,javafx.fxml -cp workshop-javafx-jdbc.jar application.Main, para rodar a aplicação.



AUTOR 
André Luiz de Sousa
www.linkedin.com/in/andré-luiz-de-souza-0a061893












