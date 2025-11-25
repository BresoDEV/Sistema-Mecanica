
# Sistema Mecânica

Este projeto é uma página simples chamada **Sistema Mecânica**, construída em HTML/JS, que permite gerenciar senhas de sites diretamente no navegador. Os dados ficam salvos localmente, sem necessidade de servidor — ideal para uso pessoal e rápido.

Acesso:https://bresodev.github.io/Sistema-Mecanica/
---

## 🚀 O que faz?

- Permite salvar entradas com **site**, **e-mail** e **senha**.  
- Exibe uma lista das senhas salvas de forma organizada e legível.  
- Permite apagar cada entrada individualmente.  
- Possui um mecanismo para **exportar** todas as entradas como código JavaScript, para que você possa importar em outro navegador ou sessão.  
- Protege o acesso à página usando uma **senha principal** gravada no `localStorage`.  
- Usa uma criptografia simples (ROT13) para ofuscar os dados no `localStorage`.

---

## ✅ Por que usar?

- Gerenciar senhas sem depender de serviços externos ou nuvem.  
- Ter um sistema de controle leve, rápido e totalmente offline.  
- Fazer backup manual das entradas usando exportação/importação de código.  
- Ter mais privacidade, já que tudo fica apenas no seu navegador.

---

## 💡 Como usar?

1. Abra o arquivo HTML (`index.html`) no seu navegador favorito.  
2. Se for a primeira vez, configure a **senha de acesso** no `localStorage` para liberar o uso da página.  
3. Insira os dados (site, e-mail e senha) nos campos e clique em **Salvar** para adicionar uma nova entrada.  
4. As senhas adicionadas aparecerão como seções expansíveis — clique para ver o e-mail e a senha.  
5. Para apagar uma entrada, basta usar o botão **Apagar** correspondente.  
6. Para exportar todas as entradas, clique no cadeado: ele mostrará todo o código necessário para recriar os dados em outro local.  
7. Se quiser importar, cole esse código na área e clique em **Executar** para restaurar os dados no `localStorage`.

---

## ⚠️ Importante

- A criptografia usada (ROT13) **não é segura para dados sensíveis**. Use essa ferramenta apenas para senhas não críticas ou para estudo.  
- Como os dados ficam no `localStorage`, se você limpar os dados do navegador, tudo será perdido.  
- Certifique-se de guardar o código de exportação se quiser migrar seus dados.

---

## ✨ Ideal para

- Quem quer uma solução simples e offline para gerenciar senhas.  
- Desenvolvedores ou curiosos que querem entender como manipular `localStorage` e criptografia básica.  
- Usuários que preferem ter controle total sobre seus dados — sem depender de serviços externos.

---

Feito com simplicidade para dar a você um controle prático das suas senhas no navegador — sem complicação. 😊  

