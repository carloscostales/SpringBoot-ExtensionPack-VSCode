# Pack de extensiones VSCode para SpringBoot
![spring-badge]

> Un pack de extensiones para proyectos SpringBoot en Visual Studio Code.

Esta pack de extensiones proporciona las siguientes extensiones:

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) - Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text.

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Auto rename paired HTML/XML tag.

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint JavaScript into VS Code.

- [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) - Popular extensions for Java development that provides Java IntelliSense, debugging, testing, Maven/Gradle support, project management and more.

- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Supercharge Git within VS Code — Visualize code authorship at a glance via Git blame annotations and CodeLens, seamlessly navigate and explore Git repositories, gain valuable insights via rich visualizations and powerful comparison commands, and so much more.

- [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets) - Full HTML tags including HTML5 Snippets.

- [IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) - AI-assisted development.

- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) - Full HTML tags including HTML5 Snippets.

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) - Launch a development local Server with live reload feature for static & dynamic pages.

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) - Material Design Icons for Visual Studio Code.

- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Code formatter using prettier.

- [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) - REST Client for Visual Studio Code.

- [Spring Boot Extension Pack](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-boot-dev-pack) - A collection of extensions for developing Spring Boot applications.

- [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml) - XML Language Support by Red Hat

# Instalacion Node.js

- Instalar [Node.js](https://nodejs.org/es/download/)

- Instalar herramientas de generacion de codigo para extensiones de VSCode

```bash
$ npm install -g generator-code
```

# Despliegue

- Clonar el repositorio

```bash
$ git clone https://github.com/carloscostales/VSCode-Extension-Pack-SpringBoot
```

- Instalar vsce

```bash
$ npm install -g vsce
```

- Crear el archivo .vsix

```bash
$ vsce package
```

- Instalar el pack desde el fichero (.vsix)

1. Lanzar Visual Studio Code
2. Escoger **Extensions** desde el menu
3. Click **More** > **Install from VSIX...**
4. Select the file `springboot-extensionpack-carlos-x.x.x.vsix`
5. Click **Reload Now** para recargar VSCode

# Publicar

- Crear un publisher

```bash
$ vsce create-publisher <publisher-name>
```

- Login

```bash
$ vsce login <publisher-name>
```

- Publicar

```bash
$ vsce publish
```

# Author

[Carlos Costales](https://github.com/carloscostales)

[spring-badge]: https://spring.io/images/spring-logo-9146a4d3298760c2e7e49595184e1975.svg