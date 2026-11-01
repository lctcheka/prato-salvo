# 🥗 Prato Salvo

O **Prato Salvo** é uma plataforma web desenvolvida para conectar fornecedores de alimentos, clientes e estafetas/entregadores, visando a redução do desperdício de alimentos e a facilitação do acesso a refeições.

A aplicação conta com uma arquitetura modular por perfis de acesso, oferecendo painéis dedicados e personalizados para cada tipo de utilizador do sistema.

---

## 🚀 Funcionalidades e Módulos

- ** Landing Page:** Apresentação da plataforma e navegação inicial.
- ** Painel do Cliente:** Interface interativa para visualização e solicitação de pratos/refeições.
- ** Painel do Fornecedor:** Gestão de inventário e disponibilização de alimentos.
- ** Módulo de Entrega:** Gestão de rotas e acompanhamento de entregas.
- ** Painel Administrativo:** Controlo global do sistema e monitorização de dados.
- ** Módulo de Cadastro:** Fluxo de registo de novos utilizadores.

---

## 🛠️ Tecnologias Utilizadas

- **Front-end:** HTML5, CSS3 (Design Responsivo), JavaScript (ES6+)
- **Arquitetura:** Componentização modular por páginas e scripts de ponte (`*-bridge.js`) para integração de dados
- **Ferramentas de Desenvolvimento:** VS Code, Live Server

---

## 📂 Estrutura do Projeto

```text
prato-salvo/
├── index.html
├── assets/
│   └── shell/ (Estilos e scripts globais da aplicação)
└── pages/
    ├── admin/       # Gestão e administração do sistema
    ├── cadastro/    # Formulários de registo
    ├── cliente/     # Painel do cliente final
    ├── entrega/     # Módulo para estafetas/entregadores
    ├── fornecedor/  # Painel para fornecedores de refeições
    └── landing/     # Página principal de apresentação
