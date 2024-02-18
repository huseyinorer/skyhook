## Setup

1. Create a webhook in Discord (Server Settings -> Webhooks -> Create Webhook)
2. Copy the webhook url
3. Turn the Discord webhook url into a skyhook webhook url like so:

```
Replace discord.com in url with skyhookapi.com
https://discord.com/api/webhooks/firstPartOfWebhook/secondPartOfWebhook
->
https://skyhookapi.com/api/webhooks/firstPartOfWebhook/secondPartOfWebhook
```

4. Add the provider you want to the end of the url:

```
https://skyhookapi.com/api/webhooks/firstPartOfWebhook/secondPartOfWebhook/providerGoesHere
```

## Supported Providers

- [AppCenter](https://learn.microsoft.com/en-us/appcenter/dashboard/webhooks/) - `/appcenter`
- [AppVeyor](https://www.appveyor.com/docs/notifications/#webhook-payload-default) - `/appveyor`
- [Basecamp 3](https://github.com/basecamp/bc3-api/blob/master/sections/webhooks.md) - `/basecamp`
- [BitBucket](https://confluence.atlassian.com/bitbucket/manage-webhooks-735643732.html) - `/bitbucket`
- [BitBucket Server](https://confluence.atlassian.com/bitbucketserver/event-payload-938025882.html) - `/bitbucketserver`
- [CircleCI](https://circleci.com/docs/1.0/configuration/#notify) - `/circleci`
- [Codacy](https://support.codacy.com/hc/en-us/articles/207280359-WebHook-Notifications) - `/codacy`
- [Confluence](https://developer.atlassian.com/cloud/confluence/modules/webhook/) - `/confluence`
- [Dockerhub](https://docs.docker.com/docker-hub/webhooks) - `/dockerhub`
- [GitLab](https://gitlab.com/help/user/project/integrations/webhooks) - `/gitlab`
- [Heroku](https://devcenter.heroku.com/articles/deploy-hooks#http-post-hook) - `/heroku`
- [Instana](https://www.instana.com/docs/ecosystem/webhook/) - `/instana`
- [Jenkins](https://plugins.jenkins.io/notification) - `/jenkins` (requires the [notification plugin](https://wiki.jenkins.io/display/JENKINS/Notification+Plugin))
- [Jira](https://developer.atlassian.com/server/jira/platform/webhooks/) - `/jira`
- [NewRelic](https://docs.newrelic.com/docs/alerts/new-relic-alerts/managing-notification-channels/customize-your-webhook-payload) - `/newrelic`
- [Patreon](https://www.patreon.com/platform/documentation/webhooks) - `/patreon`
- [Pingdom](https://www.pingdom.com/resources/webhooks) - `/pingdom`
- [Rollbar](https://docs.rollbar.com/docs/webhooks) - `/rollbar`
- [Travis](https://docs.travis-ci.com/user/notifications/#Webhooks-Delivery-Format) - `/travis`
- [Trello](https://developers.trello.com/apis/webhooks) - `/trello`
- [Unity Cloud](https://build-api.cloud.unity3d.com/docs/1.0.0/index.html#operation-webhooks-intro) - `/unity`
- [Uptime Robot](https://blog.uptimerobot.com/web-hook-alert-contacts-new-feature/) - `/uptimerobot`
- [VSTS](https://docs.microsoft.com/en-us/vsts/service-hooks/events#) - `/vsts`

## Deploying

- [Docker](docs/docker)
- [Google Cloud](docs/gcloud)

## License

skyhook is available under the MIT license. See the LICENSE file for more info.

\ ゜ o ゜)ノ
