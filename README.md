## **📌 Sistema de Reserva para Eventos**
Um sistema onde organizadores podem cadastrar eventos e usuários podem se inscrever neles. Pode ser útil para palestras, workshops, shows, reuniões etc.

### **👨‍💻 Tecnologias**
- **Backend API:** Laravel 
- **Frontend:** PHP
- **Banco de Dados:** MySQL

---

## **🔗 API - Endpoints**

### **🔐 Autenticação (Usuários)**
1. `POST /register` → Criar uma conta
2. `POST /login` → Fazer login e obter um token
3. `GET /user` → Obter dados do usuário logado
4. `PUT /user` → Atualizar perfil do usuário

### **📅 Gestão de Eventos (somente organizadores)**
5. `POST /events` → Criar evento (exige autenticação como organizador)
6. `GET /events` → Listar todos os eventos
7. `GET /events/{id}` → Detalhes de um evento específico
8. `PUT /events/{id}` → Atualizar evento (somente organizador do evento)
9. `DELETE /events/{id}` → Excluir evento (somente organizador do evento)

### **✅ Inscrição em Eventos**
10. `POST /events/{id}/register` → Usuário se inscreve no evento
11. `GET /user/events` → Lista de eventos que o usuário está participando
12. `DELETE /events/{id}/cancel` → Cancelar inscrição no evento

---
