# PS-Inteli-Academy
## Dashboard de Notícias de Inteligência Artificial com Automação
*Descrição do Projeto*

Este projeto consiste no desenvolvimento de um pipeline automatizado para coleta, processamento e visualização de notícias sobre Inteligência Artificial.
A solução integra duas fontes de dados, utiliza Inteligência Artificial para estruturar informações e disponibiliza os resultados em um dashboard interativo.
O objetivo é transformar dados não estruturados (notícias) em informações organizadas e úteis para análise.

*Tecnologias Utilizadas*

n8n (automação de workflows)

OpenAI (processamento de linguagem natural)

Airtable (armazenamento e dashboard)

RSS Feeds (TechCrunch e MIT News)

*Funcionamento do Sistema*

O fluxo automatizado segue as seguintes etapas:

Coleta de Dados

Extração de notícias via RSS: TechCrunch e MIT News

Limitação da quantidade de notícias para evitar sobrecarga e rate limit

Merge das notícias coletadas em um único fluxo

Processamento com IA

Geração de resumo das notícias

Classificação automática por categoria

Conversão para formato JSON estruturado

Padronização das informações

Inserção automática dos dados no Airtable

Exposição dos Dados

Retorno via Webhook para consumo externo

*Dashboard*

Entrar com email do inteli; link do dashboard: https://airtable.com/invite/l?inviteId=invk1bZq9kav50u0I&inviteToken=8fad0f236013f84de51b7b370dd6ae9a94838f5c4d435f65f314271680bba40f&utm_medium=email&utm_source=product_team&utm_content=transactional-alerts


Os dados são apresentados em um dashboard interativo no Airtable, permitindo:

Visualização das notícias organizadas;
Filtro por categoria;
Análise simplificada de tendências;
