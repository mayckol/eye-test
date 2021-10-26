# Eye Test
## (Diretório Raiz: ``eye-test``)

Clonar os respositórios

`$` git clone git@github.com:mayckol/api-mock-restaurant.git\
`$` git clone git@github.com:mayckol/frontend-restaurant

#  Instalação das dependências:(na raiz)
`$` cd api-mock-restaurant\
`$` yarn\
`$` cd ../frontend-restaurant\
`$` yarn\
##  OU
`$` cd api-mock-restaurant && yarn && cd ../frontend-restaurant && yarn
#  Ambiente utilizando Docker:

###  No diretório raiz
`$` docker-compose up -d

================================================================================
#  Ambiente sem docker

###  No diretório ``api-mock-restaurant`` execute\
`$`yarn dev
###  No diretório `frontend-restaurant`` execute\
`$`yarn start

#  Portas utilizadas

``eyemobile_frontend  0.0.0.0:9000->3000/tcp``

``eyemobile_mock 0.0.0.0:3003->3003/tcp``

#  Informações

#### Os registros mock ficam do arquivo db.json dentro do diretório ``api-mock-restaurant``.
#### Necessário node, yarn ou npm.😉
