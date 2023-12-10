# Wikipedia Data Scraping and Solr Indexing

This project involves scraping data from Wikipedia related to various topics and then indexing the collected data using Apache Solr.

## Scraping Requirements

### Topics and Subtopics
- **Health**: Common diseases, global health statistics, mental health trends…
- **Environment**: Global warming, endangered species, deforestation rates…
- **Technology**: Emerging technologies, AI advancements…
- **Economy**: Stock market performance, job markets, cryptocurrency trends…
- **Entertainment**: Music industry, popular cultural events, streaming platforms...
- **Sports**: Major sporting events, sports analytics...
- **Politics**: Elections, public policy analysis, international relations…
- **Education**: Literacy rates, online education trends, student loan data…
- **Travel**: Top tourist destinations, airline industry data, travel trends…
- **Food**: Crop yield statistics, global hunger, and food security…

### Data Collection
- Scrape a minimum of 500 unique documents for each topic.
- Ensure that not more than 5% of documents have a length less than 200 characters in the summary.
- Utilize the Wikipedia API with the suggested wrapper [wikipedia](https://pypi.org/project/wikipedia/).

### Code Organization
- Part 1: Data Scraping
  - Subpart 1: Define dictionaries for each topic.
  - Subpart 2: Implement functions for fetching main summaries and links summaries.
  - Subpart 3: Loop through topics, fetch main and link summaries, and organize data into dictionaries.
  - Subpart 4: Combine and export data for each topic to CSV files.

- Part 2: Indexing
  - Subpart 1: Introduction to Solr Terminologies and Schema.
  - Subpart 2: Preprocessing strategies for indexing.
  - Subpart 3: Configuration and experimentation with Solr schema.
  - Subpart 4: Preprocess data for indexing and submit to Solr.

## Usage
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the scraping script for data collection.
4. Configure Solr schema and preprocess collected data for indexing.
5. Submit the preprocessed data to Solr for indexing.

## Contributing
Feel free to contribute to improve the scraping logic, Solr configuration, or any other aspect of the project. Create a new branch for your contributions and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
