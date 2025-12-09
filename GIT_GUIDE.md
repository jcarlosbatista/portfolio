# 📚 Guia de Atualização no GitHub

## ✅ Push Realizado com Sucesso!

Seu código já está no GitHub: https://github.com/jcarlosbatista/portfolio

---

## 🚀 Como Atualizar o Repositório (Passo a Passo)

### **Opção 1: Via Terminal (Recomendado)**

1. **Navegue até a pasta do projeto:**
   ```bash
   cd "/Users/batista/Library/CloudStorage/GoogleDrive-jcarlos.batista@gmail.com/My Drive/Workspace_Projects/Projeto_Portifolio"
   ```

2. **Verifique o status das alterações:**
   ```bash
   git status
   ```
   Isso mostra quais arquivos foram modificados.

3. **Adicione os arquivos alterados:**
   ```bash
   git add .
   ```
   Ou para arquivos específicos:
   ```bash
   git add index.html
   git add projetos/databricks.html
   ```

4. **Faça o commit com uma mensagem descritiva:**
   ```bash
   git commit -m "Descrição do que foi alterado"
   ```
   Exemplos:
   - `git commit -m "Atualização de informações de experiência"`
   - `git commit -m "Adicionado novo projeto Databricks"`
   - `git commit -m "Correção de links e melhorias no layout"`

5. **Envie as alterações para o GitHub:**
   ```bash
   git push
   ```

6. **Pronto!** As alterações estarão no GitHub e o GitHub Pages atualizará automaticamente (pode levar alguns minutos).

---

### **Opção 2: Via GitHub Desktop (Interface Gráfica)**

1. **Instale o GitHub Desktop:** https://desktop.github.com/
2. **Abra o GitHub Desktop** e adicione o repositório local
3. **Faça as alterações** nos arquivos
4. **No GitHub Desktop:**
   - Veja as alterações na aba "Changes"
   - Escreva uma mensagem de commit
   - Clique em "Commit to main"
   - Clique em "Push origin" para enviar

---

## 📝 Comandos Úteis

### Ver histórico de commits:
```bash
git log --oneline
```

### Ver diferenças antes de commitar:
```bash
git diff
```

### Desfazer alterações não commitadas:
```bash
git restore nome-do-arquivo.html
```

### Ver status atual:
```bash
git status
```

### Atualizar do GitHub (se alguém mais mexer):
```bash
git pull
```

---

## 🔄 Fluxo Completo de Atualização

```bash
# 1. Ver o que mudou
git status

# 2. Adicionar tudo
git add .

# 3. Commitar
git commit -m "Sua mensagem aqui"

# 4. Enviar para o GitHub
git push
```

---

## 🌐 Ativar GitHub Pages (se ainda não fez)

1. Acesse: https://github.com/jcarlosbatista/portfolio/settings/pages
2. Em **"Source"**, selecione: **Deploy from a branch**
3. **Branch:** `main`
4. **Folder:** `/ (root)`
5. Clique em **Save**

Seu site estará em: **https://jcarlosbatista.github.io/portfolio/**

---

## ⚠️ Dicas Importantes

- **Sempre faça commit antes de fazer push**
- **Use mensagens de commit descritivas** (ex: "Correção de links" ao invés de "update")
- **O GitHub Pages atualiza automaticamente** após cada push (pode levar 1-2 minutos)
- **Se algo der errado**, você pode ver o histórico com `git log` e voltar a versões anteriores

---

## 🆘 Problemas Comuns

### Erro: "fatal: not a git repository"
**Solução:** Certifique-se de estar na pasta correta do projeto.

### Erro: "Permission denied"
**Solução:** Verifique suas credenciais do GitHub ou use um Personal Access Token.

### Erro: "Updates were rejected"
**Solução:** Alguém fez alterações no GitHub. Execute `git pull` primeiro, depois `git push`.

---

## ✅ Checklist de Atualização

- [ ] Fiz as alterações nos arquivos
- [ ] Verifiquei com `git status`
- [ ] Adicionei os arquivos com `git add .`
- [ ] Fiz commit com mensagem descritiva
- [ ] Fiz push com `git push`
- [ ] Verifiquei se o site atualizou (aguarde alguns minutos)

---

**Pronto! Agora você sabe como atualizar seu portfólio no GitHub! 🎉**

