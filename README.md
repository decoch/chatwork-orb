# Chatwork Orb

Easily integrate custom Chatwork notifications into your CircleCI projects. Create custom alert messages for any job or receive status updates.

## Usage

Example config:

```yml
version: 2.1

orbs:
  line: decoch/chatwork

jobs:
  build:
    docker:
      - image: <docker image>
    steps:
      - chatwork/notify
```

