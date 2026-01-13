# Toy-Bot
Este repositório contém a implementação do Toy Robot, um projeto acadêmico desenvolvido com o objetivo de aplicar conceitos fundamentais de lógica de programação, estruturas de controle, modelagem de problemas e Programação Orientada a Objetos.

O projeto simula o comportamento de um robô virtual que se movimenta sobre uma superfície plana (grade), obedecendo a um conjunto específico de comandos. A aplicação foi construída de forma modular, priorizando clareza, organização do código e facilidade de manutenção.

## Objetivos do Trabalho
- Simular o movimento de um robô em um ambiente controlado
- Aplicar conceitos de orientação a objetos
- Trabalhar validação de comandos e estados
- Desenvolver raciocínio lógico e algorítmico
- Implementar regras de negócio de forma consistente

## Descrição do Problema

O Toy Robot opera sobre uma superfície bidimensional (tabuleiro), podendo se mover apenas dentro de seus limites. O robô recebe comandos textuais e deve executá-los respeitando as regras do ambiente.

O sistema deve garantir que:

- O robô não saia dos limites do tabuleiro
- Apenas comandos válidos sejam executados
- O estado do robô (posição e direção) seja sempre consistente

## Funcionalidades Implementadas

O projeto permite:

- Posicionar o robô no tabuleiro por meio do comando PLACE
- Movimentar o robô uma unidade por vez com o comando MOVE
- Rotacionar o robô para a esquerda (LEFT) ou direita (RIGHT)
- Exibir a posição atual e direção do robô com o comando REPORT
- Validar comandos inválidos ou movimentos fora do tabuleiro
