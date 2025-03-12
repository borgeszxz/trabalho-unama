## **📌 Sistema de Reserva para Eventos**
Um sistema onde organizadores podem cadastrar eventos e usuários podem se inscrever neles. Pode ser útil para palestras, workshops, shows, reuniões etc.

### **👨‍💻 Tecnologias**
- **Framework Back end:** Laravel
- **Back end:** PHP 
- **Frontend:** Javascript
- **Banco de Dados:** MySQL

---

## **🔗 API - Endpoints**

### **🔐 Autenticação (Usuários)**
1. `GET /user` → Obter dados do usuário logado
   
### **📅 Gestão de Eventos (somente organizadores)**
2. `GET /events` → Listar todos os eventos
3. `GET /events/{id}` → Detalhes de um evento específico

### **✅ Inscrição em Eventos**
4. `GET /user/events` → Lista de eventos que o usuário está participando
---
