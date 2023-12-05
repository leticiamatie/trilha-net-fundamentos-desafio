<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
  <a href="[https://www.dio.me/](https://web.dio.me/track/decola-tech-avanade-net-developer)">
     <img align="center" width="40px" src="https://hermes.dio.me/tracks/6bb40420-5f89-4902-8df7-3399674d9d84.png"></a>
    <span>Desafio de projeto .NET Fundamentos</span>
</h1>

Projeto desenvolvido para fins didáticos com o objetivo de programar um sistema de estacionamento utilizando conhecimentos adquiridos no módulo de fundamentos, da trilha .NET da DIO.

## Contexto
Você foi contratado para construir um sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Proposta e conceitos
Você precisará construir uma classe chamada "Estacionamento".

A classe contém três variáveis, sendo:

- **precoInicial**: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

- **precoPorHora**: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

- **veiculos**: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

A classe contém três métodos, sendo:

- **AdicionarVeiculo**: Método responsável por receber uma placa digitada pelo usuário e guardar na variável **veiculos**.

- **RemoverVeiculo**: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: **precoInicial** * **precoPorHora**, exibindo para o usuário.

- **ListarVeiculos**: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

Por último, deverá ser feito um menu interativo com as seguintes ações implementadas:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar
   
## Funcionalidades
- Adicionar veículo
- Remover veículo (calculando o valor a ser pago com base no tempo estacionado)
- Listar veículos

