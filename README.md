# 📒 Agenda - Gerenciador de Contatos em Django  

## 📌 Sobre o Projeto  
O **Agenda** é uma aplicação web desenvolvida em **Django** para gerenciamento de contatos.  
Ela permite que o usuário **registre-se, faça login, cadastre, edite, visualize e exclua contatos**, além de atualizar seu próprio perfil.  

O projeto foi construído com foco em **simplicidade, usabilidade e organização** dos dados pessoais.  

---

## 🚀 Funcionalidades  

✅ Sistema de autenticação (Login, Registro, Logout)  
✅ Cadastro e gerenciamento de usuários  
✅ Perfil do usuário com atualização de dados  
✅ CRUD completo de contatos:  
- Criar novo contato  
- Listar contatos cadastrados  
- Atualizar contato existente  
- Excluir contato  
✅ Upload de imagem do contato  
✅ Pesquisa de contatos  
✅ Mensagens de sucesso e feedback ao usuário  

---

## 📷 Demonstração  

### 🔐 Login  
<img width="973" height="617" alt="image" src="https://github.com/user-attachments/assets/8282b156-5b8b-4379-ad84-f1f9ae1d898e" />


### 📝 Registro  
<img width="643" height="763" alt="image" src="https://github.com/user-attachments/assets/b05678df-95fe-48b7-afbd-249710b35903" />


### 📑 Lista de Contatos  
<img width="922" height="743" alt="image" src="https://github.com/user-attachments/assets/0b552984-5ce2-4e0c-8299-057e3fc6e245" />

### 👤 Perfil do Usuário  
<img width="877" height="742" alt="image" src="https://github.com/user-attachments/assets/b1f130d5-5672-4c81-a4d0-fde9d628f2b7" />


### 📌 Cadastro de Contato  
<img width="720" height="740" alt="image" src="https://github.com/user-attachments/assets/4482afe4-be3d-4bae-9fb6-a4ce5b517e2b" />


### 🔎 Visualização de Contato  
<img width="842" height="729" alt="image" src="https://github.com/user-attachments/assets/e4ea2ccd-896b-4df1-b791-e3271cdea545" />


---

## 🛠️ Tecnologias Utilizadas  

- **Backend:** [Django](https://www.djangoproject.com/)  
- **Frontend:** HTML5, CSS3, Bootstrap  
- **Banco de Dados:** SQLite (padrão Django, pode ser substituído por PostgreSQL/MySQL)  
- **Autenticação:** Sistema de usuários do Django  
- **Armazenamento de imagens:** Media upload do Django  

---
## 📂 Estrutura do Projeto 
```bash
agenda/
│── core/                # Configuração principal do Django
│── accounts/            # App de autenticação e gerenciamento de usuários
│── contacts/            # App de contatos (CRUD)
│── templates/           # Templates HTML
│── static/              # Arquivos estáticos (CSS, JS, imagens)
│── media/               # Upload de fotos de contatos
│── manage.py
│── requirements.txt
│── README.md
```
