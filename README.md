function calcular(operacao, a, b) {
    if (operacao === 'soma') {
        return a + b;
    } else if (operacao === 'subtracao') {
        return a - b;
    } else {
        return 'Operação inválida';
    }
}

const operacao = prompt("Escolha a operação: soma ou subtracao").toLowerCase();
const a = parseFloat(prompt("Digite o primeiro número:"));
const b = parseFloat(prompt("Digite o segundo número:"));

const resultado = calcular(operacao, a, b);
console.log(`O resultado é: ${resultado}`);
