# Venustas 🌸

O **Venustas** é uma solução completa e profissional para a gestão e agendamento de serviços em salões de estética. Desenvolvido para oferecer uma experiência fluida tanto para os profissionais como para os clientes, o sistema automatiza fluxos de trabalho, gere agendas de forma inteligente e centraliza o controle financeiro.

## 🚀 Tecnologias Utilizadas

O projeto utiliza uma stack moderna e escalável:

- **Frontend:** [Next.js](https://nextjs.org/) + [Tailwind CSS](https://tailwindcss.com/)
- **Backend:** [FastAPI](https://fastapi.tiangolo.com/) (Python)
- **Base de Dados:** [PostgreSQL](https://www.postgresql.org/) via [Supabase](https://supabase.com/)
- **Automação:** [n8n](https://n8n.io/) para notificações e integrações
- **Hospedagem:** Vercel e Render

## ✨ Funcionalidades Principais

- **Agenda Inteligente:** Visualização multi-profissional com sistema de prevenção de conflitos de horário.
- **Gestão de Clientes (CRM):** Histórico detalhado de procedimentos, preferências e dados de contacto.
- **Módulo Financeiro:** Gestão de comandas, fluxos de pagamento e relatórios de faturação.
- **Notificações Automáticas:** Lembretes de agendamento enviados via WhatsApp para reduzir a taxa de faltas.
- **Painel Administrativo:** Controlo de permissões e gestão de serviços/profissionais.

## 🛠️ Estrutura do Projeto

```text
📂 venustas-web  -> Interface do utilizador e dashboard
📂 venustas-api  -> Lógica de negócio e rotas da base de dados
📂 venustas-infra -> Scripts de migração e fluxos do n8n
