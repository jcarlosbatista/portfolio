# 📝 Guia Rápido: Comandos Git para Atualizar o Site

## 🚀 Passos para Atualizar o Site no GitHub

### **1. Verificar o Status**
```bash
git status
```
Mostra quais arquivos foram modificados.

---

### **2. Adicionar Arquivos Alterados**
```bash
git add .
```
Adiciona TODOS os arquivos modificados.

**Ou para arquivos específicos:**
```bash
git add index.html
git add projetos/databricks.html
```

---

### **3. Fazer Commit**
```bash
git commit -m "Descrição do que foi alterado"
```

**Exemplos de mensagens:**
```bash
git commit -m "Atualização: Alterado anos de experiência para 15 anos"
git commit -m "Correção: Ajustado texto da seção Sobre"
git commit -m "Novo: Adicionado projeto Databricks"
git commit -m "Atualização: Novos contatos e links"
```

---

### **4. Enviar para o GitHub**
```bash
git push
```

---

## ⚡ Comando Completo (Tudo de Uma Vez)

```bash
git add . && git commit -m "Sua mensagem aqui" && git push
```

**Exemplo:**
```bash
git add . && git commit -m "Atualização: 15 anos de experiência" && git push
```

---

## 📋 Fluxo Completo Passo a Passo

```bash
# 1. Ir para a pasta do projeto
cd "/Users/batista/Library/CloudStorage/GoogleDrive-jcarlos.batista@gmail.com/My Drive/Workspace_Projects/Projeto_Portifolio"

# 2. Ver o que mudou
git status

# 3. Adicionar tudo
git add .

# 4. Fazer commit
git commit -m "Descrição das alterações"

# 5. Enviar para GitHub
git push
```

---

## ⏱️ Após o Push

- **GitHub Pages atualiza automaticamente** em 1-5 minutos
- **Acesse:** https://drivendatalabs.tech/
- **Se não atualizar:** Limpe o cache do navegador (Ctrl+Shift+R)

---

## 🔍 Comandos Úteis Adicionais

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

### Ver status detalhado:
```bash
git status -s
```

---

## 🆘 Problemas Comuns

### Erro: "nothing to commit"
**Solução:** Não há alterações para commitar. Verifique se salvou os arquivos.

### Erro: "Permission denied"
**Solução:** Verifique suas credenciais do GitHub ou use um Personal Access Token.

### Erro: "Updates were rejected"
**Solução:** Alguém fez alterações no GitHub. Execute:
```bash
git pull
git push
```

---

## ✅ Checklist Rápido

- [ ] Fiz as alterações nos arquivos
- [ ] Salvei os arquivos
- [ ] Executei `git add .`
- [ ] Executei `git commit -m "mensagem"`
- [ ] Executei `git push`
- [ ] Aguardei alguns minutos
- [ ] Verifiquei o site: https://drivendatalabs.tech/

---

**Pronto! Agora você sabe como atualizar seu site! 🎉**

