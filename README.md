# deploy-action

> You can use this action autho-deploy your Dioxus web project.

```yml
name: github pages

on:
  push:
    branches:
      - main

jobs:
  build-deploy:
    runs-on: ubuntu-latest
    steps:
      - name: "Dioxus Deploy"
        uses: DioxusLabs/deploy-action@v1
        with:
          toolSource: "Dioxuslabs/cli"
```
