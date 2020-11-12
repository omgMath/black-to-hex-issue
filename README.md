# Reproduction of Arial #000 instead of Arial Black
* Clone the repository
* Run `npm run build`
* Check the `./.next/static/css/<id>.css`

It should look like this:
```
html{font-family:Impact,Arial #000,Arial,sans-serif}
```