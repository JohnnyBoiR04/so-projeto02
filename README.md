# so-projeto02

# Projeto de Sistemas Operativos: Simulação de Restaurante

## Objetivo
Compreender os mecanismos associados à execução e sincronização de processos e threads através da simulação de um restaurante.

## Descrição do Projeto
Vários grupos de clientes (groups) jantam num restaurante com duas mesas, interagindo com um recepcionista (receptionist), um empregado de mesa (waiter) e um cozinheiro (chef). O desafio consiste em simular estas interações e processos.

## Componentes do Sistema
- **Grupos de Clientes (Groups):** Chegam ao restaurante e interagem com o recepcionista.
- **Recepcionista (Receptionist):** Gerencia a atribuição das mesas e os pagamentos.
- **Empregado de Mesa (Waiter):** Transmite os pedidos aos cozinheiros e serve as refeições.
- **Cozinheiro (Chef):** Prepara as refeições solicitadas.

## Etapas do Processo
1. **Interpretação do Recepcionista:**
   - Os grupos chegam e são direcionados para uma mesa ou colocados em espera.

2. **Pedido e Serviço de Refeições:**
   - Os grupos pedem a comida, que é preparada pelo cozinheiro e servida pelo empregado.

3. **Finalização e Pagamento:**
   - Após a refeição, os grupos contactam o recepcionista para pagar e sair.

## Sincronização e Implementação Técnica
- Desenvolvimento de uma aplicação em C para simular o restaurante.
- Utilização de **semáforos** e **memória partilhada** para a sincronização dos processos.
- Criação de processos no início do programa, que devem estar ativos apenas quando necessário.

## Arquivos a Modificar
- `semSharedMemGroup.c`
- `semSharedMemChef.c`
- `semSharedMemWaiter.c`
- `semSharedMemReceptionist.c`

## Execução e Testes
- Utilize o comando `make all_bin` na diretoria `src` para compilar.
- Execute `./probSemSharedMemRestaurant` na diretoria `run` para visualizar o resultado.

## Entrega e Ética
- Realização do trabalho em grupos de 2 alunos.
- Respeito a um código de ética rigoroso contra o plágio e a partilha de código.
- Entrega inclui código fonte e um relatório descrevendo a abordagem e testes realizados.

## Prazo de Entrega
- **31 de Dezembro de 2023**

