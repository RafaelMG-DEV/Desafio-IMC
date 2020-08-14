# Desafio-IMC

Desafio número 1 do Bootcamp LaunchBase da Rocketseat

/* ===================================================================
    DESAFIO IMC

    IMC É CALCULADO DIVIDINDO O PESO PELA ALTURA AO QUADRADO

    VALORES IMC:

    MENOR QUE 30        -   NÃO ESTÁ OBESO
    MAIOR OU IGAL A 30  -   ESTÁ OBESO
   
====================================================================*/

const Nome = 'Rafael'
const Peso = 85
const Altura = 1.70
const IMC = Peso / (Altura * Altura)

const Resultado = `${Nome}, seu IMC é ${IMC}.`

console.log(Resultado)

if (IMC >= 30) {
    console.log(`${Nome}, você está com obesidade e precisa se cuidar!!`)
} else {
    console.log(`Meus parabens ${Nome}!! Você não está com obesidade!!`)
}
