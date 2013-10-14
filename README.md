query
=====

Once compiled, this code gives you 3 scripts:

 * webdevdata-query.sh
 * webdevdata-stats-HTML-attributes.sh
 * webdevdata-stats-HTML-tags.sh

The first one gives you the URLs (I mean files of WebDevData) matching a CSS-like query you pass as an argument. For instance all URLs having select tags with an onchange attribute. (We use such queries to fulfill KBAccess, a collaborative database of accessibility examples)

The second and third ones gives you, for each attributes and for each tags, their occurence in WebDevData.
