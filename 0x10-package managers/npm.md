## npm
-`npm` (Node Package Manager) is the default package manager for Node.js.

-It helps developers manage JavaScript libraries and tools (dependencies) easily.

-With npm, you can install, update, and manage project dependencies, as well as publish and distribute packages.

## Key features of npm

- Easy installation and management of dependencies.

- Support for local and global installation of packages.

- Ability to publish and distribute packages.

- Integration with popular package managers like Yarn and pnpm.

- Fast and efficient package resolution.

- Support for dependency resolution, version management, and dependency tree management.

- Easy debugging and error handling.

## Installing npm

- To install npm, you can use the following command:

```bash
npm install -g npm
```

- This will install npm globally on your system.

## Package.json and package-lock.json

- `package.json` contains a list of dependencies and their versions.

- `package-lock.json` contains a lock file that specifies the exact versions of dependencies used in the project.

- Both files are used to manage dependencies in a project.

# Key elements of package.json file

- `name`: The name of the project.

- `version`: The version of the project.

- `description`: A description of the project.

- `main`: The main entry point of the project.

- `scripts`: A list of scripts that can be run with `npm run <script-name>`.

- `dependencies`: A list of dependencies required by the project.

- `devDependencies`: A list of dependencies required for development only.

## Creating  a package.json file

- To create a package.json file, you can use the following command:

```bash
npm init
```

- This will create a new package.json file in the current directory.

- You can then edit the file to add your project details and dependencies.

- You can also use the `npm init -y` command to create a package.json file with default values.

- You can also use the `npm init -f` command to create a package.json file with no default values.

- When you install a package, npm stores the files and folders for this package in a folder called node_modules.

## package-lock.json

- `package-lock.json` is a file that contains a lock file that specifies the exact versions of dependencies used in the project.

- This file is used to manage dependencies in a project.

- When you install a package, npm stores the files and folders for this package in a folder called node_modules. 

## Installing a package

- To install a package, you can use the following command:

```bash
npm install <package-name>
```

- This will install the specified package and its dependencies in the `node_modules` folder.

- If you want to install a package globally, you can use the following command:

```bash
npm install -g <package-name>
```

- This will install the specified package and its dependencies globally, meaning they will be available on your system for all projects.

<hi>## Uninstalling a package</hi>

- To uninstall a package, you can use the following command:

```bash
npm uninstall <package-name>
```

- This will remove the specified package and its dependencies from the `node_modules` folder.

<h1>listing installed packages</h1>

- To list all installed packages, you can use the following command:

```bash
npm list
```

- This will show a list of all installed packages and their versions.

<h1>installing a specific version of a package</h1>

- To install a specific version of a package, you can use the following command:

```bash
npm install <package-name>@<version>
```

- This will install the specified package and its dependencies at the specified version.


<h1>check security vulnerabilities</h1>

- To check for security vulnerabilities in a package, you can use the following command:

```bash
npm audit
```

- This will check for vulnerabilities in the specified package and its dependencies.

## Development vs Regular/Production Dependencies

- Development dependencies are used for development and testing purposes.

- Regular/production dependencies are used for production and deployment.

- Development dependencies are installed using the `npm install` command.

- Regular/production dependencies are installed using the `npm install --save` command.

## Runing a script

- To run a script, you can use the following command:

```bash
npm run <script-name>
```

- This will run the specified script in the `scripts` section of the package.json file.

## Package Versioning and updates

- To update a package, you can use the following command:

```bash
npm update <package-name>
```

- This will update the specified package and its dependencies to the latest version.

- To update all packages, you can use the following command:

```bash
npm update
```

- This will update all packages and their dependencies to the latest version.

- To update a package to a specific version, you can use the following command:

```bash
npm update <package-name>@<version>
```

- This will update the specified package and its dependencies to the specified version.

- To update all packages to a specific version, you can use the following command:

```bash
npm update --save <package-name>@<version>
```

## Resources

-This are symbols used in npm versions
- [npm documentation](https://docs.npmjs.com/)




