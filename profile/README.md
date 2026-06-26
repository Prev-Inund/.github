# PREV-INUND — Projeto Preditivo de Cheias

Bem-vindo à organização PREV-INUND: uma iniciativa tecnológica e científica dedicada à monitoramento, previsão e mitigação de cheias na Região Metropolitana de Porto Alegre.

**Missão:** Fornecer informação operacional, alertas antecipados e relatórios de risco ambiental para apoiar a proteção civil, gestores públicos e comunidades locais frente a eventos de inundação.

**Objetivo:** Tornar-se a referência em previsão hidrológica integrada, combinando séries históricas, monitoramento em tempo real.

---

## Sobre o Projeto

O Projeto Prev-Inund integra uma rede de estações hidrometeorológicas distribuídas pelos quatro principais afluentes da bacia do Guaíba (Caí, Sinos, Taquari, Gravataí e Jacuí). Os sensores transmitem dados telemétricos (precipitação, nível e vazão), que alimentam algoritmos de conversão nível→vazão e modelagem de propagação de cheias.

Principais componentes:
- Malha de estações telemétricas
- Pipeline de ingestão, validação e normalização de dados (CSV/telemetria)
- Motor algorítmico em Python para curvas de descarga e previsão de onda de cheia
- Dashboard web e sistema de alertas automáticos

---

## Principais Funcionalidades

- Monitoramento contínuo em tempo real das estações
- Conversão dinâmica de nível para vazão por curvas de descarga locais
- Calibração automática com base em dados históricos (base iniciada em 1942)
- Cálculo do tempo de propagação da onda de cheia até o Lago Guaíba
- Avaliação da influência da degradação das APPs no Lag Time e no assoreamento
- Geração de alertas e relatórios de risco para proteção civil e autoridades

---

## Entregáveis

- Dashboard de monitorização e visualizações geoespaciais
- Sistema de Alerta Antecipado (SAA) com níveis de risco e tempo de aviso
- Relatórios periódicos de risco ambiental e mapas de prioridade para restauração
- Repositórios de código (Backend e frontend) e documentação

