### Hello

Micah Woods

@mwoods79

---

### Heroku

---

### shameless plug

Jax.ex

---

### oclif > _

---

Open CLI Framework

---

### what is it?

---

oclif is an open source framework for building a command line interface (CLI) in Node.js.

---

Create CLIs with a few flags or advanced CLIs that have subcommands.

---

oclif makes it easy for you to build CLIs for your company, service, or your own development needs.

---

### who uses it?

* Heroku
* Salesforce
* Adobe
* Apollo
* Netlify
* You should be

---

### why?

* repeatable or composable tasks
* machine readable output
* scripting
* easily interact with an api

---

### what we'll discuss

* how Heroku uses oclif
* why you want to use oclif
* examples of you using oclif

---

### oclif single commands

```
ls
cat
```

---

### generates documentation

```
heroku help apps
heroku apps --help
heroku apps -h
```

---

### testing harness for free

```
yarn test
npm test
```

---

### "multi" command cli's

```
git init
heroku apps
sfdx force
```

---

multi commands can be build as plugins

```
heroku plugins:generate
heroku plugins:install plugin-name
```

---

heroku command built using plugins

---

The Heroku CLI is actually a couple dozen plugins

https://github.com/heroku/cli/tree/master/packages

---

Some plugins are not installed by default:

`heroku plugins:install heroku-kafka`

---

### plugins allow

* teams to maintain their own code
* for support and admin tools
* beta plugins while implementing new features

---

### plugins is an oclif plugin

```
yarn add @oclif/plugin-plugins
```

---

### workshop time

---

https://github.com/mwoods79/gub
