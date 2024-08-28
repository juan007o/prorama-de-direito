
AULA 1

nuvem - Ambiente não físico que permite armazenar dados pessoais
informação - conjunto organizado de dados e conhecimento que constituem referencias sobre um acontecimento ou fato
dados - dados são valores atribuídos a algo. Estes valores não precisam ser necessariamente números. Eles também podem ser, por exemplo, conceitos ou posições em um mapa.
  Um banco de dados é uma coleção organizada de informações - ou dados - estruturadas, normalmente armazenadas eletronicamente em um sistema de computador.
  servidor - são computadores ou sistemas computacionais que atendem requisições de dispositivos clientes, através de uma ou mais redes (locais ou remotas), capazes de executar aplicações (programas), prover processamento e/ou capacidade de armazenamento de dados.


AULA 2

EXEMPLOS DE FORMATO
ABERTO X PROPRIETÁRIOS

Formatos Proprietários:

.docx (Microsoft Word):

Descrição: Formato de documento de texto criado pela Microsoft. Usado para documentos que podem incluir texto formatado, imagens, tabelas e outros elementos.
Implications: É amplamente utilizado e suportado por muitos aplicativos de processamento de texto, mas a especificação completa é controlada pela Microsoft, o que pode limitar a interoperabilidade com softwares que não são da Microsoft.
.xlsx (Microsoft Excel):

Descrição: Formato de planilha de dados utilizado pelo Microsoft Excel. Permite a criação de tabelas, gráficos, fórmulas e muito mais.
Implicações: Semelhante ao .docx, o .xlsx é suportado por muitos aplicativos, mas sua especificação é proprietária, o que pode causar problemas de compatibilidade com ferramentas que não sejam da Microsoft.
.psd (Adobe Photoshop):

Descrição: Formato de arquivo de imagem utilizado pelo Adobe Photoshop. Permite a edição de imagens com múltiplas camadas, filtros e efeitos.
Implicações: O formato é ideal para edição de imagens complexas, mas é restrito ao software da Adobe, limitando a abertura e edição de arquivos em outros programas.

Formatos Abertos:

.pdf (Portable Document Format):

Descrição: Formato criado pela Adobe, mas cujas especificações são publicamente disponíveis. É usado para documentos que podem ser visualizados e impressos de maneira consistente em diferentes dispositivos.
Implicações: O PDF é amplamente compatível com diversos dispositivos e plataformas, promovendo a preservação do layout e do conteúdo. No entanto, a versão básica do PDF pode não suportar todas as funcionalidades de edição avançada.
.csv (Comma-Separated Values):

Descrição: Formato de texto simples utilizado para armazenar dados tabulares. Cada linha representa uma linha de dados e as colunas são separadas por vírgulas (ou outro delimitador).
Implicações: É um formato amplamente aceito e fácil de ler e escrever com a maioria dos softwares de processamento de dados. No entanto, não suporta formatação avançada ou dados hierárquicos complexos.
.odt (Open Document Text):

Descrição: Formato de documento baseado em padrões abertos, utilizado por softwares como LibreOffice e OpenOffice.
Implicações: Oferece uma alternativa ao .docx com especificações abertas, facilitando a interoperabilidade entre diferentes suites de escritório. É uma boa escolha para garantir acesso e edição sem depender de software proprietário.
.json (JavaScript Object Notation):

Descrição: Formato leve de troca de dados que é fácil de ler e escrever para humanos e fácil de analisar e gerar para máquinas. Utilizado frequentemente para dados estruturados e APIs.
Implicações: Promove a interoperabilidade entre sistemas e é amplamente utilizado na troca de dados entre aplicações web e servidores.

 Implicações Relacionadas a Dados Públicos
**1. Interoperabilidade:

Formatos Proprietários: Dados públicos armazenados em formatos proprietários podem enfrentar desafios de interoperabilidade. Isso pode dificultar o acesso e a reutilização dos dados por outras organizações ou pelo público geral, especialmente se o software necessário para acessar esses dados não for de fácil acesso ou for caro.
Formatos Abertos: O uso de formatos abertos facilita a interoperabilidade e o compartilhamento de dados. Dados públicos em formatos abertos são mais acessíveis e podem ser utilizados por uma gama mais ampla de usuários e sistemas.
**2. Transparência e Acesso:

Formatos Proprietários: A falta de especificação aberta pode criar barreiras ao acesso e compreensão dos dados. Isso pode comprometer a transparência e a capacidade dos cidadãos de analisar e utilizar os dados públicos.
Formatos Abertos: Promovem maior transparência e acesso fácil aos dados, alinhando-se aos princípios de governo aberto e acessibilidade. Dados em formatos abertos podem ser facilmente visualizados e manipulados, incentivando maior participação e análise pública.
**3. Preservação a Longo Prazo:

