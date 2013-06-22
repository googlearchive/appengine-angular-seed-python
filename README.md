## App Engine angular-seed Python

Trivial Python App Engine app based on [angular-seed](https://github.com/angular/angular-seed)

Author: Fred Sauer <fredsa@google.com>


## Project setup

1. Install the [App Engine Python SDK](https://developers.google.com/appengine/downloads)
1. If you didn't use `--recursive` with your `git clone` command, manually update the `angular-seed` submodule:

```
git submodule update --init
```


## Testing the app locally

To run the app locally:

```
dev_appserver.py .
```


## Deploying

To deploy the application:

1. Use the [Google Cloud Console](https://cloud.google.com/console) to create an app
1. Replace `your-app-id` in `app.yaml` with the app id from the previous step
1. Deploy the application

```
appcfg.py --oauth2 update .
```


## Contributing changes

See [CONTRIB.md](CONTRIB.md)


# Licensing

See [LICENSE](LICENSE)
