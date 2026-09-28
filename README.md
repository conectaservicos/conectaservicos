# Conecta Serviços

1. Execute `supabase-schema.sql` no SQL Editor.
2. Preencha `SUPABASE_URL` e `SUPABASE_ANON_KEY` no `index.html`.
3. Crie o primeiro usuário e execute:
```sql
update public.profiles set role='admin',status='active' where email='SEU_EMAIL_ADMIN@EXEMPLO.COM';
```
4. Publique os arquivos no GitHub Pages.
5. Configure Site URL e Redirect URLs no Supabase Auth.
6. Instale pelo Chrome/Edge usando “Instalar aplicativo”.