Formatos Proprietários: Dados em formatos proprietários podem enfrentar riscos de obsolescência à medida que os softwares que os suportam se tornam menos comuns ou são descontinuados. Isso pode levar à perda de acesso a longo prazo.
Formatos Abertos: Oferecem maior segurança para a preservação a longo prazo, uma vez que suas especificações são abertas e documentadas, permitindo a criação de ferramentas para acessar e utilizar os dados mesmo após muitos anos.
**4. Custo e Recursos:

Formatos Proprietários: Pode haver custos associados à aquisição de software específico para acessar ou manipular dados em formatos proprietários. Isso pode ser uma limitação para organizações com recursos financeiros limitados.
Formatos Abertos: Geralmente, não exigem software especializado, o que pode reduzir custos e tornar os dados mais acessíveis para uma variedade de usuários e organizações.



AULA 3
Python
Descrição:

Linguagem de Programação: Python é uma linguagem de alto nível, interpretada e orientada a objetos, conhecida por sua sintaxe clara e legível.
Usos Comuns: Desenvolvimento web, automação, análise de dados, aprendizado de máquina, scripting, desenvolvimento de aplicativos de desktop e muito mais.
Características Principais:

Sintaxe Simples: A sintaxe do Python é simples e fácil de ler, o que a torna uma excelente escolha para iniciantes.
Interpretação: Python é uma linguagem interpretada, o que significa que o código é executado linha por linha, facilitando a depuração.
Bibliotecas e Frameworks: Python possui uma vasta gama de bibliotecas e frameworks (como Django, Flask, Pandas, NumPy) que simplificam o desenvolvimento de aplicações e análise de dados.
Tipagem Dinâmica: As variáveis em Python não precisam ser declaradas com um tipo específico; o tipo é inferido em tempo de execução.
Exemplo de Código:

python

def saudacao(nome):
    return f"Olá, {nome}!"

print(saudacao("Mundo"))
2. Java
Descrição:

Linguagem de Programação: Java é uma linguagem de alto nível, compilada e orientada a objetos, famosa por sua portabilidade e robustez.
Usos Comuns: Desenvolvimento de aplicações empresariais, sistemas integrados, aplicativos Android, e sistemas de backend de grande escala.
Características Principais:

Compilação e JVM: Java é compilado para bytecode, que é executado na Java Virtual Machine (JVM). Isso permite que o mesmo código Java seja executado em diferentes plataformas sem modificação.
Tipagem Estática: Java é estaticamente tipada, o que significa que os tipos de variáveis devem ser declarados explicitamente e são verificados em tempo de compilação.
Orientação a Objetos: Java é fortemente orientada a objetos, com suporte completo a conceitos como herança, encapsulamento e polimorfismo.
Gerenciamento de Memória: Java usa coleta de lixo (garbage collection) para gerenciar a memória automaticamente.
Exemplo de Código:

java

public class Saudacao {
    public static void main(String[] args) {
        System.out.println(saudacao("Mundo"));
    }
    
    public static String saudacao(String nome) {
        return "Olá, " + nome + "!";
    }
}
3. JavaScript
Descrição:

Linguagem de Programação: JavaScript é uma linguagem de programação interpretada e orientada a objetos, amplamente usada para desenvolvimento web.
Usos Comuns: Desenvolvimento front-end para websites (interatividade e manipulação de DOM), desenvolvimento de back-end (com Node.js), e criação de aplicativos móveis (com frameworks como React Native).
Características Principais:

Execução no Navegador: JavaScript é executado diretamente no navegador web, permitindo a criação de páginas web dinâmicas e interativas.
Tipagem Dinâmica: Semelhante ao Python, JavaScript também tem tipagem dinâmica, onde os tipos são inferidos em tempo de execução.
Orientação a Objetos e Funcional: JavaScript suporta programação orientada a objetos (através de protótipos) e também programação funcional.
Event-Driven: É frequentemente utilizado para criar aplicações baseadas em eventos e manipular eventos do usuário em páginas web.
Exemplo de Código:

javascript

function saudacao(nome) {
    return `Olá, ${nome}!`;
}

console.log(saudacao("Mundo"));
Comparação Resumida
Sintaxe e Tipagem:

Python: Sintaxe simples e legível; tipagem dinâmica.
Java: Sintaxe mais rígida e detalhada; tipagem estática.
JavaScript: Sintaxe flexível e dinâmica; tipagem dinâmica.
Execução:

Python: Interpretada, executada em um ambiente de tempo de execução específico.
Java: Compilada para bytecode, executada na JVM, permitindo portabilidade entre plataformas.
JavaScript: Interpretada e executada no navegador (ou no servidor com Node.js).
Usos e Contexto:

Python: Versátil, adequado para uma ampla gama de aplicações, desde scripts simples até sistemas complexos.
Java: Ideal para aplicações empresariais e sistemas que exigem robustez e portabilidade.
JavaScript: Principalmente para desenvolvimento web, tanto front-end quanto back-end.

python
def saudacao(nome):
    return f"Olá, {nome}!"

print(saudacao("Mundo"))







java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Olá, Mundo!");
    }
}


javaScript

console.log("Olá, Mundo!");
