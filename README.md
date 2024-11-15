# DIO - Trilha .NET - Fundamentos
www.dio.me

## 💎 Funcionalidades do Desafio Implementadas
- Este projeto foi desenvolvido utilizando conhecimentos fundamentais de C#, *como manipulação de listas, controle de fluxo com condicionais e laços*, além da interação com o usuário via terminal.
- Para implementar a funcionalidade de adicionar veículos, utilizamos a classe `List<string>` para armazenar as placas, e o método `Console.ReadLine()` para capturar a entrada do usuário.
- A remoção de veículos envolveu o uso de métodos como `Any()` para verificar a presença de um item na lista e a remoção com `Remove()`.
- Além disso, para calcular o valor a ser pago pelo estacionamento, utilizamos operações matemáticas simples e convertemos entradas do usuário com `int.Parse()`.
- A listagem dos veículos estacionados foi realizada através de um *laço foreach*, percorrendo a lista e exibindo as placas no terminal.
- Esse desafio aplicou conceitos de programação orientada a objetos e manipulação de dados em C#, além de proporcionar uma experiência prática com a criação de um sistema interativo no console.

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de fundamentos, da trilha .NET da DIO.

## Contexto
Você foi contratado para construir um sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Proposta
Você precisará construir uma classe chamada "Estacionamento", conforme o diagrama abaixo:
![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

A classe contém três variáveis, sendo:

**precoInicial**: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

**precoPorHora**: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

**veiculos**: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

A classe contém três métodos, sendo:

**AdicionarVeiculo**: Método responsável por receber uma placa digitada pelo usuário e guardar na variável **veiculos**.

**RemoverVeiculo**: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: **precoInicial** * **precoPorHora**, exibindo para o usuário.

**ListarVeiculos**: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

Por último, deverá ser feito um menu interativo com as seguintes ações implementadas:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar


## Solução
O código está pela metade, e você deverá dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no código, em seguida, implemente conforme as regras acima.


## Happy coding! 👩🏽‍💻 
[![linkedin](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/datavizwithfer/) 
[![medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@DataVizWithFer)

<div align="center">
<img src="https://forthebadge.com/images/badges/built-with-love.svg" />
</div>
