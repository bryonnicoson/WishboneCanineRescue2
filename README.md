# Wishbone Canine Rescue, Bloomington-Normal, IL
Android app to help place rescued dogs in permanent homes

**Author**: Bryon Nicoson [bryon.nicoson@gmail.com](mailto:bryon.nicoson@gmail.com)

**Last Revised**: 8 Aug 2016

**Background**: Fifth and final project for General Assembly Android Development Immersive course.  
During [previous project](https://github.com/bryonnicoson/WishboneCanineRescue) realized that [Petfinder](https://www.petfinder.com/developers/api-docs)
is using [the older Google Data API](https://developers.google.com/gdata/docs/json?csw=1), the parsing of which I did not have time to figure out
given the original project timeline, and so instead opted for a local database source.  Now I have a chance to finish that app properly.  I want to deliver
a functional application to help this rescue.

**Goals**: Develop, deliver, and publish a robust, "finished" product.

**Research questions**: 
* How to parse Petfinder's Google Data API JSON to POJO
* If cannot parse JSON, how to parse Petfinder's Google Data API XML to POJO
* How to best handle multiple devices, portrait & landscape layouts
* How to best handle errors (Internet, API unavailable) - local sql cache for API?
* What communication functionality should I add (email to wbcr?)

**Methodology**: Over the course of two weeks...

1. Figure out Petfinder Google Data API JSON -> POJO || XML -> POJO
2. Model API Data to Classes
3. Refactor List & Detail View Activities & XML from previous project 
4. Add data caching & error handling
5. Add contact method / adoption application - Formsite API?  
6. Add firebase for notification of upcoming WBCR events?
7. Add PayPal payment functionality?

**Participants**: Target audience for this app are three groups:

1. Wishbone Canine Rescue stakeholders (staff, volunteers, and fosters)
2. People interested in rescuing a dog
3. My potential future employers :)

**Schedule**:  

* **Start Date**: 8 Aug 2016
* **Due Date**: 19 Aug 2016

**Script (Hypothetical participant questions)**:

1. What should I know about a specific breed of dog before I decide to adopt one?
2. Does a particular dog have any special needs?
3. When/where can I come to see a dog?
4. What will happen to this app if/when Petfinder updates their API? (Is Bryon going to maintain support for this app?)
5. Whom should I contact if I have additional questions?
