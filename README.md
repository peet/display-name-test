## eslint-plugin-react dsiplay-name false negatives

This repo contains 5 .jsx files that should report errors for the `display-name` rule specified in `.eslintrc.js`

### `npm test` output

```
> display-name-test@1.0.0 test C:\Peet\git\displayName
> eslint --ext .jsx .


C:\Peet\git\displayName\HasDisplayNameError.jsx
  3:36  error  Component definition is missing display name  react/display-name

✖ 1 problem (1 error, 0 warnings)

npm ERR! Test failed.  See above for more details.
```

