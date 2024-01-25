# Aprenda Python PT-BR
 
- Python é uma linguagem de programação popular.

-  Python pode ser usado em um servidor para criar aplicações web.

--------------------------------------------
    Abaixo à instrução para você instalar no Windows
--------------------------------------------

# Introdução ao Python

## O que é Python?

-  Python é uma linguagem de programação popular. Foi criado por Guido van Rossum, e lançado em 1991.

## É utilizado para:

-  desenvolvimento web (server-side),
-  desenvolvimento de software,
-  matemática
-  script do sistema.

## O que o Python pode fazer?

-  Python pode ser usado em um servidor para criar aplicações web.
-  Python pode ser usado junto com o software para criar fluxos de trabalho.
-  Python pode se conectar a sistemas de banco de dados. Ele também pode ler e modificar arquivos.
-  Python pode ser usado para lidar com big data e realizar matemática complexa.
-  Python pode ser usado para prototipagem rápida, ou para desenvolvimento de software pronto para produção.

## Por que Python?

-  Python funciona em diferentes plataformas (Windows, Mac, Linux, Raspberry Pi, etc).
-  Python tem uma sintaxe simples semelhante à língua inglesa.
-  Python tem sintaxe que permite aos desenvolvedores escrever programas com menos linhas do que algumas outras linguagens de programação.
-  Python é executado em um sistema interpretador, o que significa que o código pode ser executado assim que é escrito. Isso significa que a prototipagem pode ser muito rápida.
-  Python pode ser tratado de forma processual, orientada a objetos ou funcional.

## Saiba mais

-  A versão principal mais recente do Python é o Python 3, que usaremos neste tutorial. No entanto, o Python 2, apesar de não ser atualizado com nada além de atualizações de segurança, ainda é bastante popular.
-  Neste tutorial Python será escrito em um editor de texto. É possível escrever Python em um Ambiente de Desenvolvimento Integrado, como Thonny, Pycharm, Netbeans ou Eclipse, que são particularmente úteis ao gerenciar coleções maiores de arquivos Python, eu costumo usar Visual Code.

## Sintaxe Python em comparação com outras linguagens de programação

-  Python foi projetado para legibilidade, e tem algumas semelhanças com a língua inglesa com influência da matemática.
-  Python usa novas linhas para completar um comando, ao contrário de outras linguagens de programação que geralmente usam ponto-e-vírgula ou parênteses.
-  Python depende de recuo, usando espaço em branco, para definir o escopo; como o escopo de loops, funções e classes. Outras linguagens de programação geralmente usam colchetes para essa finalidade.

--------------------------------------------
De:

    https://www.w3schools.com/python

--------------------------------------------

# Instalando o Python

1 - Digite no google > python

<br>

