# Queue

Em uma estrutura de dados do tipo fila (queue), um nó é uma unidade básica que armazena um elemento da fila juntamente com uma referência para o próximo elemento na sequência. 

### Cada nó em uma fila possui dois principais atributos:

- Valor (ou Dado): É o elemento que está sendo armazenado na fila. Pode ser qualquer tipo de dado, como um número, uma string, um objeto, etc.


- Referência para o Próximo Nó: Em implementações baseadas em listas encadeadas, cada nó possui um ponteiro (ou referência) que aponta para o próximo nó na sequência da fila. Essa referência é fundamental para manter a ordem dos elementos na fila, onde o primeiro elemento inserido é o primeiro a ser removido (FIFO - First In, First Out).

## Funcionamento de uma Fila:

> Inserção (Enqueue): Adiciona um novo elemento ao final da fila.

> Remoção (Dequeue): Remove o elemento que está no início da fila.

> Consulta (Peek): Obtém o elemento que está no início da fila sem removê-lo.

## Utilização em Aplicações:

- Filas de Tarefas: São utilizadas em sistemas para processamento de tarefas em ordem de chegada, como em impressão de documentos ou processamento de pedidos.
- Buffers e Filas de Mensagens: Em sistemas distribuídos e de comunicação, filas são usadas para gerenciar o fluxo de dados entre componentes.

## Características Principais:
- Estrutura Linear: Os elementos são organizados em uma sequência única, onde cada elemento tem um único sucessor.

- Operações Eficientes: As operações de inserção e remoção têm complexidade de tempo constante O(1), desde que a implementação seja adequada.

## Conclusão:
O conceito de nó em uma fila é fundamental para entender como os elementos são organizados e manipulados em uma estrutura de dados do tipo fila. Cada nó contém um elemento de dados e uma referência para o próximo nó na sequência, garantindo que a fila mantenha a ordem e permitindo operações eficientes de inserção e remoção.