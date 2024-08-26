<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# Daily Pattern Analyzer

## Description

The **Daily Pattern Analyzer** project is designed to identify and analyze recurring patterns in stock performance based on different days of the week. The algorithm examines historical market data to determine if there are consistent trends or anomalies specific to certain days, such as Mondays, Tuesdays, Wednesdays, Thursdays, and Fridays.

## Features

- **Data Import**: Retrieves historical stock data using the MetaTrader5 library.
- **Pattern Analysis**: Assesses stock performance for each day of the week.
- **Outlier Handling**: Filters out outliers to ensure more accurate pattern detection.
- **Visualization and Export**: Aggregates the results into a DataFrame and exports them to an Excel file for easy analysis and review.

## Workflow

1. **Import Libraries**: Loads necessary libraries for data processing and manipulation.
2. **Create Asset List**: Specifies the assets to be analyzed, which can be customized to include different stocks or indices.
3. **Set Start Date**: Defines the initial date for analyzing historical data.
4. **Calculate Results**: Implements a function to:
   - Initialize the MetaTrader5 connection.
   - Retrieve historical data for the specified timeframes.
   - Calculate performance metrics for each day of the week.
   - Remove outliers to improve pattern accuracy.
   - Aggregate data by day of the week and compute relevant statistics.
5. **Process Data**: Executes the calculation function for all selected assets and timeframes, consolidating the results.
6. **Export Results**: Exports the analyzed data to an Excel file for further inspection and analysis.

## Usage

1. **Install Dependencies**: Make sure all required libraries are installed.
2. **Define Asset List**: Set up the list of assets you wish to analyze, including specific stocks or indices.
3. **Run the Code**: Execute the script to analyze performance patterns for each day of the week.
4. **View and Export Results**: Results will be compiled and exported to an Excel file for detailed review.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to add new features, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

# Analisador de Padrões Diários

## Descrição

O **Analisador de Padrões Diários** é um projeto projetado para identificar e analisar padrões recorrentes no desempenho das ações com base em diferentes dias da semana. O algoritmo examina dados históricos do mercado para determinar se existem tendências ou anomalias consistentes específicas para certos dias, como segundas-feiras, terças-feiras, quartas-feiras, quintas-feiras e sextas-feiras.

## Funcionalidades

- **Importação de Dados**: Recupera dados históricos das ações utilizando a biblioteca MetaTrader5.
- **Análise de Padrões**: Avalia o desempenho das ações para cada dia da semana.
- **Tratamento de Outliers**: Filtra outliers para garantir uma detecção de padrões mais precisa.
- **Visualização e Exportação**: Consolida os resultados em um DataFrame e exporta para um arquivo Excel para fácil análise e revisão.

## Fluxo de Trabalho

1. **Importar Bibliotecas**: Carrega as bibliotecas necessárias para processamento e manipulação de dados.
2. **Criar Lista de Ativos**: Especifica os ativos a serem analisados, podendo ser personalizados para incluir diferentes ações ou índices.
3. **Definir Data Inicial**: Estabelece a data inicial para analisar os dados históricos.
4. **Calcular Resultados**: Implementa uma função para:
   - Inicializar a conexão com o MetaTrader5.
   - Recuperar dados históricos para os períodos de tempo especificados.
   - Calcular métricas de desempenho para cada dia da semana.
   - Remover outliers para melhorar a precisão dos padrões.
   - Agregar dados por dia da semana e calcular estatísticas relevantes.
5. **Processar Dados**: Executa a função de cálculo para todos os ativos e períodos de tempo selecionados, consolidando os resultados.
6. **Exportar Resultados**: Exporta os dados analisados para um arquivo Excel para inspeção e análise detalhadas.

## Uso

1. **Instalar Dependências**: Certifique-se de que todas as bibliotecas necessárias estejam instaladas.
2. **Definir Lista de Ativos**: Configure a lista de ativos que deseja analisar, incluindo ações ou índices específicos.
3. **Executar o Código**: Execute o script para analisar os padrões de desempenho para cada dia da semana.
4. **Visualizar e Exportar Resultados**: Os resultados serão compilados e exportados para um arquivo Excel para revisão detalhada.

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões para melhorias ou quiser adicionar novos recursos, por favor, abra um problema ou envie um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

