## NPM - Node Package Manager

- It enables you to install libraries, frameworks, and other development tools for your project, similar to installing a mobile application from an app store

### Important NPM Commands we use it when we developing the Node.js Application

#### 1. npm help (or) npm

```
Shows the list of available npm commands.

```

#### 2. npm init

```
The command is used to initialize a project. When you run this command, it creates a package.json file.

When running npm init, you’ll be asked to provide certain information about the project you’re initializing. This information includes the project’s name, the license type, the version, and so on.

To skip the process of providing the information yourself, you can simply run the

npm init -y
```

#### 3. npm install

```
This command is used to install packages. You can either install packages globally or locally.

When a package is installed globally, we can make use of the package’s functionality from any directory in our computer.

On the other hand, if we install a package locally, we can only make use of it in the directory where it was installed.

So no other folder or file in our computer can use the package.

Install Package Locally :
    npm install <package_name>

Install Package Globally :
    npm install <package_name> -g

Install all modules listed as dependencies in package.json.
    npm install
```

#### 4. npm [ls or list]

```
This command is used to list out the all npm packages

To List globally installed npm packages.
    npm ls -g

```

#### 5. npm uninstall

```
This command is used to uninstall a package.

To uninstall a package on actively working folder.
    npm uninstall <package_name>

To uninstall a package on globally
    npm uninstall <package_name> -g

```

#### 6. npm update

```
This command is used to update the packages.

To update all packages on actively working folder.
    npm update

To update all packages on global
    npm update -g

To update specifific package on actively working directory
    npm install <package_name>
    npm install <package_name>@latest

To update specifific package on globally
    npm install -g <package_name>
    npm install -g <package_name>@latest

To update a spefic package by version on actively working direcotory.
    npm install <package_name>@versionnumber

To update a spefic package by version on globally.
    npm install -g <package_name>@versionnumber
```
