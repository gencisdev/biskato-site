<div align="center">

<img src="icon.svg" width="84" alt="Biskato" />

# Biskato — site

**Página pública do Biskato**, o marketplace de serviços de Luanda.

[![Site](https://img.shields.io/badge/site-no%20ar-C8102E?style=flat-square&logo=vercel&logoColor=fff)](https://biskatoao.vercel.app)
[![HTML](https://img.shields.io/badge/HTML%20%C3%BAnico-sem%20build-E34F26?style=flat-square&logo=html5&logoColor=fff)](index.html)
[![Analytics](https://img.shields.io/badge/Vercel%20Web%20Analytics-activo-111?style=flat-square&logo=vercel&logoColor=fff)](https://vercel.com/analytics)
[![Licença](https://img.shields.io/badge/licen%C3%A7a-propriet%C3%A1ria-111?style=flat-square)](../Biskatoao-App/blob/main/LICENSE)

[🌐 biskatoao.vercel.app](https://biskatoao.vercel.app) · [💻 Código da app](https://github.com/gencisdev/Biskatoao-App)

</div>

---

## O que é

Uma página estática, num único `index.html` — sem build, sem dependências, sem
*frameworks*. Apresenta o Biskato a clientes e profissionais de Luanda: o problema,
como funciona, serviços populares, planos de visibilidade, perguntas frequentes e
contactos.

## Capturas da app

<table>
  <tr>
    <td align="center"><img src="https://raw.githubusercontent.com/gencisdev/Biskatoao-App/main/docs/screenshots/04-explorar.png" width="200" alt="Explorar" /><br/><sub><b>Explorar</b></sub></td>
    <td align="center"><img src="https://raw.githubusercontent.com/gencisdev/Biskatoao-App/main/docs/screenshots/05-mensagens.png" width="200" alt="Mensagens" /><br/><sub><b>Mensagens</b></sub></td>
    <td align="center"><img src="https://raw.githubusercontent.com/gencisdev/Biskatoao-App/main/docs/screenshots/06-planos.png" width="200" alt="Planos" /><br/><sub><b>Planos</b></sub></td>
  </tr>
</table>

## Conteúdo da página

- Hero com ilustração de profissionais a trabalhar (SVG inline)
- Serviços populares ilustrados: pedreiro, electricista, canalizador, costureira,
  pintor, carpinteiro, limpeza e mecânico
- Secções: o problema · como funciona · para clientes e profissionais · planos · FAQ
- Chamada para acção com contacto **orgbiskato@gmail.com**
- Acessibilidade: navegação por teclado, contraste e texto alternativo nas ilustrações

## Publicar na Vercel

1. Cria conta em [vercel.com](https://vercel.com) (podes usar «Sign up with GitHub»).
2. **Add New → Project → Import** o repositório `biskato-site`.
3. Framework Preset: **Other** (estático, sem build).
4. **Deploy** — fica no ar em `https://biskatoao.vercel.app` (domínio próprio em
   *Settings → Domains*).

Pela CLI:

```bash
npm i -g vercel
vercel --prod
```

## Estrutura

```
index.html    # site completo (HTML + CSS + SVG inline)
icon.svg      # favicon / logo Biskato
vercel.json   # deploy (headers de segurança, cleanUrls)
```

## Visitas

O site usa **Vercel Web Analytics** (plano Hobby): contagem de visitantes e páginas
vistas sem cookies nem identificação pessoal. Os números ficam no dashboard do
projecto, em *Analytics*.

## Licença

Proprietária — todos os direitos reservados. Ver a
[licença do projecto](https://github.com/gencisdev/Biskatoao-App/blob/main/LICENSE).
Contacto: **orgbiskato@gmail.com**

---

<div align="center"><sub>© 2026 TheBoyz Dev Org · Feito em Luanda</sub></div>
