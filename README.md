# Movie Browser

<div style="text-align: center;">
    <img src="/src/assets/logo.svg" alt="Movie Browser Logo" width="200" />
</div>

## Descripción

**Movie Browser** es una aplicación web diseñada para explorar y buscar información sobre películas. La aplicación está desplegada y accesible en el siguiente enlace: [Movie Browser en Vercel](https://movie-spa-react-movie-browser.vercel.app/).

## Estructura de carpetas
movie-spa-react/
├── .env.local
├── .env.local.example
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── README.md
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
├── vite.config.ts
├── public/
│   └── vite.svg
└── src/
    ├── App.css
    ├── App.tsx
    ├── index.css
    ├── main.tsx
    ├── vite-env.d.ts
    ├── assets/
    │   ├── logo.png
    │   ├── logo.svg
    │   └── react.svg
    ├── components/
    │   ├── MovieCard.tsx
    │   └── SearchBar.tsx
    ├── interfaces/
    │   └── movies.ts
    ├── pages/
    │   ├── Home.tsx
    │   └── MovieDetails.tsx
    ├── routes/
    │   └── AppRoutes.tsx
    └── services/
        ├── movie.ts
        └── themoviedb.tsx

## Desplegar la aplicación

Para construir la aplicación para producción, utiliza el siguiente comando:
```bash
npm run build
```

Esto generará una carpeta `dist` con los archivos optimizados para producción.
