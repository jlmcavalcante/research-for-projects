# Projeto de monitoramento

## Objetivo do projeto

- Este projeto tem como objetivo desenvolver uma solução de monitoramento para um sistema de inteligência artificial que realiza comunicações dinâmicas com múltiplas plataformas externas por meio de APIs. A proposta visa estabelecer um mecanismo abrangente de observabilidade, capaz de acompanhar e avaliar o funcionamento das integrações em três dimensões complementares:
  - Sistema: identificar em tempo real quais comunicações estão ativas e detectar falhas de conectividade entre os sistemas integrados;
  - Semântica: monitorar a quantidade e o conteúdo das mensagens e tokens trocados, bem como os fluxos de comunicação entre os diferentes sistemas;
  - Custas: mensurar o tráfego de dados e os custos financeiros associados ao uso e processamento dessas comunicações.
- Como parte deste trabalho, será realizado o levantamento de requisitos técnicos e funcionais, bem como uma pesquisa exploratória sobre estudos e soluções similares, com o objetivo de embasar tecnicamente as decisões de arquitetura, ferramentas e estratégias de monitoramento a serem adotadas.

## Resultado Desejado

- Como resultado deste trabalho, espera-se a elaboração de um documento de projeto de software que descreva de forma estruturada a proposta de monitoramento do sistema de inteligência artificial em questão. Este documento deverá servir como base conceitual e técnica para a futura implementação do sistema de monitoramento, e será composto pelas seguintes seções:
  - Introdução: apresentação do contexto, motivação e objetivos do projeto;
  - Trabalhos Relacionados: levantamento e análise de soluções existentes e estudos correlatos na literatura;
  - Metodologia: descrição das abordagens utilizadas para levantamento de requisitos, análise de cenário e definição da arquitetura proposta;
  - Cenário: descrição técnica e funcional do sistema atual, incluindo os fluxos de comunicação entre a IA e os sistemas externos (como WhatsApp, Azure e SEPRO);
  - Proposição de Monitoramento: definição da arquitetura de monitoramento, abrangendo os três eixos principais (Sistema, Semântica e Custas), bem como os componentes e ferramentas recomendados para sua viabilização.

## Temas relacionados

- Observabilidade em sistemas distribuídos
- Monitoramento semântico de APIs e mensagens
- Custos e métricas em sistemas baseados em nuvem
- MLOps e monitoramento de pipelines de IA
- Monitoramento de aplicações em ambientes híbridos/multicloud

## Ferramentas relacionadas
- [OpenTelemetry](https://opentelemetry.io/)
- [Arize Phoenix](https://docs.arize.com/phoenix)
- [Grafana Loki](https://grafana.com/docs/loki/latest/)
- [Grafana](https://grafana.com/solutions/?pg=hp&plcmt=hero-slide-3)
- [Prometheus](https://prometheus.io/docs/introduction/overview/)
- [Kibana](https://www.elastic.co/pt/kibana#observability)