# processingjs
Lógica de Predicados

## Erros observados em 04/12/2019

<code>
Biblioteca-Grafica, Biblioteca_Grafica   

Javascript é uma linguagem de Programação
Fórmula:	Linguagem("Processing,Programação")

Gosta("Alexandre") = Processing
Gosta("Alexandre") = "Processing"

Gosta como função é estranho. Uma pessoa pode gostar de mais de uma coisa.

Donos("Casey Reas","Benjamin Fry") = "Projeto Processing"

MELHOR: Dono("Casey Reas","Projeto Processing") 

Ajuda("Lauren McCarthy","Casey Reas","Ben Fry")
MELHOR Ajuda("Lauren McCarthy","Ben Fry")

Structs não é um conceito em Javascript
Fórmula:	¬Conceito("Matrizes,Javascript")

Alexandre aprendeu C e Alexandre aprendeu Javascript
Fórmula:	Aprendeu("Alexandre","X") ^ Aprendeu("Alexandre","Javascript")

Se o Software foi escrito em Javascript então ele não funciona com Java.
Fórmula:	Escrito("Software","Javascript") -> ¬Funciona("Software","Java")
// o software parece algo genérico. Existe x Software(x)...

Existe ao menos um Shape em Processing.
Fórmula	∃x(Shape(x) & Processing(x))
Shape(x): X é um Shape. Processing(x): É processing
// onde está dizendo que x está em processing?

Existe ao menos uma aplicação de Processing na Ciência.
Fórmula	∃x(Aplicação("ProcessingJS")) = Ciencia("Processing"))
// onde está o x na fórmula?

Existe ao menos alguém estudando Processing.
Fórmula	∃x(Alguem(x)) = Estudando("Processing")
// onde está a informação de que x estuda Processing?
// Alguem(x) não precisa. O ∃ é para isso.
// Seria melhor algo como:
// ∃x(Desenvolvedor(x) & Estuda(x, "Processing"))


v={X,Y,Z}
V= {x, y, z}

Não deveria estar:
OBS: Constantes: 6 Variáveis: 3 Predicados de aridade 1: 3 Predicados de aridade 2 ou superior: 2 Funções de aridade 1: 2 Funções de aridade 2 ou superior: 1
OBS: Valores no universo de valores concretos: mínimo de 10

Constante(s)

Não faz sentido:
AjudaM₁(...)

Funções incompletas.
</code>
