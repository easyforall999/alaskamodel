## Assumptions
 - The data model here is created by taking the assumption that all flight journeys do not have a layover to 
 remove complexities
 - Of the various flights populated after a search, user has the option to choose both onward and return flights individually. User also has the option to choose the cabin types for each of the selected flights. 
 - The Key Status_code indicates whether the search query was a success or an error. A search without results gives rise to an error code (in the example given - 1580)
 - Invoices are only created for the sessions which lead to a conversation, thereby, just search sessions without any conversion will have a null in the invoice section
 - The popularity metric for a given flight is not a universal metric but it changes based on the type of user trying to search for a certain flight, ie., dynamic wrt to the user profiles 
   