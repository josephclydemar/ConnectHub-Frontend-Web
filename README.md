<img src="./assets/connecthub-logo.png" height="300"/>
<br>


## `ConnectHub`-Frontend-Web

<br>

### Overall Project Description   
**`ConnectHub`** is a social media application inspired by the features of both Twitter and Facebook. It provides users with a platform to connect, share updates, and engage with friends and followers. With **`ConnectHub`**, users can post status updates, share photos and videos, follow other users, and engage in real-time conversations through comments and messages. The project consists of three main components: a Frontend server to handle data storage and processing, a frontend web interface for desktop users, and a frontend mobile interface for users on the go.

<br>

### Repository Description
**`ConnectHub`-Frontend-Web** is the frontend web repository for the **`ConnectHub`** social media application. It provides users with a web-based interface to access **`ConnectHub`**'s features and functionalities from desktop and laptop devices. Utilizing responsive design principles, **`ConnectHub`-Frontend-Web** offers an intuitive user experience, allowing users to browse their feed, interact with posts, and manage their profile with ease.


<br>
<br>
<br>
<br>

### React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

<br>
<br>

#### Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

