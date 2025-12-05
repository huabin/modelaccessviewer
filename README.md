# Model Access Viewer
Check which models your API token can access.

### How To

Check [online](https://modelaccessviewer.binhua.org)

### Alternatively
you can also check model access from your terminal:

**OpenAI**

```
curl https://api.openai.com/v1/models \
  -H "Authorization: Bearer your_api_token"
```

**Google Gemini**

```
curl "https://generativelanguage.googleapis.com/v1beta/models" \
  -H "x-goog-api-key: your_api_token"
```

**xAI Grok**

```
curl https://api.x.ai/v1/models \
  -H "Authorization: Bearer your_api_token"
```
