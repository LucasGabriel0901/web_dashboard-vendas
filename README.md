Análise de Satisfação de Clientes - E-commerce Olist
Este projeto apresenta uma Análise Exploratória de Dados (EDA) fundamentada no conjunto de dados público da Olist. O foco central da investigação é identificar e quantificar os fatores logísticos e operacionais que impactam diretamente a percepção de valor e a satisfação do consumidor final.

Como entrega técnica, foi desenvolvido um dashboard interativo utilizando Streamlit, permitindo a exploração de indicadores de performance (KPIs) e a filtragem de métricas de entrega e avaliações em tempo real.

Objetivos da Análise
A análise foi estruturada para solucionar problemas de negócio e extrair insights sobre os seguintes pontos:

Impacto Logístico: Correlação estatística entre o tempo de transporte e a pontuação atribuída pelo cliente.

Gestão de Expectativas: Análise comparativa do impacto de pedidos entregues fora do prazo estimado nas notas de avaliação.

Performance por Categoria: Identificação de clusters de produtos com desempenho crítico em termos de satisfação.

Geolocalização e Logística: Mapeamento da distribuição de pedidos e análise de lead time médio segmentado por região e estado.

Tecnologias e Ferramentas
O projeto utiliza uma stack moderna de ciência de dados para garantir escalabilidade e reprodutibilidade:

Linguagem: Python

Processamento de Dados: Pandas para limpeza, transformação e agregação de grandes volumes de dados.

Visualização: Plotly para gráficos dinâmicos e interativos.

Interface: Streamlit para a disponibilização da ferramenta de BI em ambiente web.

Infraestrutura: Docker (Dev Containers) para padronização do ambiente de desenvolvimento.

Estrutura do Repositório
data/: Diretório reservado para os arquivos brutos e processados (conforme política de armazenamento do projeto).

notebooks/: Arquivos Jupyter contendo o passo a passo da limpeza de dados e análise exploratória inicial.

src/: Código-fonte da aplicação Streamlit e scripts de processamento.

config/: Arquivos de configuração do ambiente e dependências (requirements.txt ou .devcontainer).

Metodologia de Execução
Tratamento de Dados: Unificação das diversas tabelas do dataset (pedidos, itens, pagamentos e avaliações) via chaves primárias.

Engenharia de Atributos: Criação de métricas como "Tempo de Entrega Real" e "Diferença da Data Estimada".

Desenvolvimento do Dashboard: Integração dos insights gerados em uma interface funcional para tomada de decisão.
