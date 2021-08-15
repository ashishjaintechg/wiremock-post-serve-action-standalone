# wiremock-post-serve-action-standalone
These artifacts will run the post serve action using webhooks extensions


java -jar wiremock-jre8-standalone-2.29.1.jar --port 3333 --verbose --extensions org.wiremock.webhooks.Webhooks

http://localhost:3333/api/users


[
  {
    "id": 1,
    "first_name": "Ashish",
    "last_name": "Jain",
    "age": 35
  },
  {
    "id": 2,
    "first_name": "Chirag",
    "last_name": "Jain",
    "age": 28
  }
]

Additionally 
This will call coupon service get method as a webhook request.

