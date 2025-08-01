## REST API maximum transfer

use HTTP GET method to fetch information from a database of patient medical records by quering `https://jsonmock.hackerrank.com/api/transactions`. The query results are paginated and can be accessed by appending `?page={num}` to the query string. where `{num}` in the page number.

Your task is to retrive and process the medical records according to specific criteria, handling the pagination properly and processing all avaialable records.

The response from the API is a JSON with the following give fields
- page: The current page
- per_page: the maximum number of the results per page
- total: The total number of records
- total_pages: The total number of pages to query to get all results

#### Problem:
```
function getMaximumTransfer(name, city){
   // Code here
}

Input: getMaximumTransfer("Bob Martin", "Bourg")
Output: [$3,717.84, $3,568.55]
```

#### Explanation:
```
Filtered out all the data which is have name of "Bob Martin" and city of "Bourg". The, Return the data max credit and debit amount.
```

`Note: Format curreny without using third party library` 




