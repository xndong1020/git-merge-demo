## This is a great project

```js
const AWS = require('aws-sdk')


const { _id } = event
const dbClinet = new AWS.dynamodb.documentClient()

const param = {
  Table: 'Nicole.users',
  Key: { _id }
}
```

### TODO: code implementation
