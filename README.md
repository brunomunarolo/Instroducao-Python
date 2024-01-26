# Aprenda Python PT-BR

- Python é uma linguagem de programação popular.

- Python pode ser usado em um servidor para criar aplicações web.

- Lembre-se de abrir um editor de códigos para seguir junto ao tutorial.

- Use o sumário ao lado para se localizar.

<img src="https://github.com/brunomunarolo/Introducao-Python/assets/113137632/2c37ab24-6a37-4e5f-8cd9-6ece0ec1ba72)">

--------------------------------------------

- Logo a frente instalação do Python

--------------------------------------------

<br>

# Introdução ao Python

## O que é Python?

- Python é uma linguagem de programação popular, criada por Guido van Rossum e lançada em 1991.

## É utilizado para:

- desenvolvimento web (server-side),
- desenvolvimento de software,
- matemática,
- script do sistema.

## O que o Python pode fazer?

- Python pode ser usado em um servidor para criar aplicações web.
- Python pode ser usado junto com o software para criar fluxos de trabalho.
- Python pode se conectar a sistemas de banco de dados. Ele também pode ler e modificar arquivos.
- Python pode ser usado para lidar com big data e realizar matemática complexa.
- Python pode ser usado para prototipagem rápida ou para desenvolvimento de software pronto para produção.

## Por que Python?

- Python funciona em diferentes plataformas (Windows, Mac, Linux, Raspberry Pi, etc).
- Python tem uma sintaxe simples semelhante à língua inglesa.
- Python tem uma sintaxe que permite aos desenvolvedores escrever programas com menos linhas do que algumas outras linguagens de programação.
- Python é executado em um sistema interpretador, o que significa que o código pode ser executado assim que é escrito. Isso significa que a prototipagem pode ser muito rápida.
- Python pode ser tratado de forma processual, orientada a objetos ou funcional.

## Saiba mais

- A versão principal mais recente do Python é o Python 3, que usaremos neste tutorial. No entanto, o Python 2, apesar de não ser atualizado com nada além de atualizações de segurança, ainda é bastante popular.
- Neste tutorial, Python será escrito em um editor de texto. É possível escrever Python em um Ambiente de Desenvolvimento Integrado, como Thonny, Pycharm, Netbeans ou Eclipse, que são particularmente úteis ao gerenciar coleções maiores de arquivos Python; eu costumo usar o Visual Studio Code.

## Sintaxe Python em comparação com outras linguagens de programação

- Python foi projetado para legibilidade e tem algumas semelhanças com a língua inglesa com influência da matemática.
- Python usa novas linhas para completar um comando, ao contrário de outras linguagens de programação que geralmente usam ponto-e-vírgula ou parênteses.
- Python depende de recuo, usando espaço em branco, para definir o escopo; como o escopo de loops, funções e classes. Outras linguagens de programação geralmente usam colchetes para essa finalidade.

--------------------------------------------
De:
https://www.w3schools.com/python
--------------------------------------------

# Instalando o Python

1 - Digite no Google > python

