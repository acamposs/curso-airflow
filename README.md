# Curso de Apache Airflow

## Introdução

Este repositório foi criado para armazenar os conhecimentos e práticas desenvolvidos ao longo do curso de Apache Airflow. O aprendizado foi realizado através de dois cursos:
- [**Curso Apache Airflow**](https://www.alura.com.br/formacao-apache-airflow) pela plataforma **Alura**, instruído por [Milena Gená](https://cursos.alura.com.br/user/millenagena), [Igor Nascimento](https://cursos.alura.com.br/user/igor-nascimento-flipe), [Daniel Siqueira](https://cursos.alura.com.br/user/danpsiqueira), [Bruno Rafaell](https://cursos.alura.com.br/user/bruno-matos0), Marcelo Cruz, Paulo Calanca, e Rafael Bottega.
- [**Curso Apache Airflow Tutorial**](https://youtube.com/playlist?list=PLLNidqMOzeD5yXv9lDtBM-VJ5-1F-ZdXI&si=1p0aVwONBj4eYKJ_) pelo canal **YouTube**, instruído por [André Ricardo](https://www.andrericardo.com.br/curriculo/meu-curriculo/).

## Checklist de Conhecimentos Adquiridos

- Introdução ao Apache Airflow 
- Construção de Pipeline de Extração e Transformação de Dados
- Configuração de Executores do Airflow
- Utilização de Python Operator
- Implementação do Latest Only Operator
- Configuração de Logging, Debugging e Monitoramento

## Como Rodar a Aplicação

### Requisitos

- **Python** 3.7+
- **Docker** 
- **Docker Compose**


### Passo a Passo
1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/curso-airflow.git
    cd curso-airflow
    ```

2. Suba os containers do Docker:
    ```bash
    docker-compose up -d
    ```

3. Acesse a interface do Airflow no seu navegador:
    ```
    http://localhost:8080
    ```

4. Use as credenciais padrão para login:
    - Usuário: `airflow`
    - Senha: `airflow`


