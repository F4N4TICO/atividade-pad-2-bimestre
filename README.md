# atividade-pad-2-bimestre

//questao1
/*
var text = 'Kaylane'
function nome(text){
  console.log("Olá " + text + "!")
}
nome(text)
*/
//questao2
/*
function operacoes(val1,val2,callback)
{
  console.log(callback(val1,val2))
}
operacoes(4,5,function(var1,var2)
{
  return var1 + var2;
})
operacoes(4,5, function(var1,var2){
  return var1 - var2
})
operacoes(4,5, function(var1,var2){
  return var1 / var2
})
operacoes(4,5, function(var1,var2){
  return var1 * var2
})
*/
//questao3
/*
function um(x,callback){
  return function dois(y){
    callback(x,y)
  }
}

var var1 = um(80,function(val1,val2){
  if(val1%val2 == 0){
    console.log('true')
  }else{
    console.log('false')
  }
})
var1(7)
*/
//questao 4
/*function numMeses(num) {
  if (num == 1) {
    console.log("janeiro")
  }
  if (num == 2) {
    console.log("Fevereiro")
  }
  if (num == 3) {
    console.log("Março")
  }
  if (num == 4) {
    console.log("Abril")
  }
  if (num == 5) {
    console.log("Maio")
  }
  if (num == 6) {
    console.log("Junho")
  }
  if (num == 7) {
    console.log("Julho")
  }
  if (num == 8) {
    console.log("Agosto")
  }
  if (num == 9) {
    console.log("Setembro")
  }
  if (num == 10) {
    console.log("Outubro")
  }
  if (num == 11) {
    console.log("Novembro")
  }
  if (num == 12) {
    console.log("Dezembro")
  }
}
numMeses(11)*/

//questao 5
/*
function numeros(num1,num2, callback)
{ 
  return callback(num1,num2)
}

numeros(7,7, function(x,y){
  if (x > y) {
    console.log("O primeiro número é maior")
  }
  if (x < y) {
    console.log("O primeiro número é menor")
  }
  else{
    console.log("Os números são iguais")
  }
})
*/
