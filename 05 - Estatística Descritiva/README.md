# Análise de Dados sobre Pedidos de Demissão

Este projeto tem como objetivo analisar os fatores que podem ter contribuído para os pedidos de demissão de funcionários de uma empresa. A partir de medidas descritivas e correlações, buscamos identificar padrões e possíveis áreas problemáticas.

## Escopo

Considere a base de dados a seguir:

[![Planilha](https://img.shields.io/badge/Base%20de%20Dados-📊-gray?style=for-the-badge)](https://docs.google.com/spreadsheets/d/1q64TPaErzCYgXX6Exp1hopq_L2JnRT3j/edit?usp=sharing&ouid=110283574113665030533&rtpof=true&sd=true)

Você foi contratado para fazer as medidas de estatística descritivas para as variáveis quantitativas de uma base de dados sobre possíveis motivos de desgaste dos funcionários de uma empresa que os levaram a pedir demissão, sua tarefa é calcular essas medidas  e trazer possíveis causas a partir da interpretação dos resultados.

Dica: Antes de calcular as medidas separe os dados em dois grupos, os que pediram demissão e os que não pediram


## Principais Descobertas

### Baixa Satisfação com o Ambiente de Trabalho
- Média de satisfação: **2.46** (escala de 1 a 4)
- Primeiro quartil: **1.0**, Moda: **1**
- Indica um ambiente possivelmente não acolhedor ou sem incentivos motivacionais.

### Dificuldade com o Equilíbrio Vida-Trabalho
- Média: **2.66** (escala de 1 a 4), Primeiro quartil: **2.0**
- Sugere que muitos funcionários tiveram dificuldades para manter um equilíbrio saudável.

### Renda e Remuneração
- Renda mensal média: **4.787**
- Salário mensal médio: **14.559**
- A alta variabilidade sugere disparidade salarial, o que pode afetar a satisfação dos funcionários.

### Baixa Satisfação nas Relações Fora do Trabalho
- Média de satisfação: **2.60**
- Sugere que o desgaste profissional pode estar impactando negativamente a vida pessoal.

### Análise por Setor
- **Diretor de manufatura**: Média de satisfação **2.3**, alto nível de insatisfação.
- **Executivo de vendas**: Alta taxa de demissão.
- **Recursos Humanos**: Satisfação mediana, mas indicativos de problemas com gestão.

## Metodologia

Os dados foram analisados utilizando Python e bibliotecas como Pandas e NumPy. Foram realizadas medições estatísticas e cálculo de correlação entre variáveis.

### Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Google Sheets (fonte de dados)
- Qlik Sense (para visualização de dados)

## Como Utilizar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-repositorio.git
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install pandas numpy
   ```
3. Execute o script de análise:
   ```bash
   python analise_demissao.py
   ```

## Conclusão
A análise identificou fatores críticos que podem estar impactando a retenção de funcionários. Empresas que desejam reduzir a taxa de turnover devem revisar suas políticas de bem-estar, equilíbrio entre vida e trabalho, e estrutura salarial.

Além disso, setores específicos apresentam maior vulnerabilidade, exigindo uma abordagem personalizada para retenção de talentos.

---

Caso tenha sugestões ou dúvidas, fique à vontade para abrir uma issue ou contribuir com melhorias!




