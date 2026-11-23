# Search and query

Query dataset entries on *dserver* via command line.

[![asciicast](https://asciinema.org/a/660463.svg)](https://asciinema.org/a/660463)

This sample works with a [*dserver*](https://github.com/jic-dtool/dservercore) instance observing some testing s3 and smb storage endpoints.

Instead of using the CLI, you may as well

* browse the index of *dserver* on [demo.dtool.dev](https://demo.dtool.dev)
* use the [dtool-lookup-gui](https://github.com/jic-dtool/dtool-lookup-gui) to manipulate datasets and search the lookup server index
* use the Python [dtool-lookup-api](https://github.com/jic-dtool/dtool-lookup-api) to interact with the lookup server

For the automized re-ingestion of a dataset after metadata modification, dserver relies on S3 notifications send by the object storage backend and processed by the custom [dserver-notification-plugin](https://github.com/jic-dtool/dserver-notification-plugin).
