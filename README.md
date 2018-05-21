# ember-test-runner


```
docker run -it -e CI=true -v $PWD:/usr/src nesoio/ember-test-runner:chrome ember test
```

## Chromium
```
docker run -it -e CI=true -v $PWD:/usr/src nesoio/ember-test-runner:chromium ember test
```

## Firefox [ESR](https://support.mozilla.org/en-US/kb/switch-to-firefox-extended-support-release-esr)
```
docker run -it -e CI=true -v $PWD:/usr/src nesoio/ember-test-runner:firefox-esr ember test
```
