# BRJS ESLint config
To use this ESLint config for your project clone it locally and then:

```bash
cd path_to_your_project
npm link path_to_eslint-config-caplin
```

Then create a `.eslintrc` in your project root folder with the following content:

```json
{
	"extends": "eslint-config-caplin"
}
```

For the moment it is not possible to lint this project via npm run test, but it should be possible. Instead, you need to have eslint installed globally (`npm install -g eslint`) and use the command:

```bash
eslint .
```
