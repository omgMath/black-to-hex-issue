# Reproduction of Arial #000 instead of Arial Black
* Clone the repository
* `cd` into it
* Run `npm i`
* Run `npm run build`
* Check the `./.next/static/css/<id>.css`

It should look like this:
```CSS
html{font-family:Impact,Arial #000,Arial,sans-serif}
```

Expectation would be:
```CSS
html{font-family:Impact,Arial black,Arial,sans-serif}
```