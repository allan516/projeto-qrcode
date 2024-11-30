# Projeto QR Code

Este projeto combina dois utilitários em um só: a geração de QR Codes diretamente no terminal e a criação de senhas personalizadas. Ele utiliza os pacotes npm `prompt`, `chalk` e `qrcode-terminal` para interatividade, estilização e geração de QR Codes, além de utilizar variáveis de ambiente para configurar a geração de senhas.

## Recursos

### QR Code

- Solicita ao usuário um texto ou URL.
- Gera e exibe um QR Code diretamente no terminal.

### Password

- Cria senhas personalizadas com base nas configurações definidas no arquivo `.env`.
- Opções para incluir caracteres especiais, números, letras maiúsculas e minúsculas.
- Configuração do tamanho da senha.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução do JavaScript.
- **prompt**: Para entrada de dados interativa no terminal.
- **chalk**: Para estilização do texto no terminal.
- **qrcode-terminal**: Para geração de QR Codes no terminal.
- **dotenv**: Para gerenciar variáveis de ambiente.
