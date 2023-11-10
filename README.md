# O que um iniciante em Java precisa saber — PARTE I
Os desafios de um principiante na linguagem podem ser amenizados com algumas dicas!

##

## Preparando o PC para o desenvolvimento em Java
Pode parecer um detalhe óbvio, porém, é comum que a maioria das pessoas não saibam que é necessária a instalação de algumas ferramentas para que seja possível programar nessa linguagem, e não se trata somente da IDE escolhida, aliás, adiante abordaremos algumas opções de IDE e suas características.
##
## Primeiramente, deve-se instalar o Java Development Kit (JDK):

O Java Development Kit (JDK) é um conjunto de ferramentas, utilitários e bibliotecas que permite o desenvolvimento de aplicações Java. Ele inclui o Java Runtime Environment (JRE), que é necessário para executar aplicações Java, e também contém o Java Compiler (javac) e outras ferramentas essenciais para desenvolvedores Java, o que inclui o compilador necessário para transformar seu código-fonte em bytecode executável. Certifique-se de instalar o JDK apropriado para a sua plataforma antes de começar a desenvolver em Java.
##
## As principais componentes do JDK incluem:

`Java Compiler (javac)`: O compilador Java converte o código-fonte Java (arquivos com extensão .java) em bytecode Java (arquivos com extensão .class), que é executado na Máquina Virtual Java (JVM).

`Java Virtual Machine (JVM)`: A JVM é uma máquina virtual que executa o bytecode Java. Ela fornece a camada de abstração que permite que as aplicações Java sejam executadas em diferentes plataformas sem a necessidade de recompilação.

`Java Runtime Environment (JRE)`: O JRE inclui a JVM e bibliotecas necessárias para a execução de aplicações Java. É suficiente para executar aplicações Java, mas não para desenvolver.

`Java API Libraries`: O JDK inclui as bibliotecas Java padrão (também conhecidas como Java API) que fornecem funcionalidades para tarefas comuns, como manipulação de strings, entrada/saída de dados, networking, entre outras.
##
## Como instalar:

* Visite o site oficial da Oracle ou do OpenJDK para baixar a versão mais recente do JDK que seja LPS (versão de longo período de suporte).
* Siga as instruções de instalação fornecidas para o seu sistema operacional (Windows, macOS, ou Linux).
* Ao baixar o arquivo ZIP, caso não haja uma pasta “Java” na pasta “Arquivos de Programas” do computador, basta que seja criada uma para que os arquivos do ZIP sejam armazenados lá.
##
## Depois, deve-se configurar as variáveis de ambiente JAVA_HOME e PATH:

No painel de controle do Windows, após acessar as configurações das variáveis de ambiente, é possível verificar se nas “Variáveis do Sistema” existe a “JAVA_HOME” , caso não haja, será preciso adiciona-la com esse nome e em seu valor será inserido o diretório dos arquivos da pasta do JDK que colocamos nos “Arquivos de Programas” — será algo parecido com “C:\Program Files\Java\versão_que_você_baixou” — .

Posteriormente, ao encontrar a variável “Path” nas “Variáveis do Sistema”, essa deverá ser editada, adicionando um novo diretório que será o mesmo usado na variável “JAVA_HOME”.

No Linux ou macOS, você pode editar o arquivo .bashrc ou .zshrc para configurar as variáveis.
##
## Teste da instalação:

Para garantir que a instalação foi efetuada com sucesso basta abrir um terminal ou prompt de comando e digitar java -version para verificar se o JDK está instalado corretamente. Em seguida, digitar javac -version para garantir que o compilador Java também esteja instalado.
##
## E por fim, existe a opção de instalar um ambiente de desenvolvimento integrado (IDE):

São várias as opções de IDEs para Java. Algumas das mais populares são:

* Eclipse: [Download Eclipse](https://www.eclipse.org/downloads/);
* IntelliJ IDEA: [Download IntelliJ IDEA](https://www.jetbrains.com/idea/download/);
* NetBeans: [Download NetBeans](https://netbeans.apache.org/front/main/download/);
  
Os três ambientes de desenvolvimento integrado (IDEs) citados têm muitas semelhanças em termos de funcionalidades básicas, como edição de código, depuração e suporte a versões de controle de código. No entanto, há algumas diferenças notáveis que podem influenciar a escolha entre eles. Aqui estão algumas distinções chave:

`Eclipse:`

Licença: Eclipse é um IDE de código aberto e é amplamente utilizado em projetos de código aberto.

Flexibilidade: É conhecido por ser altamente configurável e extensível. Existem muitos plugins disponíveis para estender suas funcionalidades.

Ecossistema: É usado em uma variedade de linguagens de programação, não apenas Java. Eclipse é frequentemente utilizado para o desenvolvimento em C/C++, PHP, e outras linguagens.

Comunidade: Tem uma grande comunidade de usuários e uma ampla base de plugins.

`IntelliJ IDEA:`

Licença: IntelliJ IDEA tem uma versão gratuita (Community) e uma versão paga (Ultimate) com recursos adicionais. A versão Ultimate oferece suporte a uma variedade de linguagens além de Java.

Produtividade: É elogiado por sua interface de usuário intuitiva e recursos avançados que aumentam a produtividade do desenvolvedor.

Refatoração: Oferece poderosas ferramentas de refatoração e análise estática de código.

Spring Framework: Tem uma integração profunda com o Spring Framework, o que o torna uma escolha popular para desenvolvimento Java empresarial.

`NetBeans:`

Licença: NetBeans é um IDE de código aberto patrocinado pela Apache Software Foundation.

Integração: Oferece integração nativa com muitas tecnologias Java, como JavaFX, Maven e suporte a Web.

Facilidade de Uso: É conhecido por sua simplicidade e facilidade de uso, sendo uma boa escolha para desenvolvedores iniciantes.

Java EE: Possui suporte forte para o desenvolvimento de aplicativos Java Enterprise Edition (Java EE).

A escolha entre esses IDEs muitas vezes se resume às preferências pessoais do desenvolvedor, ao tipo de projeto em que estão envolvidos e às características específicas que cada IDE oferece. Muitos desenvolvedores experimentam mais de um IDE antes de decidir qual se adapta melhor às suas necessidades e preferências.
##
## Possível configuração do IDE:

Após instalar o IDE, pode ser solicitado o caminho para o JDK. O diretório será aquele usado nas configurações anteriores — algo parecido com “C:\Program Files\Java\versão_que_você_baixou” — .
##
## Tudo pronto!
Agora, seu ambiente de desenvolvimento Java está apito para começar a criar e executar programas Java. Lembrando que certificar-se de consultar a documentação do JDK, do IDE escolhido e de outras bibliotecas ou ferramentas que possam ser necessárias é importante.
##
Referência: FURGERI, Sérgio. Java : Ensino didático: desenvolvimento e implementação de aplicações : compatível com versão 9 e jshell com netbeans. São Paulo: Érica, 2018.


<img align="center" alt="Sa-gif" height="60" width="60" src="https://cdn.discordapp.com/attachments/1160307536470233233/1162434580607926332/hi.gif?ex=653bec91&is=65297791&hm=0ee88565f40455f9823b5fe69531872cd623fa16492a736570d9874d51341ab7&"> Sabrina Mariha, uma desenvolvedora em desenvolvimento.