2 - [Site oficial - Python.org](https://www.python.org/downloads/windows/)

3 - Downloads > Windows

4 - Recomendação de versão 3.7.8

   - Desça até achar

    Python 3.7.8 - June 27, 2020

    Note que Python 3.7.8 não pode ser usado no Windows XP ou anterior.

    Link de Download Direto > [Download Windows x86-64 executable installer](https://www.python.org/ftp/python/3.7.8/python-3.7.8-amd64.exe)

5 - Instalação

   - Ao iniciar a instalação do Python 3.7.8, selecione a opção embaixo "Add Python 3.7 to PATH"

   - Se não fizer isso, ao executar seu .py, terá problema de conexão com seus arquivos.

   - Clique em Personalizar a instalação.

   - Aqui você dá próximo em Recursos opcionais que já estará tudo selecionado automaticamente.

   - Em Opções avançadas, ative todas as opções que estiverem desativadas.

   - Instale e pode dar close na instalação finalizada.

6 - Após fechar o instalador

   - Aperte Ctrl + R e escreva dentro do terminal "python".

   - Isso mostrará se está instalado e qual versão.

<img src="https://github.com/brunomunarolo/Introducao-Python/assets/113137632/34ed19dd-fcfd-463c-9e93-8c1777688da7">

<br>

--------------------------------------------

<br>

# Agora é hora do exercício

## Guia de início rápido do Python

- Vamos escrever nosso primeiro arquivo Python, chamado helloworld.py, que pode ser feito em qualquer editor de texto.

      Eu irei usar o Visual Studio Code.

  [https://code.visualstudio.com](https://code.visualstudio.com/)

- Se você não quiser instalar, pode seguir com o Terminal ou outro software.

      Pressione CTRL + R, escreva na caixa "cmd" e pressione ENTER.

- Você está dentro do Terminal, acesse o Python dentro do Terminal digitando
  
      "py" e pressione ENTER no teclado.

- Agora você está utilizando o Terminal para executar instruções em Python.

- Tudo que digitar dentro deste Terminal Python será interpretado como se fosse um arquivo de extensão ".py".

<br>

#### Para facilitar, ative a exibição da extensão do nome do arquivo.

<img width="500" src="https://github.com/brunomunarolo/Introducao-Python/assets/113137632/60d829db-f2e5-43bb-a6e6-93e6e057ea0e">

<br>

<br>

- Ficaria assim:

<img width="90" src="https://github.com/brunomunarolo/Introducao-Python/assets/113137632/8db7dac9-2410-44be-bcbb-c04e5a50467d">


- Dentro do seu arquivo escreva e execute:

      print("Hello, World!")

<br>

<img width="500" src="https://github.com/brunomunarolo/Introducao-Python/assets/113137632/191715f9-6c63-4eaa-bbdf-8d113933e5dc">

- A saída deve ser:

      Hello, World!

## Parabéns, você escreveu e executou seu primeiro programa Python.

<br>

--------------------------------------------

<br>

# Linha de comando do Python

- Para testar uma pequena quantidade de código em Python, às vezes é mais rápido e fácil não escrever o código em um arquivo. Isso é possível porque o Python pode ser executado como uma linha de comando em si.

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

<br>


--------------------------------------------

<br>

# Sintaxe do Python

- Recuo refere-se aos espaços no início de uma linha de código.

- Onde em outras linguagens de programação o recuo no código é para legibilidade apenas, o recuo em python é muito importante.

- Python usa recuo para indicar um bloco de código.

### Exemplo
  	 
      if 5 > 2:
       print("Cinco é maior que dois!")

<br>

- Python lhe dará um erro se você pular o recuo:

### Exemplo
 
Erro de sintaxe:

    if 5 > 2:
    print("Cinco é maior que dois!")

<br>

- O número de espaços depende de você como programador, o uso mais comum é quatro, mas tem ser pelo menos um.

### Exemplo

    if 5 > 2:
     print("Cinco é maior que dois!")
    if 5 > 2:
        print("Cinco é maior que dois")

<br>

- Você tem que usar o mesmo número de espaços no mesmo bloco de código, caso contrário, o python lhe dará um erro:

### Exemplo
	
Erro de sintaxe:
	
    if 5 > 2:
    print("Cinco é maior que dois")
        print("Cinco é maior que dois")

<br>

<br>

## Variáveis do Python

- No python, as variáveis são criadas quando você atribui um valor a ela:

### Exemplo

Variáveis em Python:
	
	x = 5
	y = "Olá, Mundo!"

<br>

- Python não tem nenhum comando para declarar uma variável.

- Você aprenderá mais sobre variáveis no capítulo Variáveis do Python.

[Variáveis do Python](https://www.w3schools.com/python/python_variables.asp)

<br>

<br> 

## Comentários

- Python tem capacidade de comentários para fins de documentação no código.

- Os comentários começam com um #, e o Python renderizará o restante da linha como um comentário:

### Exemplo

Cometários em Python:
	
	#Isto é um comentário.
	print("Olá, Mundo!")

<img src="https://github.com/brunomunarolo/Introducao-Python/assets/113137632/1ee78e9b-c639-4f5f-90b1-27316b6eb389">

<br>

- Comentários podem ser usados para explicar o código Python.

- Os comentários podem ser usados para tornar o código mais legível.

- Os comentários podem ser usados para impedir a execução ao testar o código.

- Os comentários podem ser colocados no final de uma linha, e o Python ignorará o resto da linha:

### Exemplo

    print("Hello, World!") #This is a comment

- Um comentário não precisa ser texto que explique o código, ele também pode ser usado para impedir que o Python execute código:

      #print("Hello, World!")
      print("Cheers, Mate!")

<br>

## Comentários de várias linhas
  
- Python realmente não tem uma sintaxe para comentários de várias linhas.

- Para adicionar um comentário de várias linhas, você pode inserir um para cada linha:#

### Exemplo

    #This is a comment
    #written in
    #more than just one line
    print("Hello, World!")


- Ou, não exatamente como pretendido, você pode usar uma cadeia de caracteres de várias linhas.

- Como o Python ignorará literais de cadeia de caracteres que não são atribuídos a uma variável, você pode adicionar uma cadeia de caracteres de várias linhas (aspas triplas) em seu código e colocar seu comentário dentro dela:

### Exemplo

	"""
	Este é um comentário
	escrito em
	mais do que apenas uma linha
	"""
	print("Hello, World!")

- Contanto que a cadeia de caracteres não seja atribuída a uma variável, o Python lerá o código, mas depois o ignorará, e você fez um comentário de várias linhas.

<br>

--------------------------------------------

<br>

# Variáveis Python

- Variáveis são contêineres para armazenar valores de dados.

## Criando variáveis

- Python não tem nenhum comando para declarar uma variável.

- Uma variável é criada no momento em que você atribui um valor a ela pela primeira vez.

### Exemplo

	x = 5
	y = "John"
	print(x)
	print(y)

<br>

- As variáveis não precisam ser declaradas com nenhum tipo específico e podem até mudar de tipo depois de definidas.

### Exemplo
	x = 4       # x é do tipo int
	x = "Sally" # x agora é do tipo str
	print(x)

<br>

## Fundição

- Se você quiser especificar o tipo de dados de uma variável, isso pode ser feito com a transmissão.

### Exemplo

 	x = str(3)    # x will be '3'
	y = int(3)    # y will be 3
	z = float(3)  # z will be 3.0
	
	print(x)
	print(y)
	print(z)

 <br> 

## Obtenha o tipo

- Você pode obter o tipo de dados de uma variável com a função.type()

### Exemplo

	x = 5
	y = "John"
	print(type(x))
	print(type(y))

Você aprenderá mais sobre [tipos de dados](https://www.w3schools.com/python/python_datatypes.asp) e [transmissão](https://www.w3schools.com/python/python_casting.asp) mais adiante neste tutorial.

 <br>

## Aspas simples ou duplas?

- As variáveis de cadeia de caracteres podem ser declaradas usando aspas simples ou duplas:

### Exemplo

	x = "John"
	print(x)
	#Aspas duplas são iguais às aspas simples:
	x = 'John'
	print(x)

<br>

Diferencia maiúsculas de minúsculas
Os nomes das variáveis diferenciam maiúsculas de minúsculas.

### Exemplo

- Isso criará duas variáveis:

      a = 4
      A = "Sally"
      #"A" não substituirá "a"
      print(a)
      print(A)

  <br>

  

