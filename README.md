INICIO 
 
 inteiro:i =0, maximo = 100;
lógico : impar;

repita
impar=(i MOD 2) !==0;
se impar então
imprime (i+ "é impar");
fim-se
i=i+l;
até i >=maximo;

FIM




INICIO

inteiro:i=0, maximo=100;
lógico:impar;

para i de 0 até maximo faça
impar=(i MOD 2) !==0;
se impar então
imprime 9i+"é impar");
fim-se
i=i+1;
fim-para

FIM










INICIO
inteiro:maximo=10,NUM,N=1, numero_da_tabuada;
imprime:("Digite o número pelo qual você desejaobter a tabuada de 1 a 10")
leia: (NUM);

repita
numero_da_tabuada=NUM*N;
imprime ("O número" +numero_da_tabuada+ "está na tabuada de 1 a 10 do número +NUM);
até N > maximo;

FIM







INICIO
inteiro:maximo=10, NUM,N=1,numero_da_tabuada;
imprime("Digite um número pelo qual você deseja obter a tabuada de 1 a 10:");
leia(NUM);

para N de 1 até maximo faça
numero_da_tabuada= NUM*N;
imprime(numero_da_tabuada+ " é um número da tabuada de 1 a 10  do número" + NUM);
N = N+1;
fim_para

FIM










INICIO

real: numero, multiplicacao;
inteiro: numerosDigitados;

imprime (" Multiplicação dos números.")
imprime (" 0 ( ZERO ) encerra a multiplicação.");

multiplicaca0=1.0;
numero=1.0;
numeroDigitado=0;

repita
multiplicacao=multiplicacao*numero;

imprime ("Digite o número: ");
leia (numero);

numerosDigitados=numerosDigitados+1;
até numero !==0;

se numerosDigitados == 1 então
multiplicacao=0.0;
fim-se

imprime("O produto de todos os números é" + multiplicacao);

FIM




INICIO

real: numero,multiplicacao;
inteiro: numerosDigitados;

imprime(" Multiplicação dos números.");
imprime ("0 (ZERO) encerra a multiplicação.");

multiplicacao=1.0;
numero=1.0;
numeroDigitado=0;

para numero de 1.0 até =/= 0 faça
multiplicacao=multiplicacao*numero;

imprime("Digite o número: ");
leia (numero);

numerosDigitados=numerosDigitados+1;
fim-para

se numerosDigitados==1 então
multiplicacao=0.0;
fim-se

imprime("O produto de todos os números é" + multiplicacao);

FIM



INICIO

inteiro:i=1, numero;
lógico:divisor;

imprime("Digite um número pelo qual você deseja saber os seus divisores:");
leia(numero);

repita
divisor=(numero MOD i)==0;
se divisor então
imprime(i+" é um divisor de"+ numero);
i=i+1;
até i==numero;

FIM




INICIO 

inteiro:i, numero;
lógico: divisor;

imprime(" Digite um número pelo qual você deseja saber os seus divisores:");
leia(numero);

para i de 1 até numero faça
divisor = (numero MOD i)==0;
se divisor
imprime(i+" é divisor de "+numero);
fim-se

fim-para

FIM









INICIO

inteiro: numero_de_alunos; i= 1; media; aprovados=0,reprovados=0;
real:nota;porcentagem;

imprime ("Digite o total de alunos");
leia(numero_de_alunos);
imprime("Digite também a média");
leia(media);

repita
imprime("Digite a nota do aluno"+ i);
leia(nota);
se nota >= media
aprovado=aprovado+1;
senão reprovados=reprovados+1;
fim-se

até i==numero_de_alunos;

imprime("o total de alunos aprovados foi de " + aprovados);
imprime ("o total de alunos reprovados foi de "+ reprovados);
imprime ("A porcentagem de alunos aprovados foi de " + porcentage);

FIM






INICIO

inteiro:numero_de_alunos; i=1; media; aprovados=0,reprovados=0;
real:nota;porcentagem;

imprime("Digite o total de alunos");
leia (numero_de_alunos);
imprime("Digite também a média");
leia(media);

para i de 1 até numero_de_alunos faça
imprime("Digite a nota do aluno" + i);
leia(nota);
se nota>= media
aprovado=aprovado+1;
senão reprovado=reprovado+1;
fim-se

fim-para

porcentagem=aprovados*100/ numero_de_alunos;

iprime("O total de alunos aprovados foi de "+ aprovados);
imprime("O total de alunos reprovados foi de " + reprovados);
imprime("Aporcentagem de alunos aprovados foi de"+ porcentagem);

FIM




