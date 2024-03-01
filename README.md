# Escopo do Projeto Muda Fácil

## Desenvolvimento Backend

Responsável por toda a lógica do servidor, autenticação de usuários, e operações do banco de dados.

### Fellipe: Lógica de Negócios e APIs
- Desenvolver a lógica de negócios central do app.
- Implementar APIs RESTful para a comunicação entre frontend e backend.

### Rodrigo: Autenticação e Segurança
- Implementar sistema de autenticação para clientes e motoristas.
- Assegurar a segurança dos dados dos usuários.

## Desenvolvimento Frontend

Focado na criação de interfaces de usuário intuitivas e responsivas.

### Vinicius: Desenvolvimento de Interfaces
- Desenvolver todas as interfaces de usuário para o app.
- Garantir responsividade e uma boa experiência de usuário em dispositivos variados.

## Banco de Dados

Crucial para o desempenho, escalabilidade, e integridade dos dados do app.

### Fellipe e Rodrigo: Projeto e Implementação do Banco de Dados
- **Fellipe**: Design do banco de dados, incluindo esquemas e índices.
- **Rodrigo**: Implementação e configuração do banco de dados, foco em segurança e backups.

## Testes & QA (Qualidade de Software)

Essencial para garantir a estabilidade e usabilidade do app.

### Vinicius, Fellipe, e Rodrigo: Testes Compartilhados
- **Vinicius**: Testes de usabilidade e compatibilidade no frontend.
- **Fellipe e Rodrigo**: Testes automatizados e de integração para backend e banco de dados.

## Coordenação e Gerenciamento do Projeto

Como desenvolvedor chefe, você coordena a equipe, revisa trabalhos, e toma decisões técnicas chave.

- Garantir que todos na equipe estejam alinhados e cumpram com os prazos.
- Manter uma comunicação clara e eficiente dentro da equipe.

Este escopo foi ajustado para otimizar as habilidades de cada membro da equipe, promovendo uma colaboração eficaz e mantendo o projeto simples, conforme os requisitos.

---------------

# Documento de Levantamento de Requisitos - Muda Fácil

## 1. Introdução

Este documento define os requisitos para o desenvolvimento do aplicativo "Muda Fácil", que conecta clientes a motoristas para facilitar mudanças residenciais.

## 2. Objetivo

Simplificar e otimizar o processo de mudança, proporcionando uma plataforma intuitiva para contratar serviços de mudança.

## 3. Escopo do Projeto

Desenvolver um aplicativo móvel para usuários (clientes e motoristas) com funcionalidades específicas para cada grupo.

## 4. Requisitos de Usuário

### 4.1 Clientes

- **R4.1.1 Cadastro e Login**: Permitir cadastro e login usando e-mail e senha.
- **R4.1.2 Solicitação de Mudança**: Capacidade de solicitar serviços de mudança, incluindo detalhes específicos.
- **R4.1.3 Visualização de Ofertas**: Possibilidade de visualizar e selecionar ofertas de motoristas.
- **R4.1.4 Avaliações**: Avaliar o serviço após a mudança.

### 4.2 Motoristas

- **R4.2.1 Cadastro e Login**: Cadastro e login com detalhes do veículo e documentação.
- **R4.2.2 Recebimento de Solicitações**: Receber notificações de novas solicitações e aceitá-las.
- **R4.2.3 Gestão de Agendas**: Gerenciar agendas de mudanças.
- **R4.2.4 Avaliações**: Receber avaliações dos clientes.

## 5. Requisitos Funcionais

- **RF5.1 Sistema de Autenticação**: Sistema de autenticação seguro.
- **RF5.2 Gerenciamento de Solicitações**: Criar, visualizar, aceitar e gerenciar solicitações.
- **RF5.3 Sistema de Avaliação**: Permitir avaliações mútuas após a conclusão de uma mudança.
- **RF5.4 Notificações**: Notificações para motoristas e clientes sobre solicitações e atualizações.

## 6. Requisitos Não Funcionais

- **RNF6.1 Segurança**: Proteção e armazenamento seguro dos dados dos usuários.
- **RNF6.2 Usabilidade**: Interface intuitiva e fácil de usar.
- **RNF6.3 Desempenho**: Respostas rápidas e tempos de carregamento mínimos.
- **RNF6.4 Escalabilidade**: Capacidade de escalar para suportar mais usuários.

## 7. Restrições

- Conclusão em 4 meses.
- Equipe: Fellipe, Vinicius, e Rodrigo, liderada pelo desenvolvedor chefe.

## 8. Anexos

- Diagramas de fluxo de usuário.
- Wireframes e mockups das interfaces.
- Especificações técnicas para desenvolvimento.

Este documento serve como uma base inicial para o desenvolvimento do projeto "Muda Fácil". É importante revisar e atualizar este documento conforme o projeto evolui, garantindo que todos os requisitos sejam atendidos de forma eficaz.

-------

# Estrutura Analítica do Projeto (EAP) - Muda Fácil

## 1. Início do Projeto
- 1.1 Definição do escopo
- 1.2 Estabelecimento de objetivos
- 1.3 Formação da equipe
- 1.4 Planejamento inicial

## 2. Desenvolvimento do Aplicativo
### 2.1 Requisitos
- 2.1.1 Levantamento de requisitos
- 2.1.2 Análise de requisitos
- 2.1.3 Documentação de requisitos

### 2.2 Design
- 2.2.1 Design da interface do usuário
- 2.2.2 Arquitetura do sistema
- 2.2.3 Modelagem de dados

### 2.3 Implementação
#### 2.3.1 Desenvolvimento Backend
- 2.3.1.1 Autenticação
- 2.3.1.2 Lógica de negócios
- 2.3.1.3 API e integração

#### 2.3.2 Desenvolvimento Frontend
- 2.3.2.1 Interfaces do cliente
- 2.3.2.2 Interfaces do motorista

#### 2.3.3 Configuração do Banco de Dados
- 2.3.3.1 Design do banco de dados
- 2.3.3.2 Implementação e segurança do banco de dados

### 2.4 Testes
- 2.4.1 Planejamento de testes
- 2.4.2 Execução de testes (automatizados e manuais)
- 2.4.3 Correção de bugs
- 2.4.4 Testes de aceitação do usuário

## 3. Lançamento
- 3.1 Preparação para o lançamento
- 3.2 Lançamento Beta
- 3.3 Coleta e análise de feedback
- 3.4 Lançamento Oficial

## 4. Pós-lançamento
- 4.1 Suporte e manutenção
- 4.2 Atualizações e melhorias
- 4.3 Avaliação de desempenho do app

Esta EAP é um guia de alto nível para o desenvolvimento do projeto "Muda Fácil". Cada entrega pode ser decomposta ainda mais conforme necessário.
