# mercado-chile-cron

Repo vacio a proposito: existe solo para que el cron de precios de
[mercado-chile](https://github.com/cristobalGGg/mercado-chile) corra cada 5
minutos gratis. GitHub da minutos de Actions ilimitados solo en repos
publicos (con un piso real de 5 min entre corridas de cron, no menos). El
codigo de la aplicacion vive en el repo privado; este solo lo checkea con un
token de solo lectura y corre el mismo script. Ver `.github/workflows/precios.yml`.
