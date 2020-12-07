}
  "scripts": {
    "docs:build": "vuepress build docs --temp docs/.temp",
    "docs:dev": "vuepress dev docs --temp docs/.temp",
    "build": "vuepress build docs",
    "dev": "vuepress dev docs",
    "lint": "eslint . --ext .js,.vue",
    "prepublishOnly": "npm run test && npm run docs:build && conventional-changelog -p angular -r 2 -i CHANGELOG.md -s",
    "start": "yarn dev",
    "test": "jest"
  },
