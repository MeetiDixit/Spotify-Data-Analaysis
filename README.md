# Spotify-Data-Analaysis

### Dataset Link
https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs

The dataset is sourced from Kaggle and comprises approximately 50 million tuples. The project attempted to represent it in a relational database format. The dataset includes detailed information about various attributes of songs on Spotify, including Artists, Genres, Track Length, etc., making it suitable for performing meaningful queries and extracting valuable insights.

Phase 2: Several interesting SQL queries have been developed to extract insights from the relational model. Additionally, indexes have been proposed to optimize query execution performance. Timings for query execution with and without indexes are reported, demonstrating the impact of indexing on query efficiency.

Phase 3: This phase focuses on pre-processing the dataset to implement itemset mining and discover existing association rules. The model is tested with document based scripting to further analyze if the itemset mining process is fit for the relational based model or a documnet based one (NoSQL). After analyzes and time tracking of each lattice creation, the relational model is concluded as the efficient one, mainly due to its emphasis on the structured data.
