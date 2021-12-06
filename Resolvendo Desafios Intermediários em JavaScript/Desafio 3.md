## Eduzz-Fullstack-Desafios
Segue desafios que constam no Eduzz Fullstack Developer #2

espero que tenha te ajudado.

👩‍👩‍👧‍👦 não deixe de dar seu followers
⭐ star

 
## Resolvendo Desafios Básicos em JavaScript

```
1 / 3 - Triângulo <p>

let lines = gets().split('\n')

let line = lines.shift().split(" ");
let A = parseFloat(line[0]);
let B = parseFloat(line[1]);
let C = parseFloat(line[2]);
let maior;
let soma;
let triangulo;
let perimetro = A+B+C ;
let area = (((A+B)* C / 2)) ;


if (A > B && A > C) maior = A;
else if (B > C) maior = B;
else maior = C;

if (maior == A) soma = B + C;
else if (maior == B) soma = A + C;
else soma = B + A;

if (soma > maior) triangulo = true;
else triangulo = false;

if (triangulo) {
 print("Perimetro = " + perimetro.toFixed(1));
     

} else {
  print("Area = " + area.toFixed(1));

    }
   
```
<p>
 
```
2 / 3 - Tomadas <p>

 let lines = gets().split("\n");


let line = lines.shift().split(' ');
//escreva aqui o seu código

let T1 = parseInt(line[0]);
let T2 = parseInt(line[1]);
let T3 = parseInt(line[2]);
let T4 = parseInt(line[3]);


let total = ((T1+T2+T3+T4)-3);

print(total);
 
```
 <p>

```
3 / 3 - Polígonos Regulares Simples <p>
 
let lines = gets().split("\n");
let line = lines.shift().split(' ');

let N = parseInt(line[0]);
let L = parseInt(line[1]);

let P = N * L;

if (N >= 3 && N <= 1000000 && L >= 1 && L <= 4000){
  print(P);
}
 
 ```
