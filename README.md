# Flutter Experience Lab Clinicas

Projeto da Academia do Flutter do "Flutter Experience", ministrado pelo Rodrigo Rahman, reconhecido como expert Flutter e Dart pela Google (GDE).
Este projeto aborda a criação de um sistema abrangente para um laboratório clínico, com suporte multiplataforma através de versões web, desktop e mobile. A estrutura do projeto é fundamentada na Arquitetura MVVM (Model-View-ViewModel), proporcionando uma organização modular e escalável, facilitando a manutenção e expansão.Principais Ferramentas Utilizadas:
- Signal: é utilizada para gerenciar a comunicação entre diferentes componentes do aplicativo, gerenciamento de estado.
- DIO: biblioteca utilizada para manipular dados da API que são realizadas através de requisições HTTP, ela suporta 
  interceptadores e têm diversas funcionalidades. 
- Json_Rest_Server - é implementado para simular o backend.
- WebSockets: habilita a comunicação bidirecional, como mensagens em tempo real, permitindo a troca dinâmica de informações 
  entre o frontend e o backend.
- Flutter_Get - é adotada para gerenciar a injeção de dependências.

**- Projetos Interligados:**
- fe_lab_clinicas_api - arquivo datebase.json.
- fe_lab_clinicas_core - arquivos restClient interceptors, local storage, e theme, utilizados em todos os projetos.
- fe_lab_clinicas_self_service - plataforma Mobile. 
- fe_lab_clinicas_adm - plataforma Desktop.
- fe_lab_clinicas_painel - plataforma Web.


## Projeto Self-Service - Plataforma Mobile

A parte mobile deste projeto é especialmente projetada para otimizar o processo de cadastro de pacientes, oferecendo uma abordagem inovadora e intuitiva por meio do uso de tablets. Essa funcionalidade permite que os próprios pacientes realizem seus cadastros, proporcionando maior autonomia e agilidade no fluxo de atendimento. É composto por:

- Tela de login
- Tela para iniciar terminal.
- Tela para digitar o nome do paciente.
- Tela para digitar o cpf do paciente.
- Tela de cadastro.
- Tela para adicionar documentos.
- Tela que indica a senha que será chamada no painel e finalização do cadastro.


