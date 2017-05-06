# Style Guides

## Node.js
1. In your project add this repo as a devDependency:
   ```
   yarn add --dev github:beta-district/styleguide
   ```

2. Create a `.eslintrc.json` file that extends these rules:
    ```json
    {
      "root": true,
      "extends": ["./node_modules/eslint-config-betadistrict/eslintrc.js"]
    }
    ```

3. Add this to `codeclimate.yml`:
    ```yaml
    prepare:
      fetch:
      - url: "https://raw.githubusercontent.com/beta-district/styleguide/master/eslintrc.js"
        path: "node_modules/eslint-config-betadistrict/eslintrc.js"
    ```

### Without Code Climate Support
Extend the base config normally in `.eslintrc.json`:
```
  "extends": ["betadistrict"]
```

## Ruby


## Golang
\#todo
