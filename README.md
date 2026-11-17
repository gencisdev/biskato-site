# Biskato — Site informativo

Página oficial do **Biskato** (marketplace de serviços em Luanda).
Site estático, num único `index.html` — sem build, sem dependências.

## Conteúdo

- Hero com ilustração de profissionais a trabalhar (SVG)
- Serviços populares ilustrados (pedreiro, electricista, canalizador, costureira, pintor, carpinteiro, limpeza, mecânico)
- O problema · Como funciona · Clientes e profissionais · Planos · FAQ
- CTA de lançamento ("A app chega em breve") com contacto **orgbiskato@gmail.com**

## Publicar na Vercel

1. Criar conta em [vercel.com](https://vercel.com) (pode usar "Sign up with GitHub").
2. No dashboard: **Add New → Project → Import** o repositório `biskato-site`.
3. Framework Preset: **Other** (estático). Não precisa de build.
4. **Deploy** — fica no ar em `https://biskato-site.vercel.app` (ou domínio próprio em Settings → Domains).

Alternativa por CLI:

```bash
npm i -g vercel
vercel --prod
```

## Estrutura

```
index.html    # site completo (HTML + CSS + SVG inline)
icon.svg      # favicon (logo Biskato)
vercel.json   # configuração de deploy (headers de segurança, cleanUrls)
```
