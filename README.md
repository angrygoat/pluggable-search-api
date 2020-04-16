# pluggable-search-api
API for pluggable search capability. This defines a REST API for a search plugin.

The search plugin is a bridge between Metalnx and other interfaces/API to integrate various
search technology. 

A search plugin generally provides the following facilities:

* Advertise a set of search 'schema'. These can be thought of as support for search by a specific personna for a specific purpose.

* Advertise searchable attributes, type information, and saerch help tips

* Accept search requests (initially in free text 'google-like' search queries) and act as a bridge between simplified 
queries and some underlying search technology

* Marshal search results into standard views, starting with a standard search result and looking to add tabular and 
file listing type search results


