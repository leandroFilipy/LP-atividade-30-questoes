# 🧠 Atividade de Lógica de Programação – 30 Questões

Este repositório contém uma série de **exercícios de lógica de programação**, focados em **estruturas condicionais** e **controle de fluxo** utilizando a linguagem **Java**. Ideal para iniciantes que desejam praticar a lógica de programação com situações do cotidiano.

---

## 📘 Descrição

A proposta da atividade é resolver uma lista de questões práticas que envolvem:

- Estruturas condicionais (`if`, `else`, `else if`)
- Operadores lógicos (`&&`, `||`)
- Entrada de dados via `Scanner`
- Funções e validações básicas

---

## 🧪 Exemplos de Questões

1. Trocar os valores de `a` e `b` se `a < b`.
2. Verificar se um número é positivo ou negativo.
3. Receber 5 notas (de 0 a 100) e informar quantas são maiores que 60.
4. Verificar se uma pessoa pode tirar carteira de motorista (idade mínima de 18).
5. Informar quantos anos faltam para tirar a carteira, caso a idade seja menor que 18.
6. Verificar se um número é par ou ímpar.
7. Verificar se um número é par/ímpar e se é positivo/negativo.
8. Verificar se as variáveis `a` e `b` são pares.
9. Verificar se `a` **ou** `b` é par.
10. Função que valida se três ângulos formam um triângulo (soma == 180°).

---

## 💻 Exemplo de Código

```java
import java.util.Scanner;

public class ATV03 {
    public static void main(String[] args) {
        Scanner read = new Scanner(System.in);

        System.out.print("Insira a primeira nota: ");
        int nota01 = read.nextInt();

        System.out.print("Insira a segunda nota: ");
        int nota02 = read.nextInt();

        System.out.print("Insira a terceira nota: ");
        int nota03 = read.nextInt();

        System.out.print("Insira a quarta nota: ");
        int nota04 = read.nextInt();

        System.out.print("Insira a quinta nota: ");
        int nota05 = read.nextInt();

        if (nota01 > 60 && nota02 > 60 && nota03 > 60 && nota04 > 60 && nota05 > 60) {
            System.out.println("Todas as notas são maiores que 60");
        } else {
            System.out.println("Nem todas as notas são maiores que 60");
        }

        read.close();
    }
}
