# Herança e Polimorfismo (exemplo Java) - Aulão #007
###### DevSuperior - sua carreira dev com fundamento de ensino superior

**Comunidade no Discord**:
https://discord.gg/SbjpsFv

Não perca as novidades:
- https://instagram.com/devsuperior.ig
- https://facebook.com/devsuperior.fb
- https://youtube.com/devsuperior
- https://twitter.com/devsuperior

Assista o vídeo desta aula:

[![Image](https://img.youtube.com/vi/eDsS3JM5iXw/mqdefault.jpg "Vídeo no Youtube")](https://youtu.be/eDsS3JM5iXw)

## Sumário
- [O que você vai aprender](#O-que-você-vai-aprender)
- [Pré-requisitos](#pré-requisitos)
- [Enunciado do exercício](#Enunciado-do-exercício)

## O que você vai aprender
- Herança
- Métodos e classes abstratas
- Polimorfismo

## Pré-requisitos

- Lógica de programação
  - Variáveis, entrada, processamento, saída
  - Estrutura condicional
  - Estruturas repetitivas
- OOP básica
  - Classes, atributos, métodos, objetos
  - Construtores, encapsulamento
  - List

## Enunciado do exercício

Fazer um programa para ler os dados de N contribuintes (N fornecido pelo usuário), os quais podem ser pessoa física ou pessoa jurídica, e depois mostrar o valor do imposto pago por cada um, bem como o total de imposto arrecadado. 

Os dados de pessoa física são: nome, renda anual e gastos com saúde. Os dados de pessoa jurídica são nome, renda anual e número de funcionários. As regras para cálculo de imposto são as seguintes:

Pessoa física: pessoas cuja renda foi abaixo de 20000.00 pagam 15% de imposto. Pessoas com renda de 20000.00 em diante pagam 25% de imposto. Se a pessoa teve gastos com saúde, 50% destes gastos são abatidos no imposto. 
Exemplo: uma pessoa cuja renda foi 50000.00 e teve 2000.00 em gastos com saúde, o imposto fica: (50000 * 25%) - (2000 * 50%) = 11500.00

Pessoa jurídica: pessoas jurídicas pagam 16% de imposto. Porém, se a empresa possuir mais de 10 funcionários, ela paga 14% de imposto. 
Exemplo: uma  empresa  cuja  renda foi 400000.00 e possui 25 funcionários, o imposto fica: 400000 * 14% = 56000.00

### Exemplo

```
Enter the number of tax payers: 3
Tax payer #1 data:
Individual or company (i/c)? i
Name: Alex
Anual income: 50000.00
Health expenditures: 2000.00
Tax payer #2 data:
Individual or company (i/c)? c
Name: SoftTech
Anual income: 400000.00
Number of employees: 25
Tax payer #3 data:
Individual or company (i/c)? i
Name: Bob
Anual income: 120000.00
Health expenditures: 1000.00

TAXES PAID:
Alex: $ 11500.00
SoftTech: $ 56000.00
Bob: $ 29500.00

TOTAL TAXES: $ 97000.00
```

### Diagrama

![myImage](https://github.com/devsuperior/aulao007/raw/master/domain-model.png)
