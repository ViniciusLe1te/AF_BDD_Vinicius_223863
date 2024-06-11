# AF_BDD_Vinicius_223863

##BDD - GHERKIN

crie um BDD com seu devido Gherkin com base no texto abaixo:

Imagine que você está planejando alugar um carro para uma viagem. Para facilitar esse processo, uma empresa de locação de carros desenvolveu um sistema com diferentes comportamentos, dependendo das circunstâncias da locação e do cliente.

Inicialmente, considere um cliente que deseja alugar um carro de luxo. Se esse cliente realizar a reserva com antecedência de pelo menos uma semana, o sistema deve oferecer um desconto especial no valor total da locação. Por outro lado, suponha um cliente que necessita alugar um carro utilitário de última hora, sem qualquer reserva prévia. Nesse caso, o sistema deve ainda conseguir encontrar um veículo disponível e processar a locação rapidamente, mesmo que isso implique em um custo um pouco mais elevado devido à demanda urgente.

Esses cenários exemplificam como o sistema de locação de carros responde às diferentes necessidades e condições dos clientes, adaptando-se para garantir uma experiência satisfatória de locação, seja para reservas antecipadas ou demandas de última hora.

<br>

Funcionalidade: Sistema de Locação de Carros

  Cenário: Locação de carro de luxo com reserva antecipada
    Given Dado que um cliente deseja alugar um carro de luxo
    And o cliente faz uma reserva com pelo menos uma semana de antecedência
    When quando o cliente confirma a reserva
    Then então o sistema deve oferecer um desconto especial no valor total da locação

  Cenário: Locação de carro utilitário com reserva urgente
    Given dado que um cliente necessita alugar um carro utilitário
    And o cliente não tem reserva prévia
    When o cliente solicita um carro
    Then o sistema deve encontrar um veículo disponível
    And o sistema deve processar a locação rapidamente
    And o custo da locação deve ser mais alto devido à demanda urgente

##Descrição

  Gherkin é uma linguagem de domínio específico utilizada no desenvolvimento orientado por comportamento (BDD) para descrever o comportamento do software de maneira clara e compreensível para todas as partes interessadas. Utiliza uma sintaxe simples baseada em "Dado, Quando, Então" (Given, When, Then) para criar cenários de teste que podem ser automatizados, facilitando a comunicação entre desenvolvedores e não desenvolvedores.


