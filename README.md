# Emagre-aTop
Site para emagrecimento
# EmagreçaTop – Site Oficial  
*“Emagreça com saúde e sem restrições”*

Bem-vindo ao repositório que hospeda o site da marca **EmagreçaTop**. Aqui estão os passos para publicação, configuração e manutenção.

---

## 1. Sobre o projeto  
Este é um site estático (HTML, CSS, JS) criado para a marca EmagreçaTop — com foco em emagrecimento saudável e sem restrições.  
Ele contém:  
- `index.html` — página principal  
- `styles.css` — estilos responsivos  
- `script.js` — lógica de calculadora/ formulário  
- Logo personalizada, cores definidas etc.

---

## 2. Como configurar o repositório no GitHub  
1. Se você ainda não tem conta, crie uma em https://github.com.  
2. Crie um novo repositório público. Pode se chamar algo como `emagrecatop-site` ou, se quiser link direto do tipo `usuario.github.io`, nomeie o repositório como `usuario.github.io`. :contentReference[oaicite:2]{index=2}  
3. Faça upload dos arquivos do site (index, styles.css, script.js, logo etc) para o repositório (via interface web ou via Git local).

---

## 3. Publicar com GitHub Pages  
1. No repositório, vá em **Settings → Pages** (ou **Code and automation → Pages**). :contentReference[oaicite:3]{index=3}  
2. Em “Source” (Fonte), selecione a branch que contém os arquivos (ex: `main`) e pasta raiz (`/ (root)`) ou `/docs` se for o caso. :contentReference[oaicite:4]{index=4}  
3. Clique em **Save** ou **Deploy**. Aguarde alguns minutos — o site ficará disponível no endereço indicado (algo como `https://usuario.github.io/` ou `https://usuario.github.io/emagrecatop-site/`). :contentReference[oaicite:5]{index=5}  
4. Verifique o link no navegador para garantir que o `index.html` foi carregado corretamente.

---

## 4. Dicas de manutenção  
- Sempre que atualizar os arquivos (novo conteúdo, design, logo), lembre de **commit** + **push** para a branch que está sendo publicada.  
- Após o push, aguarde brevemente e recarregue o link público. Pequenas mudanças podem demorar alguns minutos para refletir.  
- Para hospedagem com domínio personalizado, será necessário configurar no GitHub Pages e no DNS do domínio. :contentReference[oaicite:6]{index=6}  
- Para uso local (antes de subir): verifique se `index.html` abre corretamente no navegador, se as imagens/logos estão no caminho correto e se não há erros no console JS.

---

## 5. Cores & identidade visual  
- Cor principal verde-menta: `#16a085`  
- Cor de destaque azul-suave: `#3498db`  
- Logo horizontal “EmagreçaTop” em formato PNG + SVG disponibilizada nesta pasta.  
- Versão fallback apenas-texto para favicon ou uso pequeno.

---

## 6. Estrutura de pastas sugerida  
