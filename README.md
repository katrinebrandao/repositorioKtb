# repositorioKtb
Repositório teste. 
var logradouro = "Rua Doutor Cardoso de Melo, 90"
var bairro = "Vila Olímpia"
console.log(logradouro + bairro) // imprime “Rua Doutor Cardoso de Melo, 90Vila Olimpia”

Declare e atribua duas variáveis: numeroA e numeroB, em que ambas precisam conter um valor numérico. Em seguida, faça as variáveis de soma, subtração, multiplicação e divisão utilizando essas duas variáveis.

var numeroA = 10
var numeroB = 2
var soma = (numeroA + numeroB)
var subtracao = (numeroA - numeroB)
var multiplicacao = numeroA*numeroB
console.log (numeroA*numeroB)
var divisao= numeroA/numeroB
console.log (numeroA/numeroB)

Uma empresa separou os seus ganhos dos meses nas seguintes variáveis:

var janeiro =  100
var fevereiro = 300
var março = 90

Ela precisa da sua ajuda para saber o total do lucro adquirido. Sua missão é usar os operadores junto com as variáveis para fazer esse cálculo e use o console.log para imprimir o resultado!

var trabalhoDeHistoria = 8.0
var trabalhoDeMatematica = 7.0
var trabalhoDeCiencia = 10
var trabalhoDeGeografia = 9.5
var totalDeTrabalhos = 4
console.log(trabalhoDeCiencia+trabalhoDeGeografia+trabalhoDeHistoria+trabalhoDeMatematica)
var somatorioDeTrabalhos = trabalhoDeHistoria+trabalhoDeMatematica+trabalhoDeGeografia+trabalhoDeCiencia
console.log (somatorioDeTrabalhos/totalDeTrabalhos)
var media = somatorioDeTrabalhos/ totalDeTrabalhos

Condicionais
if ( condição )


Var diaDaSemana = “quarta-feira”
If (diaDaSemana == “quarta-feira”) {console.log(“Hoje é dia de feijoada!”)
}

if ( a == b ) { console.log(‘A condição é verdadeira’) }
Comando if seguido de condição entre parênteses e código a ser executado entre chaves.
Exercício - Condicional IF

O sistema deve cumprimentar o usuário independente da idade
Caso o usuário tenha idade mínima para dirigir imprima: 
“Olá, NOME_DO_USUARIO_AQUI”
”Você passou no nosso teste e já pode dirigir!”
Caso o usuário não tenha a idade mínima para dirigir imprima somente o cumprimento:
“Olá, NOME_DO_USUARIO_AQUI”
------------------------------------------------------------------------------------------------------------
Precisamos de um código que verifique a idade do usuário para ver se já tem idade mínima para adquirir carta de habilitação. Para isso, teremos uma variável nome que guarda um valor do tipo string, e uma variável idade que guarda um valor do tipo numérico.
O sistema deve cumprimentar o usuário independente da idade, o resultado seria assim:
Caso o usuário tenha idade mínima para dirigir imprima: 
“Olá, NOME_DO_USUARIO_AQUI”
”Você passou no nosso teste e já pode dirigir!”.
Caso o usuário não tenha a idade mínima para dirigir imprima somente o cumprimento:
“Olá, NOME_DO_USUARIO_AQUI”
_____________________
var nome = "João"
var idade = 17
console.log ("Olá, "+nome)
if (idade >= 18) {
    console.log( "Você passou no nosso teste e já pode dirigir!")}


Condicionais - Conta bancária
Queremos um código que oriente o usuário de acordo com o saldo da conta bancária. Para isso precisamos de uma variável saldo que guarda um número decimal(float), e imprime uma mensagem de acordo com a situação financeira. Se o saldo for maior que 0 (zero) imprima “Seu saldo está positivo! Gostaria de fazer um investimento?”, agora, se o saldo for menor que zero(0) imprima “Seu saldo está negativo! Gostaria de fazer um empréstimo?”





var saldo = 10.0
if (saldo > 0) {
   console.log("Seu saldo está positivo! Gostaria de fazer um investimento?")
}
if (saldo < 0) {
    console.log("Seu saldo está negativo! Gostaria de fazer um empréstimo?")
}
 

