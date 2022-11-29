# Multiple JSON files to CSV
Someone [posted](https://www.linkedin.com/pulse/how-read-multiple-json-files-same-directory-merge-csv-notario-moral/) on LinkedIn a method to read multiple json files into a Pandas dataframe, then export as csv.

I felt there could be a slightly more elegant approach to this, hence this snippet. Without having a sample of their json data, I've built my own sets for testing purposes.

## Disclaimer for data used
JSON data has been generated using [json-generator](https://json-generator.com/), subsequently formatted to match the [example](https://json.org/example.html) from [json.org](https://www.json.org/json-en.html).