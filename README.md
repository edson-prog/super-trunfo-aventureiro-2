Estrutura do Programa
1. Definição das Cartas
O jogo utiliza uma estrutura chamada Carta, que armazena os dados de um país. Cada carta tem os seguintes atributos:

Nome do País: Representado por uma string.
População: Um valor inteiro que indica o número de habitantes do país.
Área: Um número de ponto flutuante que indica a área do país em quilômetros quadrados.
PIB: Um número de ponto flutuante representando o Produto Interno Bruto do país.
Número de Pontos Turísticos: Um valor inteiro que indica a quantidade de pontos turísticos do país.
Densidade Demográfica: Um valor de ponto flutuante calculado dividindo a população pela área do país (já feito em um desafio anterior).
2. Menu Interativo
O programa exibe um menu que oferece ao jogador opções para comparar diferentes atributos das cartas dos países. O jogador escolhe um número correspondente a um dos atributos (como população, área, PIB, etc.). O menu também oferece a opção de sair, caso o jogador não queira continuar.

Menu de Atributos:
População
Área
PIB
Número de Pontos Turísticos
Densidade Demográfica
Sair
3. Comparação das Cartas
Quando o jogador escolhe um atributo do menu, o programa compara as cartas dos dois países de acordo com a regra definida:

Para atributos como População, Área, PIB e Número de Pontos Turísticos, o país com o maior valor vence.
Para Densidade Demográfica, vence o país com o menor valor, pois uma densidade demográfica mais baixa é considerada vantajosa.
O resultado da comparação é mostrado na tela, incluindo o nome do país, o valor do atributo e quem venceu. Se os valores forem iguais, é declarado um empate.

4. Exibição do Resultado
O programa sempre exibe a comparação entre os dois países com o atributo selecionado, mostrando:

O nome de ambos os países.
O valor do atributo para cada país.
Qual país venceu a comparação (ou "Empate!" caso os valores sejam iguais).
5. Execução Contínua
O programa continua exibindo o menu e esperando pela escolha do jogador até que o jogador escolha a opção "0" para sair. O fluxo de execução do programa se repete até o usuário decidir encerrar.

6. Tratamento de Entrada
O programa deve garantir que as escolhas do usuário sejam válidas. Por exemplo:

Caso o jogador insira um número inválido no menu (fora do intervalo de 0 a 5), uma mensagem de erro é exibida, e o menu é mostrado novamente.
7. Finalização
Quando o jogador escolhe a opção de sair (opção 0), o programa exibe uma mensagem de encerramento e termina a execução.

Como Funciona:
Cartas de Países: O programa tem duas cartas fixas (Brasil e Alemanha, por exemplo). O jogador pode escolher qual atributo dessas cartas será comparado.

Menu: O menu permite que o jogador escolha qual atributo ele quer comparar. O programa então exibe as informações dos dois países e compara os valores do atributo escolhido.

Resultado da Comparação: O programa avalia qual país tem o valor maior (ou menor, no caso da densidade demográfica) para o atributo escolhido e exibe quem venceu. Caso ambos os valores sejam iguais, o programa indica um empate.

Repetição até o Usuário Decidir Sair: O menu será mostrado repetidamente até que o jogador escolha sair (opção 0).

Funcionalidades Especiais:
Densidade Demográfica: Esta é a única exceção, pois o país com a menor densidade demográfica vence a comparação, ao contrário dos outros atributos onde vence o maior valor.

Simplicidade do Jogo: O código mantém o jogo simples, usando apenas entradas do usuário para controlar a lógica de comparação, sem complicações adicionais.

Possíveis Melhorias:
Entrada de Dados Dinâmicos: O programa pode ser expandido para permitir que o usuário insira seus próprios dados de cartas de países, ao invés de usar valores fixos para as cartas.

Validação de Entrada: Pode-se adicionar uma validação mais robusta para garantir que o usuário insira valores válidos no menu (por exemplo, impedir que o usuário insira valores não numéricos).

Suporte a Múltiplas Cartas: O jogo poderia ser expandido para comparar mais de duas cartas ao mesmo tempo, tornando o jogo mais dinâmico.
