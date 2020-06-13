<h1 align=center>
<img src="https://raw.githubusercontent.com/Diegobbrito/nextlevelweek/master/mobile/assets/logonlw.svg" />
</h1>

<h3 align="center">

Projeto desenvolvido durante a semana **Next Level Week** da **[Rocketseat](https://rocketseat.com.br)** 
 </br>Utiliza as tecnologias ***TypeScript, Node, React e React Native***.

</h3>

## **:rocket: Objetivo**

O projeto **Ecoleta** tem como finalidade a conexão entre locais de coleta de resíduos e às pessoas que necessitam descartar esses resíduos. Auxiliando no descarte do lixo e colaborando para o processo de **recliclagem e reutilização**.


## **:computer: Tecnologias**


#### **Website** ([React][react] + [TypeScript][typescript])

  - **[Axios][axios]**
  - **[Leaflet][leaflet]**
  - **[React-Icons][react_icons]**
  - **[React-Leaflet][react_leaflet]**


#### **Server** ([NodeJS][node] + [TypeScript][typescript])

  - **[Express][express]**
  - **[KnexJS][knex]**
  - **[SQLite][sqlite3]**
  - **[ts-node][tsnode]**
  #### **Server** ([NodeJS][node] + [TypeScript][typescript])

#### **Mobile** ([React Native][react_native] + [TypeScript][typescript])
- **[Expo][expo]**

#### **Utilitários**

- API: **[IBGE API][ibge_api]**
- Fontes: **[Ubuntu][font_ubuntu]**, **[Roboto][font_roboto]**
- Ícones: **[Feather Icons][feather_icons]**
- Maps: **[Leaflet][leaflet]**
- Protótipo: **[Figma](https://www.figma.com/)**

[font_roboto]: https://fonts.google.com/specimen/Roboto

[font_ubuntu]: https://fonts.google.com/specimen/Ubuntu


<!-- Techs -->

[react]: https://reactjs.org/

[typescript]: https://www.typescriptlang.org/

[node]: https://nodejs.org/en/

[leaflet]: https://react-leaflet.js.org/en/

[ibge_api]: https://servicodados.ibge.gov.br/api/docs/localidades?versao=1

[react_native]: https://github.com/facebook/react-native

[express]: https://expressjs.com/

[knex]: http://knexjs.org/

[sqlite3]: https://github.com/mapbox/node-sqlite3

[tsnode]: https://github.com/TypeStrong/ts-node

[feather_icons]: https://feathericons.com/

[react_leaflet]: https://react-leaflet.js.org/

[react_icons]: https://react-icons.github.io/react-icons/

[axios]: https://github.com/axios/axios

[expo]: https://expo.io/


## :information_source: How To Use

Do seu Terminal:
```bash
# Clone o repositorio
$ git clone https://github.com/Diegobbrito/nextlevelweek.
```

### Install API 

```bash

# Entre na pasta
$ cd backend

# Instalar dependencias
$ yarn install

# Run Migrates
$ yarn knex:migrate

# Run Seeds
$ yarn knex:seed

# Iniciar o server
$ yarn dev
```

### Install Front-end

```bash

# Entre na pasta
$ cd frontent

# Instalar dependencias
$ yarn install

# Run
$ yarn start
```

### Install Mobile

```bash

# Entre na pasta
$ cd mobile

# Instalar dependencias
$ yarn install

# Run
$ yarn start

```
Made by Diego Brito [Get in touch!](https://www.linkedin.com/in/diego-brito-3265b4188/)

[nodejs]: https://nodejs.org/
[typescript]: https://www.typescriptlang.org/
[reactjs]: https://reactjs.org
[yarn]: https://yarnpkg.com/
