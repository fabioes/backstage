# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
cd backstage
yarn build:backend --config ../../app-config.yaml --config ../../app-config.production.yaml
docker image build . -f .\packages\backend\Dockerfile -t backstage:1.0.0
docker compose up
```
