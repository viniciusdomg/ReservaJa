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

## RFs
[site_de_reserva_requisitos_0.5.pdf](https://github.com/user-attachments/files/19504261/site_de_reserva_requisitos_0.5.pdf)


## 📌 Diagramas
### 📌 Caso de Uso:
![image](https://github.com/user-attachments/assets/b3ef415f-cd30-4cc7-9e4c-32278e1d5723)


### 📌 Diagrama de Classes:
![Class Diagram0](https://github.com/user-attachments/assets/40498b28-14c9-43a4-b6b0-8aa8677b5dac)


---

## ⚙️ Instalação e Configuração

```sh
# Clone o repositório
git clone https://github.com/seu-usuario/ReservaJa.git
cd ReservaJa

# Crie um ambiente virtual e ative
python -m venv venv
venv\Scripts\Activate  # No Windows: venv\Scripts\activate

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

## Templetes
https://rocket-django-pro.onrender.com/crud/products/
https://adminlte-django.appseed-srv1.com/

https://www.figma.com/design/R4NBBDO4TzDulzqnK1Qn2E/pa1?node-id=0-1&p=f&t=zJChOC4m0C44xz4B-0
