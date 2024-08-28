Make Objects Simple; Move Out 3rd-Party API Calls
#################################################

:status: draft
:date: 2024-07-16 10:55:16
:tags: software engineering, architecture
:slug: make-objects-simple
:summary: When creating and object that uses data from an API, pass in the data supplied from the 
          API versus making the API calls in the class.

Ran into a problem at work today where an API that I use to get data changed its API. Now this is all
internal and so changes are more likely to happen than a publicly visible API. I work next to the
guy that wrote the code, so it our communication is very good.

