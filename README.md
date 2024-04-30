# Projeto de Hospedagem - Desafio
Este é um projeto desenvolvido como parte de um desafio de programação. O objetivo do projeto é criar um sistema de hospedagem que permita o cadastro de hóspedes, suítes e reservas, além de calcular o valor da diária e aplicar descontos com base na quantidade de dias reservados.

## Funcionalidades
Cadastro de hóspedes com nome completo e, opcionalmente, sobrenome.
Cadastro de suítes com tipo, capacidade e valor da diária.
Realização de reservas, associando suítes e hóspedes.
Cálculo do valor da diária com possibilidade de desconto para reservas com 10 dias ou mais.
Verificação automática da capacidade da suíte antes de cadastrar hóspedes.

-----------------------------------------------------------------------------------------

## Descrição do projeto original DIO 👇🏽

# DIO - Trilha .NET - Explorando a linguagem C#
www.dio.me

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de explorando a linguagem C#, da trilha .NET da DIO.

## Contexto
Você foi contratado para construir um sistema de hospedagem, que será usado para realizar uma reserva em um hotel. Você precisará usar a classe Pessoa, que representa o hóspede, a classe Suíte, e a classe Reserva, que fará um relacionamento entre ambos.

O seu programa deverá cálcular corretamente os valores dos métodos da classe Reserva, que precisará trazer a quantidade de hóspedes e o valor da diária, concedendo um desconto de 10% para caso a reserva seja para um período maior que 10 dias.

## Regras e validações
1. Não deve ser possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.
2. O método ObterQuantidadeHospedes da classe Reserva deverá retornar a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria deverá retornar o valor da diária (Dias reservados x valor da diária).
3. Caso seja feita uma reserva igual ou maior que 10 dias, deverá ser concedido um desconto de 10% no valor da diária.


![Diagrama de classe estacionamento](diagrama_classe_hotel.png)

## Solução
O código está pela metade, e você deverá dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no código, em seguida, implemente conforme as regras acima.
