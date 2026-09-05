FABIOLA & JUNIOR — LISTA ONLINE
1. Execute supabase_setup.sql no SQL Editor.
2. Em Supabase > Authentication > Users, crie o usuário dos noivos.
3. Publique index.html e admin.html.
O frontend usa a Publishable Key, não uma secret/service_role key. O site usa Supabase Realtime e uma função SQL com UPDATE condicional para impedir reservas duplicadas.