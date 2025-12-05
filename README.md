# Model Access Viewer
A lightweight, client-side tool that lets you quickly check which models your API token can access across different AI providers.

## Features
- View accessible models for OpenAI, Google Gemini, and xAI Grok  
- Fully client-side — your API token is never sent anywhere  
- ingle-file HTML tool (no build steps, no dependencies)  
- Instant to use, works offline when run locally 

## How to Use

### **Option 1 — Use Online Version**
Simply open the hosted version: [modelaccessviewer.binhua.org](https://modelaccessviewer.binhua.org)

### **Option 2 — Run Locally**
1. Download `index.html`
2. Serve it with any static HTTP server, such as [hua — A painless static file server](https://binhua.org/hua)(**Highly recommended:**  )

## Alternatively
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
