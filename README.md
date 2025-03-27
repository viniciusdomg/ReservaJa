# ReservaJa

ReservaJa é um sistema web desenvolvido em **Django** para facilitar o agendamento de quadras esportivas. O projeto permite que usuários realizem reservas, consultem disponibilidades e administrem agendamentos de forma simples e intuitiva.

## 🛠 Tecnologias Utilizadas
- **Backend:** Django, Django REST Framework
- **Banco de Dados:** Postgress
- **Frontend:** HTML, CSS, JavaScript
- **Autenticação:** Django Authentication

## 🚀 Funcionalidades
- ✅ Cadastro e login de usuários  
- ✅ Agendamento de quadras  
- ✅ Consulta de horários disponíveis  
- ✅ Administração de reservas  
- ✅ Cancelamento de reservas  
- ✅ Painel administrativo para gestão dos agendamentos  

## 📌 Diagramas
### 📌 Caso de Uso:
![Diagrama de Caso de Uso](https://github.com/user-attachments/assets/eeeebbc8-3d6a-445c-b973-f28980c3ed4b)

### 📌 Diagrama de Classes:
![Diagrama de Classes](https://github.com/user-attachments/assets/eeeebbc8-3d6a-445c-b973-f28980c3ed4b)

---

## ⚙️ Instalação e Configuração

```sh
# Clone o repositório
git clone https://github.com/seu-usuario/ReservaJa.git
cd ReservaJa

# Crie um ambiente virtual e ative
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

# Aplique as migrações do banco de dados
python manage.py migrate

# Crie um superusuário para acessar o painel administrativo
python manage.py createsuperuser

# Inicie o servidor local
python manage.py runserver

# Acesse a aplicação pelo navegador:
# http://127.0.0.1:8000
