# Aprovadoreprovadoouderecupera-o
algoritmo "reprovadoaprovadorecuperaçao"
var
   n1,n2,m,na:real
inicio
    escreval ("------------------------------------------")
    escreval  ("Escola Municipal Maria Caproni de Oliveira")
    escreval ("------------------------------------------")
    escreva ("Nome do aluno: ")
    leia (na)
   escreva ("primeira nota: ")
   leia (n1)
   se (n1 > 10) entao
     escreval ("ERRO A NOTA DO ALUNO NÂO PODE PASSAR DE 10")
    senao
   escreva ("segunda nota : ")
    leia (n2)
    se (n2 > 10 ) entao
    escreva ("ERRO A NOTA DO ALUNO NÂO PODE PASSAR DE 10")
    senao
   m <- (n1 + n2) / 2
   escreval ("a media do aluno foi " , m:4:2)
   se (m >=6) entao
      escreva ("aluno APROVADO")
   senao
      se (m>=5) e (m<6) entao
         escreva ("aluno de RECUPERAÇAO")
      senao
         escreval ("aluno REPROVADO")
     fimse
    fimse
  fimse
fimse
fimalgoritmo
