# Funções

Projetos referentes ao curso "Funções" que fiz pela [Digital Innovation One](https://digitalinnovation.one/).

## Atividade 1: Alunos Aprovados

1. Criei uma função que recebe o array `alunos` e um número que irá representar a média final;
2. Percorri o array e popule um novo array auxiliar apenas com os alunos cujas notas são maiores ou iguais à média final;
3. Utilizei  a técnica "object destructuring" para manipular as propriedades desejadas de cada aluno.

## Atividade 2: This

Usei a função `calculaIdade`, utilize os métodos call e apply para modificar o valor de `this`. Crie seus próprios objetos para esta atividade!

```js
function calculaIdade(anos) {
	return `Daqui a ${anos} anos, ${this.nome} terá ${
		this.idade + anos
	} anos de idade.`;
}
```
