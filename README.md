# Firebase Quickstarts for Node.js

A collection of quickstart samples demonstrating the Firebase APIs using the Node.js Admin SDK. For more information, see https://firebase.google.com.

## Product Quickstarts

These quickstarts show you how to use Firebase products from your Node.js server:

* [auth-sessions](auth-sessions/README.md) - demonstrates how to use Firebase `httpOnly` session cookies with the Firebase Admin SDK session management API.
* [config](config/README.md) - demonstrates retrieving and updating the Firebase Remote Config template.
* [database](database/README.md) - demonstrates how to connect to and use the Firebase Realtime Database using Node.js through a simple social blogging app.
* [messaging](messaging/README.md) - demonstrates sending FCM notification messages to a topic using the Node.js Admin SDK.
* [machine-learning](machine-learning/README.md) - demonstrates how to manage your hosted ML models.

## Testing Quickstarts

The testing quickstarts previously available in this repository have
moved to a new location:

https://github.com/firebase/quickstart-testing
https://smooth80.github.io/quickstart-testing/
- name: Cache
  uses: actions/cache@v2.1.6
  with:
    # A list of files, directories, and wildcard patterns to cache and restore
    path: 
    # An explicit key for restoring and saving the cache
    key: 
    # An ordered list of keys to use for restoring the cache if no cache hit occurred for key
    restore-keys: # optional
    # The chunk size used to split up large files during upload, in bytes
    upload-chunk-size: # optional

## How to make contributions?

Please read and follow the steps in the [CONTRIBUTING.md](CONTRIBUTING.md)

## License
See [LICENSE](LICENSE)
