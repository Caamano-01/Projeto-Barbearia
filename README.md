# 📘 BarberTime – Sistema de Agendamento para Barbearia

**BarberTime** é um sistema completo para gerenciamento de barbearias, permitindo que clientes agendem serviços e que barbeiros/admins gerenciem a agenda, profissionais e serviços.  

O projeto foi desenvolvido com **HTML, CSS, JavaScript no front-end** e **PHP + MySQL no back-end**.  

---

## ✂️ Funcionalidades

### Área do Cliente
- Cadastro e login de usuários  
- Edição de perfil  
- Lista de serviços (nome, descrição, preço, duração)  
- Lista de profissionais (foto, especialidade, contato)  
- Agendamento de serviços (escolha de serviço, profissional, data e hora)  
- Histórico de agendamentos  
- Localização da barbearia  

### Área Administrativa
- Login de administradores  
- CRUD de serviços  
- CRUD de profissionais  
- Gestão de agenda de barbeiros  
- Bloqueio de horários (feriados, folgas, etc.)  
- Dashboard resumido do faturamento  

---

## 🛠 Tecnologias Utilizadas

**Frontend**: HTML5, CSS3, JavaScript (Fetch API)  
**Backend**: PHP 8+ com PDO  
**Banco de Dados**: MySQL

---

## 🗂 Estrutura do Projeto
barbearia/
├── backend/
│ ├── config/ # Conexão com o banco
│ ├── api/ # Arquivos PHP para CRUD e autenticação
│ └── admin/ # Painel administrativo
├── public/ # Frontend
│ ├── assets/ # CSS e JS
│ ├── partials/ # Header e footer
│ ├── *.html # Páginas HTML do cliente
├── sql/
│ └── barbearia.sql # Estrutura do banco de dados
