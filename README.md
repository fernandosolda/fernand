# fernand
Algoritmo "impostoderenda"
// Disciplina   : [PA]
// Professor   :cinia pinho
// Descri��o   : calcula o imposto de renda (fun��o) 
// Autor(a)    :Luis Fernando Osuna Solda 
// Data atual  : 27/11/2021
Var
salario,resp:real
Inicio
escreval("qual seu salario?")
leia(salario) se(salario&lt;= 1903 98) entao
resp&lt;- 0
fimse
se((salario&lt;= 1903 99)e(salario &lt;= 2826 65)) entao 
resp&lt;-salario*0 075
fimse 
se((salario&lt;= 2826 66)e(salario &lt;= 3751 05)) entao 
resp&lt;-salario*0 15
fimse
se((salario&lt;= 3751 05)e(salario &lt;= 4664 68)) entao 
resp&lt;-salario*0 225
fimse 
se((salario&lt;= 4664 68)entao
resp&lt;-salario*0 275
fimse 
escreval(" o desconto na sua folha de pagamento ser� de r$",resp) 


Fimalgoritmo 
