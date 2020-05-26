## Introduction to
![MEI logo](https://raw.githubusercontent.com/music-encoding/music-encoding.github.io/master/pix/meilogo-inverted.png)

*facilitated by*
*[Benjamin W. Bohl](https://bwbohl.github.io/)*
---



### Resources for this workshop

* Technology Plan
  
  https://music-encoding.org/conference/2020/technology-plan/

* [Slack channel](https://music-encoding.slack.com/join/shared_invite/zt-4zgx6zbq-2jEjDiUT7ym3dygTaY8C0g#/)  `#workshops-mec2020-mei`

* Slides

  https://bwbohl.github.io/introduction-to-mei/




## What we're up to today

1. About the Music Encoding Initiative 
2. About music encoding 
3. XML basics
4. First steps with MEI 



---
## Music Encoding Initiative

* unformalized organization
* open
* free


Note: unformalized nevertheless we have rules, By-laws, elections 

Note: open to anyone, any discipline, music lovers, musicologists, technologists

Note: open source, free




## MEI – Resources

* Website https://music-encoding.org  
* GitHub https://github.com/music-encoding
* Mailinglist mei-l@lists.uni-paderborn.de
  * subscribe at: https://lists.uni-paderborn.de/mailman/listinfo/mei-l
* 
[Slack channel](https://music-encoding.slack.com/join/shared_invite/zt-4zgx6zbq-2jEjDiUT7ym3dygTaY8C0g#/)
* Twitter https://twitter.com/MusicEncoding
* Humanities Commons https://hcommons.org/groups/music-encoding-initiative/




## MEI – Goals

* open standard
* structured semantic and machine-readable representation of music




## Music Encoding

  > structured semantic and machine-readable representation of music


  > structured
  
* clear associations between elements


  > semantic
  
* analytical information
* modeled knowledge
  
  >»quarter-note«
  
  vs
  
  >»charcoal head with a stem«



## Domains  

logical domain

gestural domain

visual domain

analytical domain



## logical domain

>The logical domain is the basic musical content[…]

– 
[MEI Guidelines Introduction](https://music-encoding.org/guidelines/v4/content/introduction.html)



## gestural domain

> The gestural domain is comprised of any number of performances, each of which may specify how and when components of the logical domain is rendered in a specific performance […]
 
– 
[MEI Guidelines Introduction](https://music-encoding.org/guidelines/v4/content/introduction.html)



## visual domain

> The visual domain is comprised of any number of scores, each of which somehow specifies exactly how components of the logical domain is rendered visually in some particular printable (and/or displayable) edition

– 
[MEI Guidelines Introduction](https://music-encoding.org/guidelines/v4/content/introduction.html)


## analytical domain

>The analytical domain is comprised of any number of theoretical analyses and/or commentaries, each of which somehow specifies opinions, exegeses, etc. 

– 
[MEI Guidelines Introduction](https://music-encoding.org/guidelines/v4/content/introduction.html)



## XML basics

* nested tree


  ### elements

  ```<elementName />```


### attributes

  ```<elementName attributeName="value" />``` 



## XML basics

* structural validaton with schema file
* semantic content validation with schematron




## XML basics

* MEI defines a schema in its own namespace
* structural frame for XML data

>https://music-encoding.org/resources/schemas.html



## XML basics – hands on

* https://music-encoding.org/tutorials/100-structure.html




## MEI basics

* notes
* rests
* chords


## MEI basics – notes

https://music-encoding.org/tutorials/101-quickstart.html


## MEI basics – rests

https://music-encoding.org/tutorials/104-rests.html


## MEI basics – chords

https://music-encoding.org/tutorials/103-chords.html




## Realworld example

* Beethoven Op. 98 No. 1

  http://dfg-viewer.de/show/cache.off?tx_dlf%5Bpage%5D=5&tx_dlf%5Bid%5D=http%3A%2F%2F194.8.210.170%2Fdbh-archiv%2Fmods%3Fscanid%3D3073&tx_dlf%5Bdouble%5D=0&cHash=95e28b6c840829ab49faaddb15d4e7c6