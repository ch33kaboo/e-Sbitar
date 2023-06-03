# e-Sbitar Back-end

_ACSI Uni project back-end written in Java._

## Get Started

In order to start the server, navigate to `src` directory and run

```
javac SimpleHttpServer.java
java SimpleHttpServer
```

## API Documentation

- **POST /user** : to add a user to the platform, the request body must have these fields: `name`, `family_name`, `email`, `password`, `type`. the `type` field must be `patient` or `doctor`.
- **GET /user** : returns array of all users in the platform.
