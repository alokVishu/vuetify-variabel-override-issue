# Variable Override issue in vuetify

- node v16.15.1
- OS Windows 10

## Project understanding

We are template vendors. We have created a folder structure to easily override variable by us and our client override both vuetify and our variable easily.

- `@core/scss/vuetify/variable` file override vuetify variables by me
- `@/styles/variables/_vuetify.scss` file where user/client can override vuetify and our custom variables.
- We have included `@/styles/variables/_vuetify.scss` file in   `vuetify.ts` file.


## Device

- I found that this issue behave weird in windows and <!-- markdownlint-capture --> mac system.
- I cannot override any variable in Windows system.
- In mac, I cannot override `font-family-root` variable and all other variable will override normally.