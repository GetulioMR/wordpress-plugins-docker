# Estrutura do Projeto

Este projeto utiliza Docker para facilitar a criação e teste de plugins WordPress. A estrutura do projeto é a seguinte:

## Arquivos e Pastas

- `docker-compose.yml`: Arquivo de configuração do Docker Compose que define os serviços necessários (MariaDB, WordPress e PHPMyAdmin).
- `.docker/`: Diretório que contém os volumes persistentes para os serviços Docker.
- `plugins/`: Diretório onde os plugins WordPress devem ser criados e armazenados.
- `.gitignore`: Arquivo que define os arquivos e diretórios a serem ignorados pelo Git.
- `README.md`: Arquivo de documentação do projeto.
- `LICENSE.md`: Arquivo de licença do projeto.

## Como Usar

1. Clone este repositório.
2. Crie seus plugins dentro do diretório `plugins`.
3. Inicie os serviços Docker com o comando:
   ```sh
   docker-compose up -d
    ```
4. Acesse o WordPress em `http://localhost:8000`.

## Licença
Este projeto é licenciado sob a licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.