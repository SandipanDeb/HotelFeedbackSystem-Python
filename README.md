# Online Hotel Feedback System

The Online Hotel Feedback Application is designed to provide a mechanism where a hotel can collect feedback from guests who stayed in their properties. The hotel can then utilize the feedback to provide improved services to its customers. 

Once the guest checks out from the hotel, they receive a link to the feedback portal in their emails requesting feedback on their stay. Users can read & write text messages and optionally log-in with
their Google account. Messages are stored in App Engine (NoSQL)
High Replication Datastore (HRD) and retrieved using a strongly consistent (ancestor) query.

## Products
- [App Engine][1]

## Language
- [Python][2]

## APIs
- [NDB Datastore API][3]
- [Users API][4]

## Dependencies
- [webapp2][5]
- [jinja2][6]
- [Twitter Bootstrap][7]

[1]: https://developers.google.com/appengine
[2]: https://python.org
[3]: https://developers.google.com/appengine/docs/python/ndb/
[4]: https://developers.google.com/appengine/docs/python/users/
[5]: http://webapp-improved.appspot.com/
[6]: http://jinja.pocoo.org/docs/
[7]: http://twitter.github.com/bootstrap/
