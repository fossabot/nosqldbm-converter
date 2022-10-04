# nosqldbm-converter
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fvovikhangcdv%2Fnosqldbm-converter.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fvovikhangcdv%2Fnosqldbm-converter?ref=badge_shield)


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

## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fvovikhangcdv%2Fnosqldbm-converter.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fvovikhangcdv%2Fnosqldbm-converter?ref=badge_large)