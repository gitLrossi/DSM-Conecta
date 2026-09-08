# DSM Conecta

Projeto desenvolvido na disciplina de Laboratório de Desenvolvimento de Software Multiplataforma da FATEC Zona Sul.

O DSM Conecta é uma aplicação voltada para a divulgação do curso de Desenvolvimento de Software Multiplataforma. A ideia é apresentar o curso, projetos dos alunos, eventos e outras informações para estudantes do ensino médio e pessoas interessadas na área de tecnologia.

Além da aplicação, o projeto trabalha com coleta e análise de dados em tempo real para acompanhar as interações dos usuários durante as ações de divulgação.

## Sobre o projeto

O sistema contará com:

* Informações sobre o curso e a matriz curricular;
* Projetos desenvolvidos pelos alunos;
* Depoimentos de estudantes e egressos;
* Agenda de eventos;
* Questionário de afinidade com a área de tecnologia;
* Registro de presença em eventos;
* Coleta de dados de interação;
* Painel com informações e métricas;
* Processamento de dados em tempo real.

## Tecnologias

### Aplicação

* Flutter
* Dart

### Back-end

* Python
* FastAPI
* WebSocket

### Banco de dados

* PostgreSQL

### Mensageria

* MQTT
* Eclipse Mosquitto

### Infraestrutura

* Docker
* Docker Compose

### Testes e versionamento

* pytest
* Git
* GitHub Actions

## Arquitetura

O projeto utiliza uma arquitetura distribuída baseada em eventos.

De forma geral, o funcionamento será:

```text
Aplicação
    ↓
MQTT / Mosquitto
    ↓
Serviço de ingestão
    ↓
Processamento dos dados
    ↓
PostgreSQL
    ↓
Painéis e métricas
```

A comunicação entre os componentes será feita principalmente por meio do protocolo MQTT.

## Estrutura do projeto

```text
DSM-Conecta/
├── Backend/
├── Frontend/
└── README.md
```

A estrutura será atualizada conforme o desenvolvimento do projeto.

## Como executar

### Requisitos

Para executar o projeto, será necessário ter instalado:

* Git
* Docker
* Docker Compose
* Flutter
* Python

### Clonar o repositório

```bash
git clone https://github.com/gitLrossi/DSM-Conecta.git
cd DSM-Conecta
```

### Executar

As instruções de execução serão atualizadas conforme os serviços forem configurados.

## Equipe

* Daniela Pereira Bosco
* Emanuelly Araújo de Jesus
* Lucas Rossi de Oliveira
* Vitória Alejandra Bandeira dos Santos
* Welber Eugenio dos Santos Junior

## Instituição

**FATEC Zona Sul**
Curso Superior de Tecnologia em Desenvolvimento de Software Multiplataforma

**Disciplina:** Laboratório de Desenvolvimento de Software Multiplataforma
**Professor:** Prof. Dr. Winston Aparecido Andrade
**Semestre:** 2026/2

## Status

🚧 Projeto em desenvolvimento.

