# Password_generator

<h2>●Entendendo o código</h2>
<h4>ELEMENTOS</h4>

<p>generatePasswordButton: Este botão é usado para gerar uma nova senha.</p> 

<p>generatedPasswordElement: Este elemento é usado para exibir a senha gerada.

<p>openCloseGeneratorButton: Este botão é usado para abrir ou fechar o gerador de senhas.

<p>generatePasswordContainer: Este elemento contém os elementos do gerador de senhas.

<p>lengthInput: Este campo de entrada é usado para definir o comprimento da senha gerada.

<p>lettersInput: Este checkbox é usado para incluir letras na senha gerada.

<p>numbersInput: Este checkbox é usado para incluir números na senha gerada.

<p>symbolsInput: Este checkbox é usado para incluir símbolos na senha gerada.

copyPasswordButton: Este botão é usado para copiar a senha gerada para a área de transferência.
<br>

<h4>Nesta parte, você define as seguintes funções:</h4>

getLetterLowerCase(): Esta função retorna um caractere aleatório do alfabeto em minúsculas.

getLetterUpperCase(): Esta função retorna um caractere aleatório do alfabeto em maiúsculas.

getNumber(): Esta função retorna um número aleatório de 0 a 9.

getSymbol(): Esta função retorna um símbolo aleatório de um conjunto de símbolos pré-definidos.

generatePassword(): Esta função gera uma nova senha usando as funções getLetterLowerCase(), getLetterUpperCase(), getNumber() e getSymbol().


<h4>Eventos</h4>

Nesta parte, você define os seguintes eventos:

click no botão generatePasswordButton: Essa ação gera uma nova senha.
click no botão openCloseGeneratorButton: Essa ação abre ou fecha o gerador de senhas.
click no botão copyPasswordButton: Essa ação copia a senha gerada para a área de transferência.

