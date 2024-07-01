# Calculadora de Partidas Rankeadas

## Descrição
Este projeto consiste em uma função simples em JavaScript para calcular o nível de um jogador com base no número de vitórias em partidas ranqueadas de um jogo fictício. O nível é determinado de acordo com faixas de vitórias estabelecidas.

## Funcionamento
A função `calcularNivel(vitorias, derrotas)` recebe como parâmetro a quantidade de vitórias e derrotas de um jogador. Com base nesses valores, ela calcula o saldo de vitórias (`vitorias - derrotas`) e determina o nível do jogador de acordo com as seguintes faixas:
- Menos de 10 vitórias: Ferro
- Entre 11 e 20 vitórias: Bronze
- Entre 21 e 50 vitórias: Prata
- Entre 51 e 80 vitórias: Ouro
- Entre 81 e 90 vitórias: Diamante
- Entre 91 e 100 vitórias: Lendário
- 101 vitórias ou mais: Imortal

O resultado é então exibido em uma mensagem formatada no console.

## Exemplos de Uso
```javascript
// Exemplo de uso da função
const saldoVitorias = calcularNivel(60, 20);
// Saída esperada: "O Herói tem um saldo de vitórias de 40 e está no nível de Ouro"
console.log(saldoVitorias);
