# Attachments

## Inline

```json
{
  "attachments": [
    {
      "filename": "file.pdf",
      "content": "base64"
    }
  ]
}
```

## URL
```json
{
  "attachments": [
    {
      "filename": "file.pdf",
      "url": "https://file.com"
    }
  ]
}
```

## Templated
```json
{
  "filename": "file-{{name}}.txt"
}
```

## Notes
* Mostly email
* Supports overrides
