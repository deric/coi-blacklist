# ČOI / CTIA blacklist

Entries in this list were currated by The Czech Trade Inspection Authority (CTIA), which is an administrative government institution which falls under the jurisdiction of the Ministry of Industry and Trade of the Czech Republic.

The list contains mostly websites on `.cz` domain that are considered to be harmful.

## [Pi-hole](https://pi-hole.net/)


1. In admin go to `Group Management > Adlists` and add this URI:
```
https://raw.githubusercontent.com/deric/coi-blacklist/main/hosts
```
2. Run `pihole -g` in order to update blacklists.


## Related projects

 - [Chrome addon](https://chrome.google.com/webstore/detail/rizikov%C3%A9-weby/iddkbojnnljflgkjchlpjlhpfhhbeefk?hl=cs)
 - [Firefox addon](https://addons.mozilla.org/cs/firefox/addon/rizikoveweby/)

## Disclaimer

This list is not officially managed CTIA, it might be out of sync.


## License

[Open data license](https://www.coi.cz/pro-spotrebitele/otevrena-data/licence-otevrenych-dat/)

