# Swift Fundamentals Condicionals

    /
    /: Playground - noun: a place where people can play
    
    import UIKit
    
    //-----------------------------------------------------------
    
    // Estruturas Condicionais - If / Else
    
    //-----------------------------------------------------------
    
    //if (expressão lógica)
    
    //{
    
    // // Caso a expressão seja verdadeira este bloco será executado
    
    //}
    
    //else
    
    //{
    
    // // Caso a opção seja falsa este bloco será executado
    
    //}
    
    var gol = true
    
    if(gol == true)
    
    {
    
    print("Pode comemorar!")
    
    }
    
    else
    
    {
    
    print("Continue torcendo...")
    
    }
    
    var numero = 20
    
    if numero < 20
    
    {
    
    print("Menor que 20'")
    
    }
    
    else if numero > 20 {
    
    print("Maior que 20")
    
    }
    
    else
    
    {
    
    print("O número é 20")
    
    }
    
    //-----------------------------------------------------------
    
    // Estruturas Condicionais - And / Or
    
    //-----------------------------------------------------------
    
    var cupom: Int = 1020
    
    var hora: Int = 11
    
    // Expressão AND
    
    if cupom == 1010 && hora < 12
    
    {
    
    print("Desconto concedido \n")
    
    }
    
    else
    
    {
    
    print("Não foi possível conceder o desconto :(")
    
    }
    
    // Expressão OR
    
    if cupom == 1010 || hora < 12
    
    {
    
    print("Desconto concedido \n")
    
    }
    
    else
    
    {
    
    print("Não foi possível conceder o desconto")
    
    }
    
    //-----------------------------------------------------------
    
    // Estruturas Condicionais - Switch / Case
    
    //-----------------------------------------------------------
    
    //switch valorASerConsiderado {
    
    //case valorCaso1:
    
    // //bloco a ser considerado se valorCaso1 for verdadeiro
    
    //case valorCaso2:
    
    /// /bloco a ser considerado se valorCaso2 for verdadeiro
    
    //case valorCaso3:
    
    // //bloco a ser considerado se valorCaso2 for verdadeiro
    
    //default:
    
    // //bloco a ser considerado caso nenhum dos cases sejam verdadeiros
    
    //}
    
    var valor: Int = 100
    
    switch valor
    
    {
    
    case 1:
    
    print("Não temos muito dinheiro")
    
    case 100:
    
    print("Estamos com algum dinheiro")
    
    case 1000:
    
    print("Estamos bem de dinheiro")
    
    default:
    
    print("Temos \(valor)")
    
    }
    
    var calculo = 5 * 10
    
    var conta = 2 + 2
    
    switch(calculo < 10, conta == 5)
    
    {
    
    case (true, true):
    
    print("Calculo é menor que 10. A conta dá 5")
    
    case(false, true):
    
    print("Calculo não é menor que 10. A conta dá 5")
    
    case(true, false):
    
    print("Calculo é menor que 10. A conta não dá 5")
    
    default:
    
    print("Calculo não é menor que 10. A conta não dá 5")
    
    }
