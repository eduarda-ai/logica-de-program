# logica-de-program
programa {
  funcao inicio() {
    inteiro numero, resultado
    escreva("digite um numero: ")
    leia(numero)

    resultado = numero % 2
    //% resto da divis�o

    se(resultado == 0){
      escreva("par")
    } senao {
      escreva ("impar")
    }
  }
}
