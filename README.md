//numa determinada festa é permitida a entreda de apenas pessoas maiores de idade. Voce, que é uma pessoa programadora que trabalha na empresa que esta produzindo a festa, deve fazer um programa que, dada a idade da pessoa na tela, informe se a pessoa pode entrar ou deve ser barrada.

//Imput Format
//A entrada do problema sera sempre uma variavel idade do tipo number. Essa idade é sempre um numero inteiro e positivo.

//Output Format
//Voce deve imprimir na tela PODE ENTRAR caso a pessoa seja maior de idade(ou seja tenha 18 anos ou mais).
//Caso a pessoa seja menor de idade imprima na tela ACESSO NEGADO

const idade = 10
if(idade >= 18) {
  console.log("PODE ENTRAR")
} else {
  console.log("ACESSO NEGADO")
}
