# 🗂 SIGOR Data Dashboard

Bem-vindo ao repositório SIGOR Data Dashboard, que organiza, consolida e analisa dados de geração e destinação de resíduos. Este projeto transforma arquivos brutos do SIGOR em dashboards interativos, permitindo insights rápidos sobre a performance das empresas e o manejo de resíduos.

# 🔹 Fluxo de Dados

# 📥 Extração Mensal
Arquivos em Excel são exportados do SIGOR todo mês e armazenados em pastas separadas:

Arquivo Sigor - <mês_do_ano>

# 🧹 Limpeza e Padronização
Padronização de nomes de empresas, tipos de resíduos e unidades.
Correção de inconsistências para garantir dados confiáveis.

# 🔗 Consolidação
Uma query central (Power Query) agrega todos os meses em uma base única, que é a fonte dos dashboards no Power BI.

# 📊 Visualização Interativa
Dashboards permitem analisar:

Geração de resíduos por empresa

Geração de resíduos por tipo de resíduo

Total destinado no mês

Distribuição por classe de resíduos
 
# 📊 Recursos Interativos do Dashboard

Menus Suspensos (Slicers)
Permitem filtrar dados por classe ou tipo de resíduo.

Linha do Tempo
Segmenta dados por período, mostrando tendências mensais ou anuais.

Tooltip por Empresa por tipo de Destinação
Ao passar o mouse sobre o visual, mostra detalhes da empresa selecionada.

Dashboards Dinâmicos
Todos os gráficos respondem a filtros e seleção de período.

# 🔧 Ferramentas

Excel → Limpeza e tratamento de dados brutos

Power Query → Consolidação dos dados

Power BI → Criação de dashboards interativos

# 🚀 Objetivo

Transformar dados do SIGOR em insights estratégicos, permitindo:

Monitoramento eficiente da geração e destinação de resíduos

Apoio à tomada de decisão ambiental em relação a quantidade de emissão de CADRIs, atendimento a legislação.

Relatórios confiáveis para gestão e auditorias
