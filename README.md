# Commands

```npm
npm install release-it @release-it/conventional-changelog @commitlint/config-conventional @commitlint/cli --include=dev
```

```npm
npm install husky --include=dev
```

```
touch .husky/commit-msg && chmod a+x .husky/commit-msg
```

commit-msg:
```
npx commitlint --edit
```

package.json
```
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "release": "release-it"
  },
```