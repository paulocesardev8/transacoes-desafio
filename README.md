#### transacoes-desafio
### Transações acima de um valor - Desafio de código da DIO

### Descrição
Você foi solicitado a criar um programa que analise uma lista de transações bancárias e filtre apenas aquelas que ultrapassam um valor limite. Seu programa deve retornar uma nova lista contendo somente as transações cujo valor absoluto (ignorar sinal negativo) seja maior que o limite informado.

#### Atenção:
As transações incluem tanto depósitos (positivos) quanto saques (negativos).
Valor absoluto é o critério para filtrar, então tanto 300 (depósito) quanto -150 (saque) serão considerados, já que ambos têm módulo maior que 100.
### Entrada
Uma lista de valores representando as transações bancárias (ex.: [100, -50, 300, -150]).
Um valor limite (inteiro ou decimal) fornecido pelo usuário.

### Saída
Uma nova lista com as transações que ultrapassam o limite, no formato: "Transações: [X, Y, Z]"

### Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

|Entrada |	Saída      |
| :------- | :--------------|
|`[100, -50, 300, -150], 100` |	`Transações: [300, -150]`|
|`[200, -50, 400], 150` |	`Transações: [200, 400]`|
|`[1000, -75, 800], 500`|	`Transações: [1000, 800]`|

