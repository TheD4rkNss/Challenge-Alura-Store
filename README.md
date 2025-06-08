# 📊 Análise da Rede Alura Store

## 🎯 Visão Geral do Projeto
Este projeto analisa dados de vendas de 4 lojas fictícias da rede Alura Store para ajudar o Senhor João a decidir qual loja vender para um novo empreendimento. A análise avalia o desempenho da loja com base na receita, avaliações de clientes, categorias de produtos e custos de envio.

## 📁 Dataset
A análise utiliza dados de 4 arquivos CSV que representam diferentes lojas:
- `loja_1.csv` - Dados de vendas da Loja 1
- `loja_2.csv` - Dados de vendas da Loja 2 
- `loja_3.csv` - Dados de vendas da Loja 3
- `loja_4.csv` - Dados de vendas da Loja 4

Cada arquivo contém:
- Informações do produto (nome, categoria, preço)
- Avaliações de clientes (classificações de 1 a 5)
- Custos de envio
- Transações de vendas

## 🛠️ Instalação e Dependências

### Bibliotecas Necessárias
```bash
pip install pandas numpy matplotlib seaborn
```

### Instalação Alternativa
```bash
# Using conda
conda install pandas numpy matplotlib seaborn

# Using requirements.txt (if provided)
pip install -r requirements.txt
```

## 🚀 Como Executar

1. **Clone ou baixe os arquivos do projeto**
2. **Certifique-se de que todos os arquivos CSV estejam no mesmo diretório do seu script Python**
3. **Execute a análise:**

```python
# Basic execution
python store_analysis.py

# Or in Jupyter Notebook
jupyter notebook store_analysis.ipynb
```

## 📈 Analysis Components

The project performs the following analyses:

- 💰 **Revenue Analysis** - Total revenue and revenue per sale by store
- ⭐ **Customer Reviews** - Average ratings and distribution by store
- 📦 **Product Categories** - Best-selling categories and products
- 🚚 **Shipping Costs** - Average shipping costs by store
- 📊 **Performance Metrics** - Comprehensive store comparison

## 📋 Saída Esperada

A análise gera:
- 📊 Gráficos de comparação de desempenho
- 📈 Visualizações de receita e vendas  
- ⭐ Distribuições de classificações de clientes
- 📝 Relatório de recomendação final
- 📄 Tabela detalhada de métricas de desempenho

## 🎯 Principais Descobertas

Com base na análise:
- **Recomendação:** Vender a Loja 4 (menor receita e eficiência)
- **Melhor Desempenho:** Loja 1 (maior receita total)
- **Satisfação do Cliente:** Todas as lojas mantêm boas classificações (4.0+)
- **Envio:** A Loja 4 tem os menores custos de envio, mas o pior desempenho geral

## 📞 Suporte

Se você encontrar problemas:
1. Verifique se todos os arquivos CSV estão presentes e formatados corretamente
2. Verifique se todas as dependências estão instaladas
3. Garanta a compatibilidade da versão do Python (Python 3.6+)
4. Verifique os caminhos dos arquivos e a estrutura do diretório
## 📄 Licença 

Este projeto é para fins educacionais como parte do treinamento em análise de dados.

---