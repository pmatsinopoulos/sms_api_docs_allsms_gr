## Start API Docs server locally

```
bundle exec dotenv -f '.env.rayo' middleman server
```

will start the Rayo API Docs server locally.

## Deploy to Github Pages

Needs to be done for all white-label names:

### For `rayo`

```
bundle exec dotenv -f '.env.rayo' ./deploy.sh
```

### For `allsms`

```
bundle exec dotenv -f '.env.allsms' ./deploy.sh
```
