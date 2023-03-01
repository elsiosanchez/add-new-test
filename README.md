# Add new Page
Add a new window or route through a module

Example add windows test2


### Import or Add Module

#### Locate in the module folder of the project

```bash
└─ src                      # Main source code.
    └─ Modules               # Global modules.
```
#### Clone the new module

```typeScript
git clone https://github.com/elsiosanchez/add-new-test.git
```

### Go to the Configuration of the nuxt.config.ts Add path of the new module
```typeScript

export default defineNuxtConfig({
    modules: [
    '~/modules/pages/index', // --> Register new module
    '@element-plus/nuxt',
    '@nuxt/ui',
    ]
})
```

### Gif 



https://user-images.githubusercontent.com/45974454/222233399-293bcae0-d46f-4511-b11a-db9e326daa03.mp4



### Issues or improvements

[#1](https://github.com/elsiosanchez/add-new-test/issues/1)
