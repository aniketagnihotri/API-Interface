# API-Interface

A Spring interface written to send GET requests to multiple APIs.

Visit https://rest-api-client-test.herokuapp.com/ as a starting URL.

The Yelp package under src/main includes three classes which send GET requests to Yelp's Fusion API for a certain number of user-specified local business results in a city or area, which are returned and published to a URL in a prettified JSON format. These parameters are defined by the user and published on the URL /yelp/{city}/{result_limit} or at /yelp. 

Other API interface code is also written under src/main, sending requests to ICNDb.com's API for Chuck Norris jokes. Any numbered joke can be retreived from this API at the URL /joke/{joke_number}, and is similarly returned and published to the URL in a prettified JSON format.
