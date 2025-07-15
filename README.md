# Credt-score
# Modelo Preditivo para Risco de Inadimplência em Cartões de Crédito

## Descrição
Este projeto tem como objetivo construir um modelo preditivo para identificar o risco de inadimplência de solicitantes de cartão de crédito. O modelo será capaz de prever o risco de um solicitante não pagar o cartão, usando dados históricos de características pessoais e financeiras.

## Objetivo
O objetivo é criar um modelo preditivo que ajude os mutuários a tomar decisões mais informadas ao solicitar um cartão de crédito, analisando variáveis que indicam o risco de inadimplência.

## Dicionário de Dados
| Variável               | Descrição                                       | Tipo     |
|------------------------|-------------------------------------------------|----------|
| sexo                   | Gênero do solicitante                           | M/F      |
| posse_de_veiculo        | Se o solicitante possui veículo                | Y/N      |
| posse_de_imovel         | Se o solicitante possui imóvel                 | Y/N      |
| qtd_filhos             | Quantidade de filhos                           | Inteiro  |
| tipo_renda             | Tipo de renda (ex: assalariado, autônomo)       | Texto    |
| idade                  | Idade do solicitante                            | Inteiro  |
| estado_civil           | Estado civil do solicitante                     | Texto    |
| ...                    | ...                                             | ...      |

## Instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/usuario/projeto.git

## Execução do código
python main.py

## Estrutura dos arquivos 
├── data/
│   ├── demo01.csv        # Dados de entrada
├── src/
│   ├── main.py           # Código principal
├── README.md             # Este arquivo
├── requirements.txt      # Dependências

## Modelo
Usamos a técnica de Random Forest, um classificador versátil e robusto para prever a inadimplência com base em características dos solicitantes.

## Resultados
O modelo apresentou uma taxa de inadimplência de 7,25%. As métricas de avaliação incluem:

Acurácia: 92%
Precisão: 80%
Recall: 75%

## Conclusões

O modelo consegue identificar efetivamente os solicitantes de alto risco. Há espaço para melhorias com a inclusão de mais variáveis financeiras.


