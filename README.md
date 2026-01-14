# 🧩  EduCare: Inteligência Artificial na Inclusão Escolar

> **Projeto de Trabalho de Conclusão de Curso (TCC)** > Um ecossistema inteligente voltado à detecção precoce de crises sensoriais e emocionais em alunos autistas, IA e monitoramento colaborativo.

---

## 🎯 Sobre o Projeto
Este projeto visa auxiliar a inclusão escolar de alunos com **Transtorno do Espectro Autista (TEA)**. O objetivo principal é desenvolver um ecossistema capaz de detectar sinais precoces de crises através da fusão de dados fisiológicos e comportamentais.

A solução integra **Inteligência Artificial (IA)** e um **Aplicativo Móvel** para criar uma rede de apoio em tempo real entre alunos, responsáveis e educadores.

---

## 🚀 Funcionalidades Principais

### ⌚ Pulseira Inteligente (IoT)
Protótipo baseado em **Arduino** para coleta em tempo real:
* **Frequência Cardíaca:** Monitoramento de picos que indicam ansiedade ou estresse.
* **Acelerômetro:** Identificação de comportamentos motores repetitivos (*stimming*) ou agitação física.
* **Conectividade:** Transmissão contínua via Bluetooth/Wi-Fi para a API central.

### 📊 Coleta de Dados Multidimensionais
Questionários estratégicos que fornecem contexto semântico à IA:
* **Módulo Responsável:** Cadastro do perfil sensorial, histórico e rotina.
* **Módulo Aluno:** * *Diário de Bordo:* Registro simplificado de humor e eventos.
    * *Estado Emocional:* Botões de acesso rápido para expressar dor, medo ou pedido de ajuda.
* **Módulo Educador:** * *Acompanhamento Diário:* Registro de interações e episódios de desconforto.
    * *Relatório Semanal:* Evolução pedagógica e adaptações de rotina.

### 🧠 Inteligência Artificial (Core)
* **Análise Preditiva:** Processamento em Python utilizando modelos como *Random Forest* ou *XGBoost*.
* **Fusão de Dados:** O modelo cruza biometria (batimentos) com gatilhos externos (sensibilidades relatadas) e o estado emocional autodeclarado.
* **Detecção de Gatilhos:** Identificação de padrões que antecedem crises (ex: correlação entre ruídos e taquicardia).

### 📱 Aplicativo Mobile (Flutter)
* **Interface Adaptada:** Design limpo com pictogramas e cores suaves, focado na acessibilidade cognitiva.
* **Alertas Predict:** Notificações instantâneas para professores sobre riscos iminentes de crise.
* **Dashboards:** Visualização clara da evolução do bem-estar do aluno.

---

## 🏗️ Arquitetura do Sistema

| Camada | Tecnologia | Responsabilidade |
| :--- | :--- | :--- |
| **Hardware** | Arduino C++ | Captura de sinais brutos dos sensores |
| **Mobile** | Flutter (Dart) | Interface do usuário e entrada de dados |
| **Backend** | Java (Spring Boot) | Orquestração, persistência e regras de negócio |
| **IA Engine** | Python (Flask/FastAPI) | Processamento de Machine Learning e predições |

---

## 🛠️ Tecnologias Utilizadas

* **Linguagens:** `Java`, `Python`, `Dart`, `C++`
* **IA:** `Pandas`, `Scikit-learn`, `XGBoost`
* **Sensores:** `Pulse Sensor`, `MPU6050 (Acelerômetro)`
* **Banco de Dados:** `PostgreSQL` / `MySQL`

---

## 📈 Impacto Esperado
Proporcionar aos educadores uma ferramenta de **intervenção precoce**, permitindo que o aluno receba suporte antes que o desconforto se torne uma crise severa, promovendo um ambiente escolar mais seguro, acolhedor e neurodivergente.

---

## 👥 Autores
* **João Pedro Cassiano de Brito**
* **Virginia da Silva**
* **Yasmin Tavares Noberto**

---
