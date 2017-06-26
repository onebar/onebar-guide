Integrations guide
================

You can connect your data sources to OneBar by using the integrations manager. In the web version go to Settings -> Integrations. You can add and remove data sources from there. Currently available options are:

- **Github** - connect your github account and add private repositories. OneBar will index the code and install a webhook to lister for updates. PRs/Issues are currently not indexed.

- **Git** - add any public repo from github or any other git hosting. You can also index a private repo by adding a private key in advanced settings. Webhooks are not supported for plain git, so the updates are retrieved on schedule. Retrieval interval is configurable in advanced settings.

- **Confluence** - add the Confluence wiki. Adding Atlassian product integration is not as trivial as the Github or Google docs, but following the instructions in the wizard should work well. Confluence does not support webhooks, the content is updated on schedule.

- **JIRA** - index all your JIRA tickets by connecting JIRA. The integration process is similar to Confluence, just follow the instructions on screen. JIRA does support webhooks, so new content is received in real-time.

- **Google Docs** - connect your google drive account. Right now OneBar will only index Docs and Spreadsheets, indexing individual files will come later.

- **Slack** - slack integration is coming soon via a slack bot.
