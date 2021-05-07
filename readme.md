# Projectstorm react-diagram with Vite issue

This project is a demo to illustrate the issue.
Sources:
 - [Vite React Typescript starter](https://github.com/vitejs/vite/tree/main/packages/create-app/template-react-ts)
 - [diagrams-demo-project](https://github.com/projectstorm/react-diagrams/tree/master/diagrams-demo-project)

## Things to observe:

### Development

Starting the project in development mode works as expected. 
`vite` or `npm start`

### Production

Building the project, and then hosting it does NOT work.
```
vite build
vite preview
```
or
```
npm run serve
```

The following issue can be seen.

```
Uncaught TypeError: Cannot read property 'Polygon' of undefined
    at Rectangle.js:8
    at u (vendor.227e0528.js:1)
    at Point.js:66
```