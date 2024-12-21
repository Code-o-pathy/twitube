# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# Notes

-.getkeep
    --After committing, if you make empty folders and check git status, it wont show those folders because those aren't necessary because they don't contain anything. But if you really want to track those empty folders. Use .getkeep files in 'em.

-type="module"/"common"
    --module -(import react from 'react-client')
    --common -(require {react} from 'react-client')
    --still there is certain contradictions of module and common syntax like for .env but it would be handles later.

-nodemon
    --while doing backend you have to turn off and start the servers again to see the effects of the changes. Nodemon restarts the server autommatically once you save the file. Its a dev dependency. Not sent over github. 
    --give a script comman in package.json. Eg-"start":"nodemon src/index.js".

-prettier
    --when working on a large project with mulitple developers, its essential for all the developers to have same formatting otherwise conflict arises while uploading to git. Prettier's dev dependency helps to maintain a standard format.