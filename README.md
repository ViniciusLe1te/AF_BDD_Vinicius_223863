# AF_BDD_Vinicius_223863

-- ETAPA 1 --

Tendo em vista o processo explicado anteriormente, crie um BDD com seu devido Gherkin com base no texto abaixo:

Imagine que você está planejando alugar um carro para uma viagem. Para facilitar esse processo, uma empresa de locação de carros desenvolveu um sistema com diferentes comportamentos, dependendo das circunstâncias da locação e do cliente.

Inicialmente, considere um cliente que deseja alugar um carro de luxo. Se esse cliente realizar a reserva com antecedência de pelo menos uma semana, o sistema deve oferecer um desconto especial no valor total da locação. Por outro lado, suponha um cliente que necessita alugar um carro utilitário de última hora, sem qualquer reserva prévia. Nesse caso, o sistema deve ainda conseguir encontrar um veículo disponível e processar a locação rapidamente, mesmo que isso implique em um custo um pouco mais elevado devido à demanda urgente.

Esses cenários exemplificam como o sistema de locação de carros responde às diferentes necessidades e condições dos clientes, adaptando-se para garantir uma experiência satisfatória de locação, seja para reservas antecipadas ou demandas de última hora.

<br>

Funcionalidade: Sistema de Locação de Carros

  Cenário: Locação de carro de luxo com reserva antecipada
    Dado que um cliente deseja alugar um carro de luxo
    E o cliente faz uma reserva com pelo menos uma semana de antecedência
    Quando o cliente confirma a reserva
    Então o sistema deve oferecer um desconto especial no valor total da locação

  Cenário: Locação de carro utilitário com reserva urgente
    Dado que um cliente necessita alugar um carro utilitário
    E o cliente não tem reserva prévia
    Quando o cliente solicita um carro
    Então o sistema deve encontrar um veículo disponível
    E o sistema deve processar a locação rapidamente
    E o custo da locação deve ser mais alto devido à demanda urgente

<br>


