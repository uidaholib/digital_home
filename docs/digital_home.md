# digital_home notes

## digital_collections spreadsheet

- what goes in here vs CDIL spreadsheet
- standards
- project management info vs collection metadata

### fields 

- objectid = the stub of the collection.
- title = title, usually taken from the _config.yml.
- tagline = subtitle, usually taken from the _config.yml.
- description = description, usually taken from the _config.yml.
- url = full link to the collection home page.
- last_update = last time collection was updated, code or metadata.
- created = when it was first published.
- item_count = total number of items. This should only be a number, no qualifiers or notes!
- featured = true or blank. collections given "true" will used to populate features on the home page. These should be curated and changed occasionally.
- status = published or hidden. "hidden" collections will not appear in the browse page--however, unpublished collections should not be in the spreadsheet!
- search_index = true or blank/false. collections with true will be included in the search index (MUST have a valid search.json file) and aggregations.
- categories = broad content subject categories, creating large topical groupings of collections. Separated by semicolon. these should generally be from our controlled vocab. Used on collections browse.
- type = collection groups. Used on collections browse.
- mediatype = general item file types featured/contained in the collection. these should be from a limited vocab. audio; documents; images; maps; newspapers; scores; videos. Used on collections browse.
- location = general location of the collection, multiple can be separated by semicolon (optional). Used on collections browse.
- latitude = lat for general location (optional). Used on collections map.
- longitude = long for general location (optional). Used on collections map.
- date_start = YYYY, earliest year in collection. Can found on home page. Used on collections timeline.
- date_end = YYYY, latest year in collection. Can found on home page. Used on collections timeline.
- notes = any extra notes about the collection, internal use. 
- featured_image = full url to full sized image representing the collection. Generally matched the featured_image in theme.yml.
- image_small = full url to small image representing the collection. 
- image_thumb = full url to thumb image representing the collection.
- image_alt_text = alt text describing the image.
- image_source = full link to the item page of the image if it is a collection item. 
- data_location = provide the full url to the "assets/data" folder of the collection (which should contain metadata.csv and search.json). If a collection does NOT have standard data, leave this field blank. For standard templates this will follow the pattern https://www.lib.uidaho.edu/digital/stub_name/assets/data
- repository_location = provide the full url to the repository on github including the branch if applicable (such as in the template collections). e.g. https://github.com/uidaholib/base-digital-collections-template/tree/1918flu
- cdmid = legacy CONTENTdm id of collection, kept for looking up broken links.
