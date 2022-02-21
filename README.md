# newman_postman

1. #install dependencies
npm i
2. #run tests
newman run 'three.postman_collection.json' --environment 'environment.json'
3. #run tests + html reporter
newman run 'three.postman_collection.json' --environment 'environment.json' -r htmlextra