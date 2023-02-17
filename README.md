# ApregoarProject
![apregoar_full](https://user-images.githubusercontent.com/83875010/218793627-a94d123b-c8ac-4bca-bfa4-f411e69edf6c.png)

GEODATABASE AND MAPPING TOOLS for digital news, community, and geointelligence

## Want to share your perspective on spatial news?
Please leave your contact information here if you're willing to partcipate in a short interview! https://forms.gle/e74TjjDhnMXzmEZT9

## The situation
LOCALIZING is critical for people to understand their surroundings, and plays a large role in understanding events and their implications over time and space.

THE NEWS is a repository of human activity, rife with rich descriptions of WHO, WHAT, WHEN, WHERE, HOW, and WHY things happen.

WE LACK the mans to leverage this information for better informed citizens, nuanced monitoring of news coverage, efficient city management, improved research methods, or informed GeoINT operations.

## The problem
Publishers, governments and activism groups want to communicate information clearly to their readers to improve understanding and engagement... but interactive spatial data visualizations aren't easy for journalists to create or manage.

City users want to understand what is happening in their environment... but most articles don't include context maps, and the content of digital journals cannot yet be searched spatially or temporally.

Researchers, city managers, and GeoInt Operations want to be able to search and ingest high quality information from the news... but they cannot access these resources, nor do they have access to "briefings" on an area.

## The industry

Though the news industry is struggling to establish viable business models in the digital age, online news and social media are continuing to grow and displace other mediums.

A lack of clear and efficient transmission of information leads to misinformed citizens and city managers. Digital media agencies know the value of data visualizations for engaging readers.

Time, processing, and human resources are extended to scrape news and social media sites to extract event data for smart city and GeoINT applications.

## The solution
![apregoar_stakeholders](https://user-images.githubusercontent.com/83875010/218802635-1c3c8776-dd86-4a14-9b44-0507ea4b8a26.png)

Stakeholders include:
- Local news journals, national news agencies, community groups, and other content creators
- Local government groups such as juntas de freguesia, and câmaras municipais and other managers
- Citizens and city users
- Researchers, smarty cities, and geointelligence operators

### Publishing
![publishing](https://user-images.githubusercontent.com/83875010/218809910-abe23f23-7cbf-4b63-86be-be44cf489b34.png)

CROWDSOURCING web and mobile apps allow anyone to associate instances to published news stories as community contributors.

COMMERCIAL back office plugins allow journalists to associate instances to the articles as they publish as verified contributors.

In both tools, users can define place by choosing existing places from the built-in gazetteers (spatial libraries) and connections (ex: open street map). Eventually, a tool suggesting places based on the place names identified in the text can be confirmed or ignored by the user. Users can also upload their own spatial definitions or connect to other public resources. If no existing  places (or set of places) match where an event happened, users may design their own areas by drawing the locations on a map within the tools.

### Geospatial database
![apreogar_model](https://user-images.githubusercontent.com/83875010/218804327-916761c9-f2c1-4699-826d-aef62c970c28.png)

A story represents one digital article. Each story may have multiple "instances" (spatial definition). Each instance will be of type "event" (with a temporal component) or "contextual" (with no time definition).

Places can be already existing places (such as administrative boundaries, points of interest, etc.), or custom areas. Each instance must have at least one place, but may include multiple places and of different types.

The data represented in the "GEONOTICIAS" query summarizes all of the relevant information from the relational geo database about each story or instance.

### Article contextualization
An inline map and discovery view  allow readers to contextualize stories in space, and support "see more nearby" engagement with the original news source.
![publishing](https://user-images.githubusercontent.com/83875010/218810929-061acf1c-f4fa-4136-a667-4d3efedfd27d.png)

### Explore portals
A GENERAL explore portal allows users to peruse, explore, and filter all stories added via the Apregoar GeoNews toolset, allowing refinement of relevant news by thematic, spatial, and temporal attributes. Upon discovery, user may read a selected article by following the link to the original source.
![explore](https://user-images.githubusercontent.com/83875010/218811836-40787abc-a6a8-40f2-bdef-b5cb35f3a094.png)

A WHITELABELED explore portal is embedded into a journal's site and permits perusing of only that organization's news content.
![whitelabel_explore](https://user-images.githubusercontent.com/83875010/218811816-33aceefd-3ac6-4770-bfa4-0f85c95b7607.png)

### Dashboarding tools
Users at any level may save filtering preferences, identify areas of interest, create reading lists, and share briefings with other users. Results may be connected to directly via API, or exported as preferred.

## Potential impact
GEO-CONTEXTUALIZATION
 - Informed, active and engaged citizens with improved spatial awareness to empower communities and affect public planning
 - Improve user engagement directly with digital news

GROUND TRUTH GEONEWS
- Repository of news coverage with geospatial/temporal dimensions
- Physical distributions of public sentiment
- Dynamic, high quality input for smart cities and geointelligence operations

PROGRESSIVE GAZETTEER
- Record of current and developing spatiality
- Reusable within the platform

OPEN, MODULAR TOOLS
- A "swiss army knife" of data and information tools
- Additional connections for smart city, citizen participation, research, or commercial applications

## The overview
COMPREHENSIVE: Allows association of multiple spatial/temporal events and/or contextual places per article.

REPRESENTATIVE: Nothing happens in zero dimensions. Instead of points, the tools allow the association of multi-polygons to represent places.

HIGH CONFIDENCE: Because the instances are tagged by contributor type, verified content data is much higher quality than the geoparsed results from scraped articles.

DYNAMIC: Connections to the data are available as each article is published, negating lag time for integration into other applications. Likewise, publisher revisions are reflected automatically and immediately.

## Collaborate
We're looking for stakeholders to help guide the next stages of development, and team members to realize the next steps.

Get in touch if you'd like to learn more!

## Contact
Callie Wentling

ApregoarProject@gmail.com

![apregoar_mini](https://user-images.githubusercontent.com/83875010/218809667-0812b06b-bc92-41e8-9009-bf258a772a3e.png)
