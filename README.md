# ProjetoRegressaoLinear
Por Larissa Ribeiro Firminio e Álisson Natan dos Anjos Pinheiro

### Código em Markdown

```markdown
# Previsão de Taxa de Engajamento no Instagram com Regressão Linear

## Descrição do Projeto
Este projeto aplica modelos de Regressão Linear para prever a taxa de engajamento de influenciadores do Instagram, utilizando métricas como número de seguidores, posts, e curtidas médias. O objetivo principal é desenvolver um modelo preditivo eficiente, analisando relações entre variáveis e avaliando o desempenho através de métricas estatísticas.

## Instalação
1. Clone este repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. Certifique-se de ter o Python instalado (>=3.7).
3. Instale as dependências necessárias executando:
   ```bash
   pip install -r requirements.txt
   ```
4. Para usuários do Google Colab:
   - Faça upload dos dados (`top_insta_influencers_data.csv`) para o ambiente.
   - Instale as bibliotecas não incluídas diretamente no notebook.

## Como Executar
1. Abra o arquivo `main.ipynb` no Google Colab ou em outro ambiente Jupyter.
2. Certifique-se de que o arquivo `top_insta_influencers_data.csv` está no mesmo diretório do código.
3. Execute as células do notebook sequencialmente para:
   - Analisar os dados.
   - Treinar o modelo.
   - Avaliar os resultados.
4. Para execução local, utilize o comando:
   ```bash
   python main.py
   ```
   (Certifique-se de ajustar os caminhos para os dados no script).

## Estrutura dos Arquivos
- `/main.ipynb`: Código principal do projeto no formato notebook.
- `/main.py`: Script para execução direta.
- `/data`: Contém o arquivo `top_insta_influencers_data.csv` com os dados do projeto.
- `/docs`: Relatório técnico descrevendo as etapas e resultados obtidos.

## Tecnologias Utilizadas
- **Python**: Linguagem base para desenvolvimento.
- **Bibliotecas**:
  - `pandas`: Manipulação e análise de dados.
  - `numpy`: Operações matemáticas.
  - `matplotlib` e `seaborn`: Visualizações de dados.
  - `scikit-learn`: Modelagem e avaliação estatística.
- **Google Colab**: Ambiente para execução remota.

## Métricas de Avaliação
- **Erro Quadrático Médio (MSE)**: Mede a magnitude média do erro ao quadrado.
- **Erro Absoluto Médio (MAE)**: Mede a média dos erros absolutos.
- **Coeficiente de Determinação (R²)**: Avalia a proporção de variância explicada pelo modelo.

## Resultados
O modelo demonstrou desempenho razoável, capturando tendências principais na taxa de engajamento, mas indicando a necessidade de modelos mais complexos para melhorar a precisão. Visualizações gráficas e métricas de desempenho estão disponíveis no notebook.

---

*Contribuições são bem-vindas. Para melhorias, crie um pull request ou abra uma issue no repositório GitHub.*

