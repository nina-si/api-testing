# API Testing

This repository contains an example of API tests with Postman Collection Runner and dataset.

For more details, please [follow this link](https://cottony-bosworth-fff.notion.site/API-Testing-Challenge-568fe8bc8ef7405a899fc6036f6cc122?pvs=4).

## To run tests:

1. Clone repository:  
   `git clone https://github.com/nina-si/api-testing.git`

2. Move to project folder:  
   `cd api-testing`

3. Install dependencies:  
   `npm install -g json-server`

4. Start json-server in a watch mode:  
   `json-server --watch db.json`

5. Import a collection from this folder (`Comments API Testing.postman_collection.json`) into Postman:

   ![Collection import](./assets/import.jpg)

6. In Postman, choose to run collection manually:

   ![Test run](./assets/run.jpg)

7. In _Data > Select file_ choose file `dataset.json` from this folder:

   ![Dataset select](./assets/data.jpg)

8. Click _Run Comments API Testing_:

   ![Run button](./assets/button.jpg)

You can change dataset or play with requests.
Don't forget to stop json-server after test run.

## Test results

After test run, results can be seen:

![tests summary](./assets/tests_summary.jpg)

![tests reporting](./assets/tests_reporting.jpg)
