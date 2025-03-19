<think>
Vou elaborar um README para este projeto. Baseando-me nos arquivos fornecidos, parece que estamos lidando com um sistema de análise de dados de campanhas publicitárias/anúncios, com recursos de validação de dados e visualização por meio de dashboards.
Componentes principais identificados:
app_dashboard.py - Um dashboard Streamlit para análise de KPIs de anúncios
2. aplicacao_completa.py - Uma aplicação de validação de dados de campanhas
validador.py - Um modelo Pydantic para validação de dados de planilhas de vendas
main.py - Um script para gerar relatórios de perfil de dados usando ydata-profiling
data.csv - Conjunto de dados de campanhas publicitárias com métricas de anúncios
O README deve explicar:
Visão geral do projeto
Requisitos/dependências (baseado no requirements.txt)
Estrutura do projeto
Como instalar e usar as diferentes funcionalidades
Exemplos de uso
Descrição das funcionalidades principais
Vou escrever em português do Brasil conforme solicitado.
</think>
Análise de Campanhas de Marketing Digital
Visão Geral
Este projeto é uma solução completa para análise e validação de dados de campanhas de marketing digital. Ele inclui recursos para validar planilhas de campanhas, visualizar KPIs importantes através de dashboards interativos e gerar relatórios detalhados sobre o desempenho das campanhas.
Funcionalidades
Validação de Dados: Validação automatizada de planilhas de campanhas usando modelos Pydantic
Dashboard Interativo: Visualização de KPIs chave de marketing como:
Custo por conversão (CPA)
Custo por clique (CPC)
Taxa de cliques (CTR)
Taxa de conversão
Análise por segmentação
Relatórios Detalhados: Geração de relatórios completos de perfil de dados usando ydata-profiling
Análise Mensal Interativa: Exploração de dados filtrados por mês e métricas específicas
Requisitos
O projeto requer Python 3.8+ e as seguintes dependências principais:
Para instalar todas as dependências:
Estrutura do Projeto
Como Usar
Dashboard de Análise de KPIs
Para executar o dashboard de análise:
O dashboard permite:
Fazer upload de arquivos CSV com dados de campanhas
Visualizar métricas gerais como gastos, cliques e conversões
Analisar o desempenho por segmentação
Explorar dados por mês com visualizações interativas
Validador de Dados
Para validar dados de campanhas:
Esta aplicação permite:
Fazer upload de um arquivo CSV
Validar os dados conforme o modelo definido
Visualizar erros de validação, se houver
Baixar os dados validados
Geração de Relatórios
Para gerar um relatório detalhado dos dados:
O script gera um arquivo HTML com análises detalhadas do conjunto de dados, incluindo:
Estatísticas descritivas
Correlações entre variáveis
Distribuições de dados
Detecção de valores ausentes
Modelo de Dados
O modelo de validação verifica os seguintes campos:
Organizador: ID do organizador da campanha
Ano_Mes: Período da campanha
Tipo de Anúncio: Formato do anúncio (Vídeo, Estático)
Segmentação: Tipo de segmentação utilizada
Métricas: Valores gastos, cliques, impressões e conversões
Outros detalhes da campanha
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias.
Licença
Este projeto está licenciado sob os termos da licença MIT.