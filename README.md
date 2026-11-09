# PermitSnag

Ask Claude about backcountry permits and campgrounds in the US, Canada, New Zealand and Australia. The PermitSnag connector looks up how a permit is issued, its season and published dates, and what PermitSnag's checks last recorded for your dates, with the time of the check. The skill tells Claude to state that age, to treat unknown dates as unknown, and to hand you to the official booking page. It can also set up an alert that tells you when a permit or campsite opens, list your alerts, and turn one off.

## Data

The plugin sends the permit or campground name and dates you ask about to api.permitsnag.com. Searching needs no account. Alerts need a PermitSnag account: the first time you ask for one, Claude asks you to sign in, and PermitSnag then receives the alerts you set up. If an alert needs a purchase, you pay on a checkout page; the plugin never charges a card. PermitSnag does not receive your conversation. Privacy policy: https://permitsnag.com/privacy

## More

Setup steps for other assistants and the public server contract: https://permitsnag.com/connect and https://permitsnag.com/developers

Licence: MIT. The licence covers the files in this repository (the skill text and the connector pointer). It does not cover the PermitSnag service or its data.
