# Alura Space

Projeto desenvolvido durante os estudos de Django na Alura.

## Tecnologias

- Python
- Django
- SQLite

## Passo-a-passo para executar o projeto

### 1. Clone o repositório

    git clone https://github.com/KueRocha/alura-space.git
    cd alura-space

### 2. Crie e ative o ambiente virtual

**Windows (PowerShell):**

    python -m venv venv
    .\venv\Scripts\Activate.ps1

**Linux/macOS:**

    python -m venv venv
    source venv/bin/activate

### 3. Instale o Django e as dependências do projeto

    pip install -r requirements.txt

### 4. Execute as migrações

    python manage.py migrate

### 5. Crie um superusuário

    python manage.py createsuperuser

### 6. Inicie o servidor

    python manage.py runserver


## Para acessar o django admin use http://127.0.0.1:8000/admin.

Acesse http://127.0.0.1:8000/ para visualizar o projeto.

<img width="1827" height="919" alt="image" src="https://github.com/user-attachments/assets/a4efb450-8004-4f28-a158-64fbe3432234" />

