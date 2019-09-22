# Podcast feed XSL template
<img align="right" width="350" src="https://i.imgur.com/n4AiKPF.png">
A template to display your feed as a HTML page
Designed primarily for podcasts feeds as it is expecting enclosures etc

## What it does

Display your feed as a one-page website with channel and item images

# What it uses
- channel
  - generator
  - title
  - itunes:subtitle
  - image
  - description
  - itunes:author
  - link
  - copyright
  
- item
  - title
  - link
  - description
  - itunes:image
  - itunes:author
  - enclosure url
  - enclosure lenght (file size)
  - itunes:duration
  - pubDate

## Instructions

- Donwload and host the template.xsl file somewhere on your webserver (publicly available of course)
- add `<?xml-stylesheet type="text/xsl" href="/path/to/your/template.xls" ?>` at the beggining of your XML feed just before `<channel>`, for example
- check your feed address, you should see a beautiful webpage like the one displayed here


## Troubleshooting

If nothing is displayed check your feed for characters like "&" for example

If things are missing, check your feed, it may not be present

