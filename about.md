basicpage:
    type: page
    label: Basic Page
    match: '*.md'
    exclude: _index.md
    fields:
      - type: string
        name: title
        label: Title
        description: The title of the page.
      - type: date
        name: date
        label: Date
      - type: string
        name: layout
        label: layout
      - type: string
        name: menu
        label: Menu