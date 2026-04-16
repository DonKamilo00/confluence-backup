# Confluence Backup

**Source:** https://jordanjamesxvi.atlassian.net/wiki

**Exported at:** 2026-04-16T07:43:57.749851+00:00

**Spaces:** 0

## Structure

```
manifest.json          – full metadata (IDs, titles, ancestors, labels)
<SPACE_KEY>/
  <PAGE_ID>_<Title>/
    content.html       – page body (Confluence storage format)
    attachments/       – binary attachments
```

Use `confluence_backup.py restore` to restore this backup to a Confluence instance.
