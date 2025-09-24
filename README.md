# R-ALAB-308A.4.1

## Special Notes
The `main` branch uses axios and the `lab-fetch` branch uses fetch. Also, part 6 does not use the .total or .loaded properties because the data is sent in chunks, so the server doesn't provide the content length header. The progress bar's width is sent to 100% in the response interceptor to show that the request was handled.

## Displaying Cat Photos
At most 10 cat photos will be displayed for each breed. The options that can be selected are already filtered (there are no options without a cat photo). The photos shown are a random subset of 10, so not all photos shown will be the same or in the same order.