2 - [Site oficial - Python.org](https://www.python.org/downloads/windows/)

<br>

3 - Downloads > Windows

<br>

4 - Recomendação de versão 3.7.8
  
-  Desça até achar

       Python 3.7.8 - June 27, 2020

       Note that Python 3.7.8 cannot be used on Windows XP or earlier.

      Link de Download Direto > [Download Windows x86-64 executable installer](https://www.python.org/ftp/python/3.7.8/python-3.7.8-amd64.exe)

<br>

5 - Instalação

- Ao iniciar a instalação do Python 3.7.8 Selecione a opção embaixo "Add Python 3.7 to PATH"

  Se não quando for exercutar seu .py terá problema de conexão com seus arquivos.

- Click em Customizar a instalação

  Aqui você da próximo em Recursos opcionais que já estará tudo selecionado automaticamente.

- Em Opções avançadas

  Ative todas opções que estiverem desativadas.

- Instale e pode dar close na instalação finalizada.

<br>

6 - Após fechar o instalador 
  
- Aperte Ctrl + R e escreva dentro do terminal " python ".
  
       Lhe mostrará se está instalado e qual versão.


--------------------------------------------

# Agora é hora do exercício

## Guia de início rápido do Python

- Vamos escrever nosso primeiro arquivo Python, chamado helloworld.py, que pode ser feito em qualquer editor de texto.

      Eu irei usar o Visual Code

  [https://code.visualstudio.com](https://code.visualstudio.com/)

- Para facilitar ative a exibição do nome de extensão do arquivo.

<img width="500" src="https://github.com/brunomunarolo/Introducao-Python/assets/113137632/60d829db-f2e5-43bb-a6e6-93e6e057ea0e">

<br>

<br>

- Ficaria assim:

<img width="90" src="https://github.com/brunomunarolo/Introducao-Python/assets/113137632/8db7dac9-2410-44be-bcbb-c04e5a50467d">


- Dentro do seu arquivo escreva e execute:

      print("Hello, World!")

<br>

<img width="500" src="https://github.com/brunomunarolo/Introducao-Python/assets/113137632/191715f9-6c63-4eaa-bbdf-8d113933e5dc">

- A saída deve ler:

      Hello, World!

## Parabéns, você escreveu e executou seu primeiro programa Python.

--------------------------------------------

<br>

<br>

# Linha de comando do Python

- Para testar uma pequena quantidade de código em python, às vezes é mais rápido e fácil não escrever o código em um arquivo. Isso é possível porque o Python pode ser executado como uma linha de comando em si.

- Digite o seguinte na linha de comando do Windows, Mac ou Linux:

      C:\Users\Your Name>python

- Ou, se o comando "python" não funcionou, você pode tentar "py":

      C:\Users\Your Name>py

- A partir daí, você pode escrever qualquer python, incluindo nosso exemplo hello world do início do tutorial:

      C:\Users\Your Name>python
      Python 3.6.4 (v3.6.4:d48eceb, Dec 19 2017, 06:04:45) [MSC v.1900 32 bit (Intel)] on win32
      Type "help", "copyright", "credits" or "license" for more information.
      >>> print("Hello, World!")

- Que escreverá "Olá, Mundo!" na linha de comando:

      C:\Users\Your Name>python
      Python 3.6.4 (v3.6.4:d48eceb, Dec 19 2017, 06:04:45) [MSC v.1900 32 bit (Intel)] on win32
      Type "help", "copyright", "credits" or "license" for more information.
      >>> print("Hello, World!")
      Hello, World!

- Sempre que você terminar na linha de comando python, você pode simplesmente digitar o seguinte para sair da interface da linha de comando python:

      exit()



--------------------------------------------

<br>

# Sintaxe do Python

- Recuo refere-se aos espaços no início de uma linha de código.

- Onde em outras linguagens de programação o recuo no código é para legibilidade apenas, o recuo em Python é muito importante.

- Python usa recuo para indicar um bloco de código.

### Exemplo
  	 
      if 5 > 2:
       print("Five is greater than two!")

<br>

- Python lhe dará um erro se você pular o recuo:

### Exemplo
 
Erro de sintaxe:

    if 5 > 2:
    print("Five is geater than two!")

<br>

- O número de espaços depende de você como programador, o uso mais comum é quatro, mas tem ser pelo menos um.

### Exemplo

    if 5 > 2:
     print("Five is greater than two!")
    if 5 > 2:
        print("Five is  greater than two!")

<br>

- Você tem que usar o mesmo número de espaços no mesmo bloco de código, caso contrário, o Python lhe dará um erro:

### Exemplo
	
Erro de sintaxe:
	
    if 5 > 2:
    print("Five is greater than two!")
        print("Five is greater than two!")

<br>

## Variáveis do Python

- No Python, as variáveis são criadas quando você atribui um valor a ela:

<br>

### Exemplo

Variáveis em Python:
	
	x = 5
	y = "Hello, World!"

<br>

- Python não tem nenhum comando para declarar uma variável.

- Você aprenderá mais sobre variáveis no capítulo Variáveis do Python.

[Variáveis do Python](https://www.w3schools.com/python/python_variables.asp)

<br>

# Comentários

- Python tem capacidade de comentários para fins de documentação no código.

- Os comentários começam com um #, e o Python renderizará o restante da linha como um comentário:

	Exemplo
	<br>
	Cometários em Python:
	
	#This is a comment.
	print("Hello, Worlds!")







  

--------------------------------------------
