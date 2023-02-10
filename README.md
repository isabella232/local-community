# InnerSource Community Toolkit

When you are starting an InnerSource Community, you will need a toolkit to get your community off the ground quickly.
This is true no matter whether your community is a company-internal activity, a regional community, or a specific business-to-business sharing group.

Luckily this toolkit by the [InnerSource Commons](https://innersourcecommons.org) is just what you need to get your InnerSource community started. :)

You can use the next steps as a guidance to start a new local community:
* Announce the launch of your new community at the [#local-community Slack channel](https://innersourcecommons.slack.com/archives/C046MD5R5RT), and opening a pull request with the details of your local community  at [InnerSourceCommons/community-toolkit](https://github.com/InnerSourceCommons/community-toolkit/pulls).
* The local community should have a point of contact (one or more human beings).
* The communication channel should be clearly stated. It is recommended to use the InnerSource Commons Slack Workspace.
* Please use either the country (e.g., #spain-general) or the ISO country codes (e.g., #es-general) as part of your channel name. This will help to have a consistent way to discover local community Slack channels. 
* If you’re planning to have local meetings, please share the URL where those are managed (e.g., as in meetup.com).
* If you have produced translations, please share them as part of your local community work (e.g., those happening at the InnerSource Learning Path).
Other assets such as Twitter, Mastodon account, other social networks or tools you may use, please share them clearly in the local community page README file.

## Existing communities

* [Japan](./japan) - This is the first regional community that formed. Therefore much of the material in here was extracted from their work.
  * communication happens in Slack via [#jp-general](https://innersourcecommons.slack.com/archives/C03M546NR16)
  * with the tag "**Japan :jp:**" you can filter for their [issues](https://github.com/InnerSourceCommons/community-toolkit/labels/Japan%20%3Ajp%3A) and [discussions](https://github.com/InnerSourceCommons/community-toolkit/discussions?discussions_q=label%3A%22Japan+%3Ajp%3A%22)
  * their [Public Community Roadmap](https://github.com/orgs/InnerSourceCommons/projects/1) shows their plans for the coming quarters
* [Brazil](./brazil) - You find them in [#innersource-brazil](https://innersourcecommons.slack.com/archives/C03JP108XGE). Their directory in here was just created.
* [Thailand](./thailand) - Their directory in here was just created.
* [France](./france) - This local community is alive since January 2023
  * communication happens in Slack via [#fr-general](https://innersourcecommons.slack.com/archives/C04HJ3KPR19)

## How to create your community directory

Building on the structure of the [international](./international) directory is a good starting point.
You can customize the directory structure, but try to keep the base as close as possible so that other communities can easily refer to it.

The following commands may be helpful:

```sh
rsync -avz --include "*/" --exclude "*" international/ <YOUR_COMMUNITY_NAME>
find <YOUR_COMMUNITY_NAME>/ | xargs -I BASEPATH touch BASEPATH/.keep
```

## Questions?

This toolkit is really new!

Please contact us in [#local-community](https://innersourcecommons.slack.com/archives/C046MD5R5RT) in [Slack](https://innersourcecommons-inviter.herokuapp.com) with any questions.
