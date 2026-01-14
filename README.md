🎯 Sobre o Projeto
Este projeto é o resultado de um Trabalho de Conclusão de Curso (TCC) que visa auxiliar a inclusão escolar de alunos com Transtorno do Espectro Autista (TEA). O objetivo principal é desenvolver um ecossistema inteligente capaz de detectar sinais precoces de crises sensoriais ou emocionais através da fusão de dados fisiológicos e comportamentais.

A solução integra Inteligência Artificial (IA) e um Aplicativo Móvel para criar uma rede de apoio entre alunos, responsáveis e educadores.

🚀 Funcionalidades Principais
1.Pulseira: Protótipo baseado em Arduino para coleta em tempo real de:

Frequência Cardíaca: Para detectar estados de ansiedade ou estresse.

Acelerometro: Para identificar comportamentos motores repetitivos ou agitação física.

Transmissão contínua: Envio de dados via Bluetooth/Wi-Fi para a API central.

2. Coleta de Dados Multidimensionais (Questionários)
O sistema coleta dados subjetivos que fornecem contexto à IA:

Módulo Responsável: Cadastro do perfil sensorial, histórico de informações e rotina do aluno.

Módulo Aluno: * Diário de Bordo: Registro simples de humor e eventos do dia.

Estado Emocional Instantâneo: Botões rápidos para expressar dor, medo ou necessidade de ajuda.

Módulo Educador: * Acompanhamento Diário: Registro de interações sociais e episódios de desconforto em sala.

Relatório Semanal: Avaliação de evolução pedagógica e adaptações de rotina.

3. Inteligência Artificial (Core)
Análise Preditiva: Processamento em Python utilizando modelos de Machine Learning (Random Forest/XGBoost).

Fusão de Dados: A IA cruza os picos de frequência cardíaca com as sensibilidades relatadas pelos pais e o humor descrito pelo aluno.

Detecção de Gatilhos: Identificação de padrões que antecedem uma crise (ex: sons altos + aumento de batimentos).

4. Aplicativo Mobile (Flutter)
Interface Adaptada: Layout limpo e intuitivo, pensado para a comunicação com alunos autistas (uso de pictogramas e cores suaves).

Alertas em Tempo Real: Notificações para o professor quando a IA detecta uma probabilidade alta de crise iminente.

Dashboard de Evolução: Gráficos para visualização do bem-estar do aluno ao longo do tempo.

🏗️ Arquitetura do Sistema
Hardware (Arduino): Captura os sinais brutos.

Mobile (Flutter): Interface de entrada para os questionários e exibição de alertas.

Backend (Spring Boot): Orquestrador que armazena os dados no banco de dados e comunica-se com o motor de IA.

IA (Python/Flask): Recebe os dados, realiza a predição e retorna o nível de risco.

🛠️ Tecnologias Utilizadas
Mobile: Flutter (Dart)

Backend: Java (Spring Boot)

Inteligência Artificial: Python (Pandas, Scikit-learn, Flask)

Hardware: Arduino C++, Sensor de Batimentos (Pulse Sensor), Acelerômetro (MPU6050)

Banco de Dados: PostgreSQL / MySQL

📈 Impacto Esperado
Proporcionar aos educadores uma ferramenta de intervenção precoce, permitindo que o aluno receba suporte antes que o desconforto se torne uma crise severa, promovendo um ambiente escolar mais seguro e acolhedor.

👥 Autores
João Pedro Cassiano de Brito
Virginia da Silva
Yasmin Tavares Noberto
