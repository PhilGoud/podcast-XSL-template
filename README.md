# podcast feed XSL template
A template to display your feed as a HTML page
Designed primarily for podcasts feeds as it is expecting enclosures etc

## What it does

Display your feed as a one-page website with channel and item images

## Instructions

- Store the template.xsl file somewhere on your server
- add <?xml-stylesheet type="text/xsl" href="/path/to/your/template.xls" ?> at the beggining of your XML feed
- check your feed address, you should see a beautiful webpage


## Troubleshooting

If nothing is displayed check your feed for characters like "&" for example

If things are missing, check your feed, it may not be present
