# TA-Zeek

Inspired by the Splunk built TA (Splunk Add-on for Zeek aka Bro). The "Bro" terminology and naming has been wiped out and updated to reflect Zeek thoughout the add-on with additional parsing.

Place this add-on onto your indexers and search head. 

This add-on contains no visualizations. Install SA-Zeek for dashboards and supporting searches.

The only configuration needed is to copy default\indexes.conf.spec to default\indexes.conf on indexers to create the indexes necessary. There is no need to do with with TA-Onion-Import as that add-on already ships with the correct indexes.conf
