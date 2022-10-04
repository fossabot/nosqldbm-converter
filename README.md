# nosqldbm-converter

Convert https://nosqldbm.ru/ JSON data to Moongose Schema.

# Getting started
1. Design your database on https://nosqldbm.ru/.
2. View JSON and Copy clipboard.
3. Save it as a file raw.json.
4. Load your schemas.

    ```js
    const nosqldbmConverter = require('nosqldbm-converter')
    const rawJSON = require('./raw.json');

    console.log(nosqldbmConverter(rawJSON));
    ```

# License