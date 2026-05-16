# 🔍 CNPJ Lookup Rebel

> **Be Rebel, but bring data** — Consulte CNPJs em tempo real com uma ferramenta moderna, rápida e pronta para usar.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Production-green.svg)]()
![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)

---

## ✨ Funcionalidades

- 🔎 **Consulta de CNPJ em tempo real** via BrasilAPI
- 📊 **Dados completos**: razão social, porte, situação cadastral, sócios e muito mais
- 💾 **Histórico local**: todas as buscas são salvas automaticamente no navegador
- 📥 **Exportação CSV**: baixe seu histórico de pesquisas em um clique
- 🌙 **Dark Mode**: tema automático conforme preferência do sistema
- 📱 **Responsivo**: funciona perfeito em desktop, tablet e mobile
- 🚀 **100% Standalone**: sem dependências backend, sem servidor necessário
- 🎨 **Design Rebel Analytics**: interface moderna com identidade visual própria

---

## 🎯 Como Usar

### Online (recomendado)
Abra diretamente no seu navegador:
```
https://seu-usuario.github.io/cnpj-lookup/cnpj-lookup-rebel-final.html
```

### Localmente
1. Baixe o arquivo `cnpj-lookup-rebel-final.html`
2. Abra no seu navegador (duplo clique)
3. Pronto! Funciona offline

---

## 📋 O que você consegue consultar

| Campo | Descrição |
|-------|-----------|
| **CNPJ** | Número do CNPJ formatado |
| **Razão Social** | Nome oficial da empresa |
| **Nome Fantasia** | Nome comercial (se houver) |
| **Situação Cadastral** | ATIVA / INATIVA |
| **Porte** | ME / EPP / Demais |
| **Setor (CNAE)** | Classificação da atividade econômica |
| **Bairro** | Localização |
| **Ano de Fundação** | Quando a empresa foi aberta |
| **Idade da Empresa** | Tempo de operação em anos |
| **Sócios** | Nome e qualificação dos sócios |

---

## 🏗️ Arquitetura

```
cnpj-lookup-rebel-final.html
├── Frontend (HTML/CSS/JS)
├── localStorage (histórico local)
└── BrasilAPI (dados públicos)
```

**Tecnologias:**
- HTML5
- CSS3 (Grid, Flexbox, Dark Mode)
- JavaScript (Fetch API, localStorage)
- [BrasilAPI](https://brasilapi.com.br) para dados CNPJ

---

## 🎨 Design

- **Paleta Rebel Analytics**:
  - Primary: `#1C3F45` (Deep Teal)
  - Accent: `#2EC4B6` (Cyan Data)
  - Off-white: `#F8F8F8`

- **Tipografia**: System fonts (Apple, Google, Microsoft)
- **Ícones**: Tabler Icons
- **Responsividade**: Mobile-first, otimizado para todos os tamanhos

---

## 💾 Armazenamento

Todos os dados são armazenados **localmente no seu navegador** usando `localStorage`:

- ✅ Nada é enviado para servidores
- ✅ Histórico persiste entre sessões
- ✅ Máximo de 100 últimas buscas
- ✅ Você pode exportar como CSV quando quiser
- ✅ Pode limpar o histórico a qualquer momento

---

## 📊 Casos de Uso

Perfeito para:
- 🏢 **Equipes públicas** (CGE, Ouvidoria, etc)
- 📋 **Pesquisa de empresas** rápida e confiável
- 💼 **Due diligence** simples
- 📑 **Relatórios** com dados CNPJ consolidados
- 🔍 **Consultas em lote** (use o histórico + exportação CSV)

---

## 🚀 Deploy

### GitHub Pages (recomendado)
1. Faça fork deste repositório
2. Vá em **Settings** → **Pages**
3. Selecione **main** como source
4. Seu link estará pronto em `https://seu-usuario.github.io/cnpj-lookup/`

### Vercel
```bash
vercel --prod
```

### Netlify
1. Faça drag & drop do arquivo
2. Pronto!

---

## 🔧 Desenvolvedores

Para customizar ou expandir:

1. Edite `cnpj-lookup-rebel-final.html`
2. Altere cores na seção `:root` (CSS)
3. Modifique o endpoint da API se necessário
4. Commit e push

---

## 📝 Licença

MIT License - Sinta-se livre para usar, modificar e compartilhar!

---

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas! Abra uma [issue](https://github.com/seu-usuario/cnpj-lookup/issues) ou faça um pull request.

---

## ⚖️ Aviso Legal

- Dados obtidos de fontes públicas (BrasilAPI)
- Não é responsabilidade deste projeto a precisão ou atualidade dos dados
- Use para consultas informativas

---

## 📞 Suporte

Dúvidas? Abra uma issue no GitHub ou entre em contato!

---

## 🎯 Roadmap

- [ ] Busca por nome de empresa
- [ ] Análise de sócios em comum
- [ ] Integração com dados de restrições (inadimplência, etc)
- [ ] API própria para integrações
- [ ] Versão em aplicativo mobile

---

**Made with ❤️ for public sector data transparency**

*"Be Rebel, but bring data" — Rebel Analytics*
