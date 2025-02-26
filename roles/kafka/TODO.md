# Missing Features

The role is right now tailored towards a static configuration of Kafka.
The following features are missing:

## Dynamic Quorum Voters

See https://kafka.apache.org/39/documentation.html#kraft_reconfig

- Each controller would need it's own unique UUID
- The invocation of the format-storage.sh script would need to be adjusted

## SSL

- SSL is not yet supported

