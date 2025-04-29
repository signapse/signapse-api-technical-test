**Preparation**

Please come prepared ready to start building the application – your preferred programming
environment, IDE and language of choice.

**The test**

1. Create an API with the endpoint `/ordered-numbers` ;
2. The endpoint should consume data from a a third-party API:
[http://technical-test.api.production.signapsesolutions.com](http://technical-test.api.production.singapsesolutions.com)
This endpoint returns an array of random integers and UUID’s
The endpoint is protected with Bearer Authorisation tokens, you will be sent the token in advance of the test. 
3. The order and type of data returned from the third-party does not match the requirements of our end-users.
Only integers must be returned (strings should be filtered out) from the `/ordered- numbers` endpoint and they should be sorted in ascending order, with odd numbers coming before even numbers.
For example: `[1, 5, 11, 4, 10, 22]`
