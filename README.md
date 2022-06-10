# How To Create A REST API With JSON Server
<a href="https://medium.com/codingthesmartway-com-blog/create-a-rest-api-with-json-server-36da8680136d">Full article</a>

## Installing JSON Server 
`$ npm install -g json-server`

## Writing a JSON File
`{
  "employees": [
    {
      "id": 1,
      "first_name": "Sebastian",
      "last_name": "Eschweiler",
      "email": "sebastian@codingthesmartway.com"
    },
    {
      "id": 2,
      "first_name": "Steve",
      "last_name": "Palmer",
      "email": "steve@codingthesmartway.com"
    },
    {
      "id": 3,
      "first_name": "Ann",
      "last_name": "Smith",
      "email": "ann@codingthesmartway.com"
    }
  ]
}`

## Run the Server
`$ json-server --watch db.json`