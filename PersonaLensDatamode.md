# 📊 PersonaSense Data Model

A structured schema for a tool that accepts natural language queries and delivers persona-based sentiment insights using data from news, social, and public sources.

---

## 🧑‍💻 User

Stores system user information.

```plaintext
- user_id (PK)
- name
- email
- organization
- role (e.g., analyst, researcher)
- preferences (JSON)
- created_at
- updated_at
