# Hey We Code

[Hey We Code](https://heywecode.com) is a web IDE that allows teams to collaborate on front-end projects. It's currently in beta. If you run into issues, or have feature requests, please create an issue in the [Issues tab](https://github.com/jameslin123/heywecode/issues).

## Notes on usage

1. Anyone with the URL of your workspace will be able to edit content in the workspace.
2. You can import NPM packages in your scripts, for example ```import _ from 'lodash';``` Not all NPM packages are supported; if you run into one that doesn't work, feel free to report it with an issue.
2. You can create new scripts and stylesheets. Remember to reference them in index.html or import them into other scripts: ```import { myFn } from './myNewScript.js'```
3. TypeScript files can be directly referenced in index.html. They will be automatically transpiled.
4. Scripts are interpreted as ES6 modules.
5. Please use the ```jsx``` or ```tsx``` suffix for files that contain JSX syntax.