# Modelagem da População Brasileira com Equações Diferenciais

![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)

## Sobre o Projeto

Este estudo analisa o crescimento da população do Brasil com base em dados históricos. Para isso, são comparados dois modelos matemáticos baseados em equações diferenciais: o modelo Exponencial de Malthus, que prevê um crescimento contínuo, e o modelo Logístico de Verhulst, que considera que a população se estabiliza ao atingir um limite.

A análise inclui o ajuste de cada modelo aos dados, a medição de seus erros para determinar qual é o mais preciso e, por fim, a utilização do modelo vencedor para projetar a população até o ano de 2050.

## Fonte dos Dados

Os dados históricos de população mundial utilizados neste projeto foram obtidos a partir do **[Our World in Data](https://ourworldindata.org/population-growth)**, uma publicação científica online que reúne dados e pesquisas sobre as maiores transformações do mundo. A utilização desses dados é livre e incentivada para fins de pesquisa e educação.

## Tecnologias Utilizadas

As dependências e bibliotecas Python necessárias para este projeto estão listadas no arquivo `requirements.txt`. As principais tecnologias são:

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Scipy**
- **Scikit-learn**

## Resultados e Conclusões

A análise mostrou que o **modelo Logístico de Verhulst** descreve o crescimento da população brasileira de forma muito mais precisa que o modelo Exponencial de Malthus.

-   **Precisão do Modelo:** A superioridade do modelo logístico foi confirmada tanto visualmente, através do ajuste da curva aos dados, quanto por meio das métricas de erro, que apresentaram um **R²** mais próximo de 1 e um **RMSE** ordens de magnitude menor.
-   **Padrão de Crescimento:** O resultado sugere que a população do Brasil não cresce de forma acelerada e sem limites, mas segue um padrão que desacelera e tende a um valor máximo (capacidade de suporte).
-   **Projeção para 2050:** O modelo logístico estimou uma população de **237 milhões de habitantes** em 2050.
-   **Validação:** Este valor se mostrou notavelmente próximo da projeção oficial da ONU, que estima **233 milhões** de habitantes para o mesmo ano, representando uma **diferença de menos de 2%**. A informação foi obtida nesta [reportagem da BBC Brasil](https://www.bbc.com/portuguese/noticias/story/2003/12/printable/031209_brasilcs).

A proximidade entre os resultados valida o modelo logístico como uma ferramenta eficaz e robusta para entender e prever a dinâmica da população brasileira neste contexto.

## Como Executar o Projeto

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/pedrolrm/analise-crescimento-populacao-brasileira.git](https://github.com/pedrolrm/analise-crescimento-populacao-brasileira.git)
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd analise-crescimento-populacao-brasileira
    ```
3.  Instale as dependências a partir do `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```
4.  Abra o notebook:
    - O arquivo `.ipynb` pode ser aberto em um ambiente Jupyter ou carregado diretamente no Google Colab.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## Autor

**Pedro Luca Rocha Manera**

-   [LinkedIn](https://www.linkedin.com/in/pedro-luca-rocha-manera/)
-   Email: `p.lucarocha@gmail.com`
