# graphql-export

This is a teeny tiny program that helps to export your graphql queries from the server to insomnia graphql requests

## Requirements
Yarn package manager

NodeJS

## Quick Use

```
yarn global add graphql-export

// For postman exports
graphql-export -u http://my-graph-ql-server-root -f postman

//For insomnia exports
graphql-export -u http://my-graph-ql-server-root -f insomnia
```

After running the command, an `export.json` file is generated which you can then import into insomnia api client
