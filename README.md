# Central de Cobrança – Galo Varginha

App web instalável (PWA) com login para acompanhar a rotina de cobrança da Academia de Futebol do Galo – Varginha (Finangest).

- Dados: Supabase (projeto `galo-cobranca`), lidos só depois do login. Regras de acesso (RLS) no banco.
- Perfis: **Administrador** (tudo) e **Operador** (somente consulta).
- Este repositório contém apenas o código da página. Nenhum dado, cookie ou senha fica aqui.
- A chave que aparece em `index.html` é a chave pública (publishable) do Supabase, feita para ficar no navegador; sozinha ela não lê nada sem login.
