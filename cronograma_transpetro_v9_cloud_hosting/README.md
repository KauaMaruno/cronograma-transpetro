# Cronograma Transpetro 2026 — V9 Cloud

Versão preparada para hospedagem estática com sincronização Supabase.

## O que já está configurado
- Supabase Auth com e-mail e senha
- Sincronização do progresso para `public.study_state`
- localStorage continua como cache/offline
- sincronização PC ↔ celular quando a mesma conta é usada
- indicação visual de status da nuvem
- detecção simples de conflito entre dados locais e nuvem
- PWA/service worker

## Importante
O arquivo usa a chave pública (publishable/anon) do projeto. Nunca coloque a `service_role` no navegador.

Antes de publicar, a tabela `study_state` e as políticas RLS precisam existir no Supabase.

Para hospedar, publique o conteúdo desta pasta em GitHub Pages, Netlify ou Cloudflare Pages.
