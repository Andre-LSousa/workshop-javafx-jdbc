[![NPM License](https://img.shields.io/npm/l/react)](https://github.com/Andre-LSousa/workshop-javafx-jdbc/blob/main/LICENSE)

![GitHub top language](https://img.shields.io/github/languages/top/Andre-LSousa/workshop-javafx-jdbc?style=plastic)

![GitHub language count](https://img.shields.io/github/languages/count/Andre-LSousa/workshop-javafx-jdbc?style=plastic)

<br>
<h1>SOBRE O PROJETO</h1>

MyApp é uma aplicação full stack desktop, construída durante o curso JAVA COMPLETO, aplicado pela DevSuperior por meio da plataforma Udemy. Este projeto tem como objetivo demonstrar o conhecimento técnico e a habilidade prática adquirida ao longo do curso, integrando o back-end e front-end de forma eficiente e intuitiva.

A aplicação consiste no desenvolvimento de um aplicativo de sistema de gerenciamento POS(Point of Sale), apresenta modelo de interface gráfica e permite executar consultas e manipular resultados com conexão a base de dados.

<br>
<h2>FUNCIONALIDADES</h2>
Cria, atualiza e exclui entidades de vendedores e departamentos.

<br><br>
<h2>LAYOUT DESKTOP</h2>
<body>
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/43badf12-d144-4b19-9d94-f3620c4dd124" alt="Image 1" height="250" width="400"/>
        <figcaption></figcaption>
    </figure>    
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/0dbacff1-0c4d-43ba-bdaa-5cdd4c6842ac" alt="Image 2" height="250" width="400"/>
        <figcaption></figcaption>
    </figure>
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/fe5c2e52-5b03-402e-aae0-91d8b0859b49" alt="Image 3" height="250" width="400"/>
        <figcaption></figcaption>
    </figure>
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/a7f6b21f-76d7-4120-8408-af1e80acac02" alt="Image 4" height="250" width="400"/>
        <figcaption></figcaption>
    </figure>
</body>

<br><br>
<h2>PADRÕES DE PROJETO APLICADOS</h2>
<body>
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/7a5bc5dc-5562-4000-a158-b90816f59614" alt="Image 1"  height="250" width="400"/>
        <figcaption>
            <h3>Padrão Factory</h3>
            <li>A classe DaoFactory fornece métodos estáticos (createSellerDao e createDepartmentDao) para criar instâncias de DAOs (SellerDaoJDBC e DepartmentDaoJDBC), encapsulando a lógica de criação de objetos.
        </figcaption>
    </figure><br><br><br>
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/e1a88f2f-1149-477e-80ab-c643ce5b1fe9" alt="Image 2"  height="250" width="400"/>
        <figcaption><h3>Padrão Observer</h3>
        <li>A Interface DataChangeListener define um método onDataChanged() que será implementado por classes que desejam ser notificadas quando há uma mudança nos dados. findAll</figcaption>
    </figure><br><br><br>
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/16835dc6-cce6-43a7-92ea-9fba682ecbe2" alt="Image 3" height="250" width="400"/>
        <figcaption><h3>Padrão Singleton</h3>
          <li>A classe DB possui um único atributo estático conn do tipo Connection, garantindo que somente uma instância de conexão será criada, método getConnection() verifica se a conexão conn é null. Se for, ele cria uma nova conexão. Caso contrário, retorna a conexão existente.
        </figcaption>
    </figure><br><br><br>
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/bd309eec-485d-41da-8e2b-6538b5abe7cf" alt="Image 4" height="250" width="400"/>
        <figcaption><h3>Padrão DAO (Data Object Acces)</h3>
        <li>A interface DepartmentDao define os métodos principais para a manipulação dos dados de Department no banco de dados, como insert, update, deleteById, findById e </figcaption>
    </figure><br><br><br>
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/87f77071-996d-480c-b059-3776cf625593" alt="Image 5" height="250" width="400"/>
        <figcaption></figcaption>
    </figure><br><br><br>
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/d623a583-e8fc-40b6-80f4-d6e8c8a9c12d" alt="Image 6" height="250" width="400"/>
        <figcaption></figcaption>
    </figure><br><br><br>
    <figure class="figure-container">
        <img src="https://github.com/user-attachments/assets/0f70bcaf-d422-4573-adc6-a3d857b53695" alt="Image 7" height="250" width="400"/>
        <figcaption></figcaption>
    </figure>
</body>

<br><br>
<h2>TECNOLOGIAS UTILIZADAS</h2>

<strong>Back end</strong>
<li>Java
<li>MySQL
<li>Jdbc

<strong>Front end</strong> 
<li>JavaFX
<li>FXML
<li>SceneBuilder<h2/><br>

<h2>COMO EXECUTAR O PROJETO</h2>

<strong>Pré requisitos: JAVA 21</strong>

<li>clonar o repositório "<i>https://github.com/Andre-LSousa/MyApp-installation-package</i>"<br>
<li>instalar o Java em "<i>https://www.oracle.com/technetwork/java/javase/downloads/index.html</i>" e extrair os arquivos compactados para a pasta "<i>C:\Program Files\Java</i>" <br>
<li>configure a variavel de ambiente "<i>JAVA_HOME</i>" com o caminho (ex: "<i>C:\Program Files\Java\"SEU JDK")</i>", e verique junto a este procedimento, em "<i>editar a variavel de ambiente</i>", se a variavel de ambiente "<i>%JAVA_HOME%\bin</i>" está relacionada na lista, caso não esteja, crie uma nova variavel. 
<li>extraia o arquivo "<i>openjfx-21.0.6_windows-x64_bin-sdk.zip</i>" e copie para a pasta "<i>C:\java-libs</i>"<br>
<li>configure a variavel de ambiente, "<i>PATH_TO_FX</i> para <i>(ex: C:\java-libs\javafx-sdk\lib)</i>"<br>
<li>copie o "<i>mysql-connector</i>" da pasta "<i>workshop-javafx-jdbc_lib</i>" e cole em "<i>C:\java-libs\javafx-sdk\lib</i>"<br>
<li>copie o arquivo "<i>JAR & db.properties</i>" para uma nova pasta (ex. "<i>MyApp</i>")<br>
<li>no prompt de comando utilize o comando "<i>cd \MyApp</i>" para acessar os arquivos instalados na pasta e utilize o comando, "<i>java --module-path %PATH_TO_FX% --add-modules javafx.controls,javafx.fxml -cp workshop-javafx-jdbc.jar application.Main</i>", para iniciar a aplicação.

<br><br>
AUTOR<br>
André Luiz de Sousa<br>
www.linkedin.com/in/andré-luiz-de-souza-0a061893
