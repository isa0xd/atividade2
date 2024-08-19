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
   chocolate_na_vida = (2 * semanas_no_ano)
   escreva("d- Se eu comer 2 chocolates por semana, logo eu comerei ", chocolate_na_vida, " chocolates por ano, até morrer. \n")
   idade_em_anos = (977000000 /segundos_do_ano)
   escreva("e- Se sua idade é de 977 milhoes de segundos, você terá: ", idade_em_anos, " anos. \n")
  }
}

  
