# Excluding file from build doesn't work

## Reproduce:
1. clone
2. `npm ci`
3. `npm run build` -> -dev.ts throws error

**This error shows that none of the 3 methods for ignoring a file works (-prefix, .nuxtignore, config ignore property)**
