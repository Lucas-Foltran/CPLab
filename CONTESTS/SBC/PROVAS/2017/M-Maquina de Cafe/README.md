# Máquina de Café
###### [Caminho para Beecrowd](https://www.beecrowd.com.br/judge/pt/problems/view/2670)
O novo prédio da Sociedade Brasileira de Computação (SBC) possui 3 andares. Em determinadas épocas do ano, os funcionários da SBC bebem muito café. Por conta disso, a presidência da SBC decidiu presentear os funcionários com uma nova máquina de expresso. Esta máquina deve ser instalada em um dos 3 andares, mas a instalação deve ser feita de forma que as pessoas não percam muito tempo subindo e descendo escadas.

Cada funcionário da SBC bebe 1 café expresso por dia. Ele precisa ir do andar onde trabalha até o andar onde está a máquina e voltar para seu posto de trabalho. Todo funcionário leva 1 minuto para subir ou descer um andar. Como a SBC se importa muito com a eficiência, ela quer posicionar a máquina de forma a minimizar o tempo total gasto subindo e descendo escadas.

Sua tarefa é ajudar a diretoria a posicionar a máquina de forma a minimizar o tempo total gasto pelos funcionários subindo e descendo escadas.

## Entrada
A entrada consiste em $3$ números, $A_1 , A_2 , A_3 (0 ≤ A_1 , A_2 , A_3 ≤ 1000)$, um por linha, onde $A_i$ representa o número de pessoas que trabalham no i-ésimo andar.

## Saída
Seu programa deve imprimir uma única linha, contendo o número total de minutos a serem gastos com o melhor posicionamento possível da máquina.

| Exemplo de Entrada | Exemplo de Saída |
|--------------------|------------------|
| 10                 | 80               |
| 20                 |                  |
| 30                 |                  |

| Exemplo de Entrada | Exemplo de Saída |
|--------------------|------------------|
| 10                 | 60               |
| 30                 |                  |
| 20                 |                  |

| Exemplo de Entrada | Exemplo de Saída |
|--------------------|------------------|
| 30                 | 100              |
| 10                 |                  |
| 20                 |                  |
