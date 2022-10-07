# Dio_Quebec_Java_Digital
## Iniciando curso da Dio - Quebec_Java_Digital
Curso Basico com 93hrs de estudo

## Links úteis
[Markdown auxilio na sintax, para futuras documentações](https://www.markdownguide.org/basic-syntax/)

Desafio de projeto sobre Git/GitHub da DIO
Repositório criado para o desafio de projeto.

## Windows
### :heavy_check_mark: Instalação JDK Zulu

Aqui no windows, vamos fazer o download do OpenJDK Zulu. As compilações do Azul Zulu do OpenJDK são compilações de código aberto, testadas pelo TCK e certificadas do OpenJDK. O Zulu Blue está disponível para uma ampla variedade de plataformas de hardware e sistemas operacionais. A documentação do Azul Zulu inclui notas de lançamento, um guia de instalação e licenças de terceiros.

1. Entre no [SITE AZUL](https://www.azul.com/downloads/?package=jdk)

2. Faça o download do arquivo .zip do JDK 11.0.11+9. No meu caso, o x86 64-bit

3. Vá no drive C://Arquivo de Programas

4. Caso não tenha um diretório com o nome Java, crie

5. Entre neste diretório e descompacte o download do zip JDK Zulu 11.0.11+9 neste diretório

6. Vamos configurar o ambiente JAVA_HOME:
    - 6.1 Menu iniciar -> Editar as varáveis de ambiente do sistema
    - 6.2 Irá abrir a janela Propriedades do Sistema, escolha a aba Avançado, em seguida clique em variáveis de Ambiente
    - 6.3 Na janela Variáveis de Ambiente, crie um novo Variáveis do sistema
    - 6.4 Abrirá uma jabela: Nova Variável de Sistema.
    - 6.5 Nome da variável: JAVA_HOME
    - 6.6 Valor da variável: em seguida OK.
        - O valor da variável é o caminho do diretório que você descompactou o zip JDK Zulu 11.0.11+9 no passo 5
    - 6.7 Na mesma janela Variáveis do Sistema, localize a variável Path, selecione e clique a opção Editar...
    - 6.8 Clique na opção Novo e cole o mesmo caminho do passo 5 acrescentando \bin
    - 6.9 Continue com o path selecionado e clique na opção Mover para Cima até chegar no topo

7. Pronto, finalizada a configuração. Próximo passo é conferir se está instalado tudo certinho

8. Abra o Prompt de Comando: Menu iniciar -> cmd

9. Vamos conferir mais uma vez se o Java está instalado na nossa máquina
    - java -version
    - Créditos: DevSuperior


### :heavy_check_mark: Instalação Eclipse
1. Acessar o site oficial do [ECLIPSE](https://www.eclipse.org/downloads/)

2. Fazer o download do instalador

3. Escolha segunda a opção: Eclipse IDE for Enterprise Java and Web Developers Link de download para Windows

4. Clique no folder da primeira opção (Java 11 + VM) e selecione o JDK que instalamos na nossa máquina

5. Mantenha as opções "create start menu entry" e "create desktop shortcut"

6. Install

7. Accept now

8. Launch

9. Pronto, intalação concluída

#

### :heavy_check_mark: Instalação IntelliJ IDEA Community
1. Entre no site ofical do [INTELLIJ](https://www.jetbrains.com/idea/download/#section=windows)

2. Escolha a opção Community e faça o download

3. Siga com next

4. Na opção Installation Options, deixe selecionado as opções: 
    - 4.1 64-bit launcher (caso seu sistema seja 64-bit, caso não, selecione 32-bit)
    - 4.2 Add "Open Folder as Project" 
    - 4.3 .java - .groovy - .kt - .kts 
    - 4.4 Add lauchers dir to the PATH 
    - 4.5 Next

5. Install

6. Para finalizar a instalação, escolha a opção reebot later

7. Com o IntelliJ já instalado, vamos iniciar:
    - 7.1 Aceite os termos: I confirm that I have... >> Confirm
    - 7.2 Data Sharing >> Send Anonymous Statistics

8. IDE pronta para uso!

#

### :heavy_check_mark: Instalação Git
1. Entre no site ofical do [GIT](https://git-scm.com/downloads)

2. Escolha a opção Windows e o instalador será baixado automáticamente

3. Mantenha as opções pré selecionadas e siga com Next

4. Install

5. Antes de finaizar a instalação, selecione a opção Lauch Git Bash

6. Ao finalizar o passo 5, irá abrir o Git Bash

7. Agora vamos fazer as configurações iniciais:

8. Confirme se o git realmente está instalado:
    - git --version

9. Vamos começar as configurações iniciais:
    - 9.1 Configurar o nome de usuário
        - git config --global user.name "Seu nome"
    - 9.2 Configurar o endereço de e-mail:
        - É de suma importância que o ENDEREÇO DE E-MAIL SEJA O MESMO DO GITHUB afim de evitar conflitos!
        - git config --global user.email seuemail@email.br
    - 9.3 Vamos conferir a lista de configurações:
        - git config --list
       
10. Pronto, git instalado e configurado com sucesso!
