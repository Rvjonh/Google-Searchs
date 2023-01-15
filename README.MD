# GOOGLE ADVANCED SEARCHS

Repository to describe a quick reminder about google searchs, shows topics to improve searchs in google and link to utilities for more searchs.

## Google Advanced UI Search

Google advanced search allows you look for information with multiple filters and/or condicions: [Google Advanced Search](https://www.google.com/advanced_search). Allows you to use operators with a UI.

## Look for through tools

* [GOOGLE LEANS](https://lens.google/intl/es-419/#shopping): Look for through photos.

* [GOOGLE SCHOOLS OR ACADEMIC](https://scholar.google.com/schhp?hl=es&as_sdt=0,5): Look for academic files about your search

## SEARCH OPERATORS

| Operator | Description | Example |
|----------|-------------|---------|
|`"[topic]"`| Look for specific topic | "flutter" tutorial |
|`-[topic]`| Denied, exclude items from that mark | web tutorial -jquery |
|`[topic] * [...topics]`| As WILDCARD, used to add elements that can be related to the topic | linus * linux (\* be sustiuided with "Torvalds") |
|`[topic1] AROUND(n) [topic2]`| It's a proximity search. Find pages containing two words or phrases X words away from each other | web AROUND(3) react|

### DATE OPERATORS

| Operator | Description | Example |
|----------|-------------|---------|
| `[topic] BEFORE:YYYY-MM-DD`| Returns searchs before that date | Microsoft BEFORE:2020-03-03 |
| `[topic] AFTER:YYYY-MM-DD`| Returns searchs after that date | Miss universe AFTER:2023-01-10 |
| `[topic] YYYY..YYYY`| Range: Returns searchs between those date | Economy 2007..2009 |

### SOURCE OPERATORS

| Operator | Description | Example |
|----------|-------------|---------|
| `[topic] SITE:[url]` | Returns links from that source or domain | React SITE:freecodecamp.org |
| `[topic] FILETYPE:[file_extension ej. '.pdf']` | Looks for files with the extension | mindset FILETYPE:.pdf |
| `[topic] LOC:[location]` | Returns searchs from that location | software engineer LOC:"san cristobal" |
| `[topic] blogurl:[name of blog]` | Returns blogs from that source or domain | software engineer blogurl:dev.io |
| `[topic] cache:[url]` | Return cached websites in case they're down | React SITE:freecodecamp.org |

### BOOLEAN OPERATORS

| Operator | Description | Example |
|----------|-------------|---------|
| `[TOPIC] AND [TOPIC]` | Returns both searchs together | Web AND Javascript |
| `[TOPIC] OR [TOPIC]` | Returns one or both topics | Angular OR React |

### IN-(URL/TITLE/TEXT/ANCHORS)

| Operator | Description |
|----------|-------------|
| `allinurl:[url] [topic]` | Looks all link from a url |
| `intitle:[title] [topic]` | Looks all titles about a topic |
| `intext:[text] [topic]` | Looks all texts about a topic |
| `inanchors:[anchor] [topic]` | Looks all anchors about a topic |

### UTILITY OPERATORS

| Operator | Description |
|----------|-------------|
| `define:[topic]` | Returns the definition of the search |
| `related:[topic]` | Returns links related to the topic |
| `what's my ip` | Returns your ip |
| `[unit] in [unit]` | Returns the change between both units |
| `weather:[location]` | Show weather that place |
| `map:[location]` | Shows the map of that place |
| `movie:[movie]` | Returns all data for that movie |
| `calculator` | Shows a calculator |
| `stocks:[stock id]` | Returns the stock mark |
| `roll a dice` | Returns multiple times a dice or mix a combination |
