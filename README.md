# 🤖 Saro Crypto Bot

Seja bem-vindo(a) ao **Saro Crypto Bot**! 🚀  
Aqui você encontrará todas as instruções para rodar o projeto e configurá-lo facilmente. Vamos nessa? 🎉

---

## 🛠️ Configuração Inicial

1. **Instale as dependências:**
   ```bash
   npm install
    ```

2. **Copie o arquivo de exemplo de configuração:**
   ```bash
   cp .env.example .env
   ```

3. **Configure as variáveis de ambiente:**
   Abra o arquivo `.env` e preencha as variáveis de ambiente com os valores necessários.

4. **🌐 Configurando o Ngrok**
    ```bash
   docker run --net=host -it -e NGROK_AUTHTOKEN=<seu-token-aqui> ngrok/ngrok:latest http 80
    ```
    - **Nota:** O token do Ngrok pode ser obtido em [https://dashboard.ngrok.com/get-started/setup](https://dashboard.ngrok.com/get-started/setup)

5. ** Para modo de desenvolvimento:**
   ```bash
   npm run dev
   ```
   
6. ** Para modo de produção:**
   ```bash
    npm run start
    ```
   
7. **🎉 Pronto!**
   Seu bot está rodando e pronto para ser utilizado. Aproveite! 🚀
