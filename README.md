# Bookshelf catalog

[Open the searchable catalog](https://ehsanbz.github.io/bookshelf-catalog/)

500 catalog entries, updated 2026-10-14. Search, sort, filter by subject, topic, language and format, and export matching rows as CSV.

Only the catalog interface and metadata are stored here. No books or book archives are included. Book links open Google Drive and retain their existing access permissions. The catalog metadata is public.

## Files

- `index.html`: standalone interface with embedded catalog data.
- `book_catalog.csv`: Excel-compatible UTF-8 catalog.
- `.nojekyll`: serves the files directly on GitHub Pages.

## Updating

Add books to the Drive Inbox, then refresh the catalog and replace both `index.html` and `book_catalog.csv` together in this repository. Preserve existing IDs and metadata. GitHub Pages automatically publishes commits to the configured main branch. A scheduled hourly check categorizes new Drive Inbox books, updates the CSV and HTML together, and publishes the catalog. Books stay on Drive. The local computer and Codex desktop app must be running for local processing.
