# Sätze

A personal reference tool to aid in learning and speaking German.

Short, memorable sentences exemplify the use of certain words. These sentences are stored as Markdown in a text file, which is parsed and rendered as HTML on page load.

## Search functionality
The Search functionality is primitive. On rendering, the sentences are converted to a “searchable string” - first converted to lowercase and then normalised to basic characters - which is stored as a data attribute and searched instead of the actual sentence. This means that capital letters, umlauts etc match without being typed. It goes without saying that this can and should be improved.
