# 🌐 Guia: Configurar drivendatalabs.tech no GitHub Pages

## ✅ Passo 1: Arquivo CNAME Criado

O arquivo `CNAME` já foi criado e enviado para o GitHub com o domínio `drivendatalabs.tech`.

---

## 🔧 Passo 2: Configurar DNS no Provedor do Domínio

Você precisa configurar os registros DNS onde você comprou/gerencia o domínio `drivendatalabs.tech`.

### **Opção A: Usar Registros A (Recomendado para domínio raiz)**

Adicione estes 4 registros **A** apontando para os IPs do GitHub Pages:

```
Tipo: A
Nome: @ (ou deixe em branco)
Valor: 185.199.108.153
TTL: 3600 (ou padrão)

Tipo: A
Nome: @ (ou deixe em branco)
Valor: 185.199.109.153
TTL: 3600

Tipo: A
Nome: @ (ou deixe em branco)
Valor: 185.199.110.153
TTL: 3600

Tipo: A
Nome: @ (ou deixe em branco)
Valor: 185.199.111.153
TTL: 3600
```

### **Opção B: Usar CNAME (Para subdomínio www)**

Se quiser usar `www.drivendatalabs.tech`:

```
Tipo: CNAME
Nome: www
Valor: jcarlosbatista.github.io
TTL: 3600
```

---

## 📝 Passo 3: Configurar no GitHub Pages

1. **Acesse as configurações do repositório:**
   - https://github.com/jcarlosbatista/portfolio/settings/pages

2. **Em "Custom domain":**
   - Digite: `drivendatalabs.tech`
   - Clique em **Save**

3. **Marque a opção:**
   - ✅ **Enforce HTTPS** (recomendado)

---

## ⏱️ Passo 4: Aguardar Propagação DNS

- **Tempo estimado:** 10 minutos a 48 horas
- **Normalmente:** 1-2 horas

Você pode verificar se está funcionando em:
- https://www.whatsmydns.net/#A/drivendatalabs.tech

---

## 🔍 Passo 5: Verificar se Está Funcionando

Após a propagação DNS, acesse:
- **http://drivendatalabs.tech** (pode levar alguns minutos)
- **https://drivendatalabs.tech** (HTTPS será ativado automaticamente)

---

## ⚠️ Importante: Remover WordPress

Como o domínio está atualmente no WordPress, você precisa:

1. **Desconectar o domínio do WordPress:**
   - Acesse o painel do WordPress.com
   - Vá em Domínios → drivendatalabs.tech
   - Remova ou desconecte o domínio

2. **Ou configurar o DNS diretamente:**
   - Se o domínio está gerenciado em outro lugar (GoDaddy, Namecheap, etc.)
   - Acesse o painel de DNS do provedor
   - Configure os registros A conforme acima

---

## 🆘 Problemas Comuns

### "Domain does not resolve"
**Solução:** Aguarde mais tempo para propagação DNS (até 48h)

### "DNS check failed"
**Solução:** Verifique se os registros A estão corretos no seu provedor DNS

### "Certificate provisioning"
**Solução:** Aguarde alguns minutos, o GitHub gera o certificado SSL automaticamente

### Site não carrega
**Solução:** 
1. Verifique se o GitHub Pages está ativo
2. Verifique se o arquivo CNAME está no repositório
3. Limpe o cache do navegador (Ctrl+F5)

---

## 📋 Checklist

- [x] Arquivo CNAME criado e enviado
- [ ] DNS configurado no provedor (registros A)
- [ ] Domínio configurado no GitHub Pages
- [ ] WordPress desconectado do domínio
- [ ] Aguardando propagação DNS
- [ ] Site acessível em drivendatalabs.tech

---

## 🔗 Links Úteis

- **Repositório:** https://github.com/jcarlosbatista/portfolio
- **GitHub Pages Settings:** https://github.com/jcarlosbatista/portfolio/settings/pages
- **Verificar DNS:** https://www.whatsmydns.net/#A/drivendatalabs.tech
- **Documentação GitHub Pages:** https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

---

**Após configurar o DNS, seu site estará disponível em: https://drivendatalabs.tech** 🎉

