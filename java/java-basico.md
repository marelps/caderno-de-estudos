Anotações feitas para estudo do curso "Ambiente de desenvolvimento Java" criado pela DIO e disponbilizado no bootcamp do Santander com a DIO

# IDE - Integrated Development Environment

Ou também conhecida como Ambiente de Desenvolvimento Integrado.
Um software que dispõe de recursos que auxilia nosso desenvolvimento
- Aceleração na escreita com auto-complete ou intellisense
- Formatação de palavras e blocos de códigos
- Análise de erro de sintaxe
- Compilação de programa
- Depuração (acompanhamento) de execução do programa

Depuração: Analisar, acompanhar cada etapa das nossas implementações

Cada IDE tem recursos comuns ou plugins específicos para auxiliar na agilidade de desenvolvimento, como:
- Visual Studio Code
    - É um editor de texto muito simples e interativo que conta com inúmeras extensões, temas variados e integração com tecnologias como NodeJS e Java. Comparando-se em perfomance, o VS Code demonstra um grande desempenho de inicialização codificanção e execução dos programas desenvolvidos. 
- NetBeand
- Eclipse
    - Interace simples, plugins para recursos adicionais, atalhos para operações de menu e de escrita e para quem trabalha com Java Swing você pode adionar o plugin WindowBuilder que tem uma interface gráfica para criar as tels gerando o código de layout para o desenvolvedor
- IntelliJ
    - Plataforma de código aberto para criação de IDEs mas nem todos os recursos são disponíveis de forma gratuita. Pode salvar arquivo, encode padrão UFT-8 e sugestões que vão surgindo ao longo da nossa interação com a ferramenta.

### Resumo:
- Eclipse: Mais utilizada no ambiente corporativo com interface bem interativa.
- NetBeans: Utilizada mais em ambiente acadêmico e com versão de menu e assistentes em português.
- IntelliJ: Ofereça muitos recursos de inteligência para agilidade de nosso desenvolvimento com sugestões de açoes bem assertivas.
- VS Code: Hoje muito utilizada por desenvolvedores que já atuam com NodeJs ou plataformas de front-end.

### Perguntas:
- O que são workspaces?
- Definir a JDK na IDE
- Criar/abrir um projeto Java
- Criar/importar um projeto Maven
- Conhecer os principais atalhos
- Code Snippet
    - O que são? Quais os aspectos?
- Executar/depurar nosso programa
- Conhecer alguns atalhos

**Maven** é uma ferramenta de automaç~çao de compilação utilizada primariamente em projetos Java, mas hoje também é utilizada para construir e gerenciar projetos escritos em C#, Ruby, Scala e outras linguagens.

## Atalhos
Todas as IDEs tem combinações de comandos que facilitam para criação de arquivo, digitação de códigos, localização e execução das classes em nosso programa, além de comando já pré-definidos de linhas de código (code snippet)

**Code Snippets** numa tradução livre seria como "retalhos de código", são pedaços de código pré-fabricados e parametrizáveis que podemos inserir em nossa aplicação.

| Comando | Eclipse | IntelliJ |
|-------|-------|-------|
Cria o método principal main | main, ctrl + espaço, enter | psvm |
Localiza recurso/arquivo | ctrl + shift + R | ctrl + shift + N |
Método de impressão no console | sysout, ctrl + espaço | sout |
Renomeando variável ou método | alt + shift + R | shift + F6
Localizar a utilização de um método | ctrl + shift + G | alt + F7 |
Entrar na implementação do método | ctrl + click | ctrl + click