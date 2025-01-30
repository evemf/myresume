# [Vue Resume](https://github.com/evemf/myresume/) by Evelia Molina

It uses Vue 3.0 (Composition API) and Bootstrap 5.


#### Getting Started

1. Clone the repo:
```
git clone https://github.com/evemf/myresume
```

2. Go to the root directory of the project and install all dependencies with npm:
```
npm install
```

3. Run the project in developer mode:
```
npm run dev
```

#### Deployment

To compile the project for production, execute:

```
npm run build
``` 

This command triggers a series of processes that package your code, assets, and other necessary files, ultimately creating a production-ready version of your project. After running the command, you'll find the compiled files within the `dist` folder. This is the folder you should use for deploying your application to a live server or hosting platform.

For deploying to GitHub Pages, make sure to run this custom command after the build process:

```
npm run deploy
```
This command will create a `404.html` file as a copy of `index.html`, so when users access a secondary route (like `/education` or `/skills`), it will redirect them to the Vue App instead of GitHub's default 404 page.

#### Copyright and License

Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-agency/blob/master/LICENSE) license, providing complete freedom for utilization.