## tasks todo

- Move `react-scripts to devDependencies

1. `npm uninstall react-scripts`
2. `npm install -D react-scripts`

- Talk about

- Fix scripts in our projects
- **deploy**: `node api/server.js`
- **build**: `npm run build:client`
- **build:client**: `react-scripts build` (this requires `homepage` to be correct)

- Remove `buid/` folder from being tracked

  - updated `.gitignore` (add `build/` back in there)
  - Remove from git `git rm -r --cached build/`
  - add/push changes

- in package.json
  - update homepage to point to your heroku address
    "homepage": "https://github.com/HackerYou/con-ed-full-stack#readme",
    aka https://amytangcodes-sportsapp.herokuapp.com
