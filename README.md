# Eduzz-Fullstack-Desafios
Segue desafios que constam no Eduzz Fullstack Developer #2

espero que tenha te ajudado.

👩‍👩‍👧‍👦 não deixe de dar seu followers
⭐ star

 
Resolvendo Desafios Básicos em JavaScript

1 / 3 - Múltiplos <p>

let lines = gets().split("\n");

let line = lines.shift().split(" ");
let A = parseInt(line[0]);
let B = parseInt(line[1]);

if (A % B == 0) 
    print("Sao Multiplos");                   //complete com a sua lógica
else 
print("Nao sao Multiplos");


2 / 3 - Teste de Seleção 1<p>


x = gets().split(" ");

A = parseInt(x[0]);

B = parseInt(x[1]);

C = parseInt(x[2]);

D = parseInt(x[3]);

if (B > C && D > A && (C+D) > (A+B) && C >= 1 && D >= 1 && A % 2 == 0){

 print("Valores aceitos"); 

}

else {

 print("Valores nao aceitos");

}


3 / 3 - Folha de Pagamento<p>
 
let valor1 = parseInt(gets()); 
let valor2 = parseInt(gets()); 
let valor3 = parseFloat(gets()); 
let salario = parseFloat(valor2 * valor3).toFixed(2);
console.log("NUMBER = " + valor1);
console.log("SALARY = U$ " + salario);

// Escreva o seu código aqui