# notion-search-for-alfred

An Alfred 5 workflow to search for Notion pages.

# How to Use

1. [Generate an integration key](https://www.notion.so/my-integrations/) for your workspace. [See instructions on configuration below](#generating-an-integration-key).
2. Copy the internal integration key.
3. Grant the integration access to pages that you want to appear in search. See [this help document](https://www.notion.so/help/add-and-manage-connections-with-the-api#add-connections-to-pages) for more information.
4. Download and install the workflow.
5. Paste your integration key when prompted by Alfred.
6. Search for pages by typing `ns [search query]`. Select a search result to open it, or use `⌘+select` to copy the page link.

# Generating an Integration Key

When creating a new integration, configure the capabilities section as follows:

<img width="1019" alt="Name and integration type (internal integration)" src="https://user-images.githubusercontent.com/34608561/196333666-f1842090-e794-4cb4-8bcf-f892b41516af.png">

<img width="1019" alt="Integration permissions (read only, no user information)" src="https://user-images.githubusercontent.com/34608561/196333693-ca336de1-27fc-497b-8945-c626e7c433ac.png">

Once configured, press Submit to create your integration.
