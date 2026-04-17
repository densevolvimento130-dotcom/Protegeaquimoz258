# 🛡️ Protege Aqui — Site Oficial

Site completo de alta conversão para a loja de segurança **Protege Aqui**, desenvolvido em HTML, CSS e JavaScript puro. Pronto para lançar na internet sem necessidade de servidor backend.

---

## 📁 Estrutura do Projecto

```
protege-aqui/
└── index.html        ← Todo o site num único ficheiro
```

---

## 🚀 Como Lançar na Internet

### Opção 1 — Netlify (Gratuito e Recomendado)

1. Acesse [https://netlify.com](https://netlify.com)
2. Crie uma conta gratuita
3. Renomeie o ficheiro para `index.html`
4. Arraste e solte o ficheiro na área de deploy
5. O site fica online imediatamente
6. Ligue o seu domínio personalizado em: Site Settings → Domain Management

### Opção 2 — GitHub Pages (Gratuito)

1. Crie conta em [https://github.com](https://github.com)
2. Crie um repositório público chamado `protege-aqui`
3. Faça upload do ficheiro renomeado como `index.html`
4. Vá em: Settings → Pages → Source → main → Save
5. Site disponível em: `https://seuusuario.github.io/protege-aqui`

### Opção 3 — Hospedagem Paga (Mais Profissional)

1. Contrate um plano na **Hostinger** (~$3/mês) ou outro provedor
2. Acesse o **Gerenciador de Ficheiros** no painel cPanel
3. Faça upload do `index.html` para a pasta `public_html`
4. Registe o domínio `.co.mz` em [https://www.nic.co.mz](https://www.nic.co.mz)
5. Aponte os Nameservers do domínio para a hospedagem

---

## 🌐 Registar Domínio

| Tipo | Onde Registar | Custo Aproximado |
|------|--------------|------------------|
| `.co.mz` | [nic.co.mz](https://www.nic.co.mz) | ~600 MT/ano |
| `.com` | [namecheap.com](https://namecheap.com) | ~$12/ano |
| `.net` | [godaddy.com](https://godaddy.com) | ~$15/ano |

---

## ✨ Funcionalidades do Site

- ✅ Página Hero com CTA de alto impacto
- ✅ Barra de credibilidade e confiança
- ✅ Secção de produtos com cards dinâmicos
- ✅ 3 Pacotes (Básico, Profissional, Premium)
- ✅ Formulário de orçamento integrado com WhatsApp
- ✅ Botão WhatsApp flutuante e animado
- ✅ Secção "Porquê Nós" com 6 diferenciais
- ✅ Secção de contacto completa
- ✅ Footer profissional
- ✅ Design 100% responsivo (mobile + desktop)
- ✅ Painel Administrativo com login

---

## 👨‍💻 Painel Administrativo

Acesse clicando em **"⚙️ Área Admin"** no rodapé do site.

| Campo | Valor |
|-------|-------|
| Utilizador | `admin` |
| Senha | `protege2025` |

### O que pode fazer no painel:
- ➕ Adicionar novos produtos
- ✏️ Editar produtos existentes
- 🗑️ Remover produtos
- ➕ Adicionar novos pacotes
- ✏️ Editar e remover pacotes
- 💾 Dados guardados automaticamente no browser (localStorage)

> ⚠️ **Nota:** Os dados do painel admin ficam guardados no browser local. Se quiser que as alterações apareçam para todos os visitantes, é necessário integrar uma base de dados (ex: Firebase). Entre em contacto para essa actualização.

---

## 📱 Contactos Integrados no Site

| Canal | Valor |
|-------|-------|
| WhatsApp | +258 85 851 0026 |
| Email | desenvolvimento130@gmail.com |

---

## 🎨 Tecnologias Utilizadas

| Tecnologia | Uso |
|-----------|-----|
| HTML5 | Estrutura do site |
| CSS3 | Estilo, animações e responsividade |
| JavaScript (Vanilla) | Interactividade e painel admin |
| Google Fonts | Tipografia (Rajdhani + Nunito) |
| localStorage | Persistência de dados do admin |

---

## 🔧 Personalização Rápida

Para alterar informações do site, abra o ficheiro `index.html` num editor de texto (ex: VS Code, Notepad++) e procure as seguintes variáveis:

```javascript
// Número WhatsApp
const WA_NUM = '258858510026';

// Credenciais do Admin
const ADMIN_USER = 'admin';
const ADMIN_PASS = 'protege2025';
```

Para alterar cores, edite as variáveis CSS no início do ficheiro:

```css
:root {
  --red: #D92B2B;
  --orange: #FF6B00;
  --white: #FFFFFF;
}
```

---

## 📈 Dicas para Aumentar Conversões

1. **Activar o Google Analytics** — acompanhe visitas e comportamento
2. **Adicionar Pixel do Facebook** — para campanhas Meta Ads
3. **Criar um Google Meu Negócio** — apareça nas pesquisas locais
4. **Publicar no Facebook e Instagram** — partilhe o link do site
5. **Pedir avaliações no Google** — aumenta a credibilidade

---

## 🆘 Suporte

Para dúvidas técnicas ou actualizações do site, entre em contacto:

- 📧 desenvolvimento130@gmail.com
- 📱 WhatsApp: +258 85 851 0026

---

*Desenvolvido com ❤️ para Protege Aqui — © 2025*
