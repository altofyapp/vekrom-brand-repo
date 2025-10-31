# 🚀 Guia Rápido de Deploy - Vekrom Brand

## 📦 Passo 1: Preparar Repositório no GitHub

### 1.1 Criar Repositório
```bash
# Vá para GitHub.com e crie um novo repositório
# Nome sugerido: vekrom-brand
# Visibilidade: Public (para Vercel grátis) ou Private
```

### 1.2 Upload dos Arquivos

**Opção A: Via Interface do GitHub (Mais Fácil)**
1. Baixe a pasta `vekrom-brand-repo` completa
2. No GitHub, clique em "uploading an existing file"
3. Arraste TODOS os arquivos e pastas
4. Commit!

**Opção B: Via Git CLI**
```bash
# Navegue até a pasta vekrom-brand-repo
cd vekrom-brand-repo

# Inicializar Git
git init

# Adicionar arquivos
git add .

# Primeiro commit
git commit -m "🎨 Initial commit - Vekrom Brand Identity"

# Conectar ao GitHub (substitua SEU-USUARIO e SEU-REPO)
git remote add origin https://github.com/SEU-USUARIO/SEU-REPO.git

# Push
git branch -M main
git push -u origin main
```

---

## 🌐 Passo 2: Deploy na Vercel

### 2.1 Método Automático (Recomendado)

1. Acesse [vercel.com](https://vercel.com)
2. Faça login com GitHub
3. Clique em **"New Project"**
4. Selecione o repositório `vekrom-brand`
5. Clique em **"Deploy"**
6. Aguarde 30 segundos... Pronto! ✨

**Sua URL será algo como:**
`https://vekrom-brand.vercel.app`

### 2.2 Método Via CLI

```bash
# Instalar Vercel CLI globalmente
npm install -g vercel

# Fazer login (vai abrir o navegador)
vercel login

# Na pasta do projeto
cd vekrom-brand-repo

# Deploy
vercel

# Para production
vercel --prod
```

---

## 📱 Passo 3: Embed no Notion

### Método 1: Embed Direto (Melhor)

1. No Notion, em qualquer página, digite: `/embed`
2. Cole sua URL da Vercel: `https://vekrom-brand.vercel.app`
3. Pressione Enter
4. Ajuste o tamanho arrastando as bordas

**Resultado:** Showcase interativo dentro do Notion! 🎉

### Método 2: Bookmark com Preview

1. Cole a URL diretamente na página
2. Quando aparecer o preview, clique em "Create bookmark"
3. Fica mais clean e clicável

### Método 3: Full Page Embed

1. Crie uma página em branco no Notion
2. Digite `/embed`
3. Cole a URL
4. Expanda para preencher toda a página
5. Perfeito para apresentações! 📊

---

## ⚙️ Configuração de Domínio Customizado (Opcional)

### Se você tem um domínio próprio:

1. Na Vercel, vá em: **Settings → Domains**
2. Adicione seu domínio: `brand.vekrom.com`
3. Configure o DNS conforme instruções
4. Aguarde propagação (até 48h)

**Sugestões de subdomínios:**
- `brand.vekrom.com`
- `identity.vekrom.com`
- `assets.vekrom.com`
- `design.vekrom.com`

---

## 🎯 URLs Úteis Após Deploy

Assumindo que sua URL base é `https://vekrom-brand.vercel.app`:

- **Showcase Principal:** `https://vekrom-brand.vercel.app`
- **Guia Rápido:** `https://vekrom-brand.vercel.app/quick-guide`
- **Logo Azul:** `https://vekrom-brand.vercel.app/assets/vekrom-final-blue-gradient.svg`
- **Logo Verde:** `https://vekrom-brand.vercel.app/assets/vekrom-final-green-gradient.svg`

**Use essas URLs para:**
- Embedar logos em sites externos
- Compartilhar em apresentações
- Referenciar em documentação
- Usar em emails HTML

---

## 🔄 Atualizações Automáticas

**Uma vez configurado, toda vez que você fizer um push no GitHub:**
1. Vercel detecta automaticamente
2. Faz rebuild
3. Deploya a nova versão
4. Tudo em ~30 segundos!

---

## 🐛 Troubleshooting

### "Página não carrega"
- Verifique se todos os arquivos estão na pasta correta
- Confirme que `index.html` está na raiz
- Check se `vercel.json` está presente

### "Imagens não aparecem"
- Verifique se a pasta `assets/` foi commitada
- Confirme que os caminhos são `assets/vekrom-...`
- Teste localmente primeiro

### "Embed no Notion não funciona"
- Certifique-se que o repositório é público
- Aguarde alguns minutos após deploy
- Tente limpar cache do Notion (cmd/ctrl + shift + R)

---

## 💡 Dicas Pro

1. **Performance:** Vercel já otimiza automaticamente (CDN global)
2. **Analytics:** Ative Vercel Analytics para ver visitas
3. **Preview:** Cada PR no GitHub gera uma URL de preview
4. **Rollback:** Fácil voltar versões anteriores na Vercel

---

## 📊 Checklist Final

- [ ] Repositório criado no GitHub
- [ ] Todos os arquivos commitados
- [ ] Deploy feito na Vercel
- [ ] URL funcionando
- [ ] Embed testado no Notion
- [ ] Domínio customizado configurado (opcional)

---

## 🎉 Pronto!

Agora você tem:
✅ Repositório profissional no GitHub  
✅ Site hospedado na Vercel com CDN global  
✅ Showcase embedado no Notion  
✅ URLs públicas para todos os assets  

**Compartilhe:** `https://vekrom-brand.vercel.app` 🚀

---

**Precisa de ajuda?**  
- GitHub: [github.com/vercel](https://github.com/vercel)
- Vercel Docs: [vercel.com/docs](https://vercel.com/docs)
- Notion Help: [notion.so/help](https://notion.so/help)
