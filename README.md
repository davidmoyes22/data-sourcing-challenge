# data-sourcing-challenge
- "You've been tasked to prepare some data for a recommendation system to help people find movie reviews and related movies. You will extract data from two different sources: The New York Times API and The Movie Database, then merge the data together. The text extracted from these APIs can later be used with natural language processing methods."
## Code Considerations
- The code below was a first attempt to structure the nyt_url. The tutor helped me change the order and concatonate both lines.
```nyt_url = (
    f"{url}fq={filter_query}&sort={sort}&fl={field_list}&"
    f"begin_date={begin_date}&end_date={end_date}&api-key={nyt_api_key}"
)
```
- The tutor helped me apply a lmbda function to remove unicode characters.
- The tutor also helped me structure the movie_id_url by hard-coding the base URL instead of passing it in as a variable.
- Lastly, the tutor helped me to Merge the dataframe on the title.
