# ![LOGO](logo.png) domainsdb.info **flow**ground Connector

## Description

A generated **flow**ground connector for the domainsdb.info API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/domainsdb.info/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:15+03:00

## API Description

Registered domains search checks the lists of registered domains for names containing particular words/phrases/numbers or symbols. Technically it's just a GUI interface for domains-index.com database containing more than 260M of registered domains and 1000+ TLDS including newGTLDs. It's free to use and could be helpful domains/marketing research tool. Search results are limited to 50 results. You can have up to 100 results via API (link in footer) and full list by

## Authorization

Supported authorization schemes:
- API Key- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Search for registered domains

*Tags:* `search`

#### Input Parameters
* `query` - _required_ - Search query for registered domains for ex. facebook
* `tld` - _optional_ - Search area (cctld|gtld|all)

## License

**flow**ground :- Telekom iPaaS / domainsdb-info-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
