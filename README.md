# WEB Flask App

Este é um projeto simples utilizando o Flask para criar um site que lê o conteúdo de um arquivo `nomes.txt` e exibe os nomes em uma página web. A página é atualizada automaticamente a cada 30 segundos. A aplicação é configurada para tratar erros como arquivo não encontrado ou arquivo vazio.

## Funcionalidades

- Leitura de um arquivo `nomes.txt` que contém uma lista de nomes.
- Exibição de uma lista de nomes em uma página web.
- Atualização automática da página a cada 30 segundos.
- Tratamento de erros para quando o arquivo `nomes.txt` não existir ou estiver vazio.

## Requisitos

- Python 3.7 ou superior
- Flask

## Instalação

1. Clone o repositório:
   ```
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   cd SEU_REPOSITORIO
   ```
2. Crie e ative um ambiente virtual:
- No Windows:
```
python -m venv .venv
.venv\Scripts\activate
```
- No Linux/Mac:
```
Copiar código
python3 -m venv .venv
source .venv/bin/activate
```

3. Instale as dependências do projeto:
````pip install -r requirements.txt````

4. Crie um arquivo ```nomes.txt``` na raiz do projeto e adicione uma lista de nomes, um nome por linha.

## Executando o Projeto
Com o ambiente virtual ativado, execute o aplicativo Flask:

```python app.py```

Abra o navegador e vá para ```http://127.0.0.1:5000/```. A página será atualizada automaticamente a cada 30 segundos.

## Estrutura do Projeto
```
.
├── .venv/                  # Ambiente virtual (ignorado pelo Git)
├── app.py                  # Código principal do Flask
├── nomes.txt               # Arquivo contendo os nomes
├── requirements.txt        # Lista de dependências
└── README.md               # Documentação do projeto
```

## Contribuição

1. Faça um fork do projeto.
2. Crie uma nova branch para suas alterações:
```git checkout -b feature/nova-funcionalidade```
3. Após realizar suas alterações, rode o Black para garantir a formatação do código:
```black .```
4. Envie suas alterações para o repositório:
```git push origin feature/nova-funcionalidade```
5. Crie um Pull Request na branch main.

## Regras de Contribuição
- Todas as mudanças devem passar pelo Black para garantir a padronização do código.
- Novas contribuições só serão aceitas via Pull Requests (PRs).
- A branch main está protegida e não pode receber commits diretos.
## Licença
Este projeto está licenciado sob a licença MIT
