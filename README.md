# E-commerce Project

## Introdução

Este é um projeto de E-commerce construído com Next.js. O objetivo deste projeto é fornecer uma plataforma de compras online com uma experiência de usuário otimizada e recursos avançados.

## Instalação

Para instalar as dependências do projeto, execute o seguinte comando:

```bash
npm install
```
## Configuração .env

Antes de executar o projeto, você pode precisar configurar algumas variáveis de ambiente. Crie um arquivo `.env` na raiz do projeto e adicione suas variáveis de ambiente personalizadas.

Seu arquivo `.env` deve se parecer com isto:

```
DATABASE_URL=your_database_url
BETTER_AUTH_SECRET=your_better_auth_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
```
## Conexão com o Banco de Dados

Para conectar-se com o banco de dados, você precisa rodar alguns comandos. Lembre-se de que você deve ter o [Drizzle ORM](https://orm.drizzle.team/) instalado e configurado corretamente ou pode usar outro ORM de sua escolha.

1 - Execute o comando para subir o banco de dados.
```bash
npx drizzle-kit push
```
2 - Se você estiver usando o Drizzle ORM, certifique-se de que o arquivo `drizzle.config.ts` esteja configurado corretamente para apontar para o seu banco de dados.

3 - Bonus - Caso Queira acompanhar mais de perto a situação do banco de dados, o Drizzle oferece um ambiente de monitoramento em tempo real. Usando esse comando
```bash
npx drizzle-kit studio
```

## Uso

Para iniciar o servidor de desenvolvimento, execute:

```bash
npm run dev
```
ou 

```bash
yarn dev
```

Agora você pode acessar o aplicativo em [http://localhost:3000](http://localhost:3000).

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

