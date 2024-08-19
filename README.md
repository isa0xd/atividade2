# atividade2
programa { 
1-
funcao inicio()
 {
   real horas_do_ano
   real chocolate_na_vida
   real minutos_por_ano 
   real idade_em_anos
   real idade_em_segundos
   real semanas_no_ano
   semanas_no_ano = 52
   real segundos_do_ano 
   segundos_do_ano = 60 * 60 * 24 * 365
    
   horas_do_ano = 24 * 365
   escreva("a- No ano há: ", horas_do_ano , " horas. \n") 
  
   minutos_por_ano = 24 * 60 * 365 * 10
   escreva("b- Em uma década há: ", minutos_por_ano, " minutos.\n ") 
 
   idade_em_segundos = (segundos_do_ano * 16)
   escreva("c- Minha idade em segundos é: ", idade_em_segundos,"\n" ) 
   chocolate_na_vida = (4 * semanas_no_ano)
   escreva("d- Se eu comer 4 chocolates por semana, logo eu comerei ", chocolate_na_vida, " chocolates por ano, até morrer. \n")
   idade_em_anos = (977000000 /segundos_do_ano)
   escreva("e- Se sua idade é de 977 milhoes de segundos, você terá: ", idade_em_anos, " anos. \n")
  }
}

2-
   real ano_mercurio
    ano_mercurio = 0.2408467 // 0.011375393673225584 dias = 87.9090455 segundos
   
    real ano_terra = 1 // 1 ano = 365,25 dias = 31557600 segundos
    real idade_em_dias
    real idade_em_segundos
    real idade_em_mercurio
   
    real calculo_dos_planetas
    calculo_dos_planetas = 1 / 0.2408467
      
   // idade_em_anos = (977000000 /segundos_do_ano) = 30 anos 
   //escreva( Se sua idade é de 977 milhoes de segundos, você terá: ", idade_em_anos, " anos. \n")
    //idade_em_dias = (calculo_dos_planetas / 365)
    //escreva ("Os dias em mercurio são: ",idade_em_dias) 
    //escreva("\n")
    
    //idade_em_segundos = (1 / 0.011375393673225584)
    //escreva("Os segundos em mercurio são: ",idade_em_segundos)
    //escreva("\n")
    idade_em_mercurio = 977000000/87.9090455
    escreva("a- A idade em mercurio seria: ",idade_em_mercurio)
    escreva("\n")
    real idade_da_pessoa
    idade_da_pessoa = 21
    real idade_em_jupiter 
    idade_em_jupiter = 11.862615
    real idade_final
    idade_final = (21 / idade_em_jupiter)
    escreva("b- A idade da pessoa em júpiter seria: ", idade_final)
    
  }
}
3-
funcao inicio() {
    inteiro materia
    inteiro tempo
    inteiro tempoDedicado
    inteiro tempoLivre

    tempoDedicado = 1 * 60 + 40
    materia = 6

    tempo = tempoDedicado / materia
    tempoLivre = tempoDedicado - (tempo * materia)
    
    escreva ("o tempo médio por materia é ", tempo, " minutos \n")
    escreva ("o tempo livre é ", tempoLivre, " minutos")
  }
}



4-
funcao inicio() {
  real a,b,c
 a = 300
 b = 400
 c = 500
 escreva(300 / 45) escreva("\n")
 escreva(300%45) escreva("\n")
 escreva ("Com 3m será possível ter 6 pedaços de 45 cm, e um com 30cm. \n")
 escreva(400/ 45) escreva("\n")
escreva(400%45) escreva("\n")
 escreva ("Com 4m será possível ter 8 pedaços de 45 cm, e um com 40cm. \n")
 escreva(500/ 45) escreva("\n")
escreva(500%45) escreva("\n")
 escreva ("Com 5m será possível ter 11 pedaços de 45 cm, e um com 5cm. \n")
  }
}
5-
funcao inicio() {
    
    escreva ("a- Considerando os valores dados, a quantidade mínima de fios a ser comprado seria ", 11.5 * 6.3 ," metros para que o fio passase pelo arredor da casa. \n")
    
    escreva("b- A quantidade de fios necessária para passar os fios pelo telhado da casa seria raiz de ")
    escreva (11.5 * 11.5 + 6.3 * 6.3, " que dá 13,113 metros")

  }

  6-
funcao inicio() {
   real minutos_por_dia = 5
   real dias_por_semana = 6
   real semanas_por_ano = 52

 escreva ("A quantidade de minutos lidos na semana são: ",minutos_por_dia * dias_por_semana) escreva ("\n")

 escreva ("A quantidade de minutos lidos no ano são: ", minutos_por_dia * dias_por_semana * semanas_por_ano) escreva ("\n")

 //Agora converte os minutos por hora 

  escreva ("A quantidade de horas dedicadas ao livro por ano são: ", minutos_por_dia * dias_por_semana * semanas_por_ano / 60, "horas.")




  }
}

7-
funcao inicio() {
   real idade

    escreva ("Qual sua idade? ")
    leia (idade)

   escreva ((idade + 1 )/ 2)


  }
}

8-
funcao inicio() {
     //velocidade do link em mbps 1 byte = 8 bits, converte o tamanho do arquivo pra megabits multiplicando o tamanho em megabytes por 8
     real tamanho_arquivo
     real velocidade_link
     real tempo_download

     escreva ("Digite o tamanho do arquivo em MB:")
     leia (tamanho_arquivo)
     escreva ("Digite a velocidade do link em Mbps:")
     leia (velocidade_link)

     tempo_download = (tamanho_arquivo * 8) / velocidade_link / 60
     escreva ("O tempo aproximado do download é: ", tempo_download, " minutos. \n")
  }
}

9-
 funcao inicio() {
    real largura, altura
    real metros_quadrados
    real valor_da_tinta = 480 // cada lata tem esse preço
    real capacidade_da_lata = 18 // cada lata tem 18 litros
    real valor_a_ser_pago
    real quantidade_de_tinta , latas_necessarias
    escreva ("Qual o tamanho (em metros quadrados) da área a ser pintada? \n")
    leia (largura,altura)

    metros_quadrados = (largura * altura)

    quantidade_de_tinta = ( metros_quadrados / 3)   

    latas_necessarias = (quantidade_de_tinta / capacidade_da_lata)

    valor_a_ser_pago =(latas_necessarias * valor_da_tinta)

    escreva ("Quantidade de latas necessárias: ", latas_necessarias, " \n")
    escreva ("Preço total: ", valor_a_ser_pago, " \n")




  }
}
