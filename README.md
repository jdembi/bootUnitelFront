# bootUnitelFront
# Lyela Boot

O Lyela Boot é um sistema que integra uma API inteligente (API1) com uma API de serviços de operadora (API2) para fornecer funcionalidades como ativação de serviços, consulta de saldo e outros.

## Estrutura do Projeto

O projeto é composto por três principais componentes:

1. **Front-end:**
    - A interface com a qual os usuários interagem.
    - Responsável por enviar requisições para a API1.

2. **API Inteligente (API1):**
    - Recebe requisições do Front-end e processa algumas localmente.
    - Quando necessário, se comunica com a API de Serviços (API2) para ativação de serviços e outras funcionalidades.

3. **API de Serviços (API2):**
    - Responsável por ativar serviços da operadora, consulta de saldo e outros serviços.
    - Comunicada pela API1 quando funcionalidades específicas precisam ser executadas.

## Diagrama de Comunicação

Um diagrama de comunicação do sistema pode ser visualizado da seguinte maneira:

## Configuração e Uso

### Pré-requisitos
- Node.js e NPM instalados.
- Configurações de autenticação para a API de Serviços (API2).

### Instalação
1. Clone o repositório.
2. Instale as dependências com `npm install`.

### Configuração
1. Configure as credenciais de autenticação para a API de Serviços no arquivo `config.js`.

### Execução
1. Inicie o Front-end com `npm start`.
2. Acesse o sistema através do navegador.

## Contribuindo

Fique à vontade para abrir issues e pull requests para melhorias, correções de bugs ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a 
