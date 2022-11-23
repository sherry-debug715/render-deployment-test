# Curriculum Notes

Use `backend` server from
`FT12/practices/authenticate-me-for-render-deployment/backend` as the backend
server. Remember to do the following commands to start up the backend server:

```shell
cp .env.example .env
npm install
npx dotenv sequelize db:migrate
npx dotenv sequelize db:seed:all
npm start
```
