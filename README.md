# LEIA-ME

Olá me chamo Luiz, hoje estou aqui para guiar o leitor sobre como abrir e executar meu programa realizado para a tarefa de Algoritimos e Programação do professor Alessom.
GRUPO
LUIZ FELIPE ARSEGO

O Programa de Cálculo de Média de Aluno
Este programa permite calcular a média de um aluno com base em suas notas. Ele também classifica o aluno como aprovado, em recuperação ou reprovado, de acordo com a média obtida.

Pré-requisitos
Compilador de C (ex: GCC) instalado no sistema.
Como utilizar o programa
Abra um editor de texto e copie o código do programa para um novo arquivo. Salve o arquivo com a extensão ".c" (ex: programa.c).

Abra o terminal ou prompt de comando e navegue até o diretório onde o arquivo do programa foi salvo.

Compile o programa utilizando o compilador de C. No caso do GCC, utilize o seguinte comando:


gcc programa.c -o programa
Após compilar com sucesso, execute o programa digitando o seguinte comando no terminal ou prompt de comando:


Copy code
./programa
O programa solicitará as informações do aluno:

Digite o nome do aluno: Insira o nome do aluno.
Digite o número de notas do aluno (máximo X): Insira o número de notas que deseja considerar para o cálculo da média. Substitua "X" pelo máximo de notas permitido (no código fornecido, o valor máximo é 20).
Em seguida, digite as notas do aluno conforme solicitado pelo programa.

Após inserir todas as notas, o programa exibirá o nome do aluno, o número de notas e as notas inseridas.

Por fim, o programa calculará a média do aluno e o classificará como "APROVADO", "EM RECUPERAÇÃO" ou "REPROVADO", de acordo com a média obtida.

O programa será encerrado.

**Observações**
Certifique-se de inserir as notas corretamente, utilizando ponto (.) como separador decimal.
Caso o número de notas inserido seja maior que o máximo permitido (definido pela constante MAX_NOTAS no código), o programa exibirá uma mensagem de erro e será encerrado.
Caso deseje alterar o valor máximo de notas permitido, você pode modificar a constante MAX_NOTAS no código e recompilar o programa.
