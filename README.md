# Fantasticon

![fantasticon](./img/fantasticon.svg)


> [Github](https://github.com/tancredi/fantasticon)

> [NPM](https://www.npmjs.com/package/fantasticon)
---

**How to Install Fantasticon to get your own IconFont**

> Create a ```Main``` Folder

> In the folder create two folder

> One for ```SVG``` src and the other for the ```iconfonts```


---

> # Step #01


### **Installing** Fantasticon

> In the main folder right click and open bash and type the following

```badh
npm install -g fantasticon
```

---
> # Step #02

### Creating a JSON File

> In main folder  type the following to generate a ```JSON``` file

```bash
npm init
```
---

```bash
npm init -y
```

---

> # Step #03

### Config the JSON File

> #### Defualt

```json
{
  "name": "my-iconfonts",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}
```


> #### Configured
```json
{
  "name": "my-iconfonts",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "generatelcons": "fantasticon ./path/to/your/SVG's Folder -o ./path/your/font Folder"
  },
  "author": "",
  "license": "ISC"
}
```

---

> # Step #04

### Creating Icon Fonts

```bash
npm run generatelcons
```

---

**This is a Note for ME!!**