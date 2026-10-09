## Foundry IQ

### Basics
#### Description
```
Knowledge base for ETF Analysis SharePoint documents with direct source-document citations.
```

### Retrieval
#### Reasoning effort
```
Low
```
#### Retrieval instructions
```
Answer using the indexed ETF Analysis SharePoint documents. Cite the supporting references and preserve citation URLs that point to the original SharePoint documents.

Queries must set both  includeReferences: true  and  includeReferenceSourceData: true
```
#### Chat completion model
```
gpt-4.1-mini
```
### Output configurations
#### Output mode
```
Answer synthesis
```
#### Answer instructions
```
Provide a concise answer grounded only in the retrieved SharePoint documents. Cite claims using the reference IDs. End every answer with a Sources section containing Markdown links to the original SharePoint documents. For each source, use the exact absolute URL from the retrieved doc_url field; never use citationUrl or an Azure AI Search index URL as the document link. Deduplicate sources.
```

## Web IQ
https://webiq.microsoft.ai/

## Fabric IQ
TODO add a data export

## Work IQ
Either use built-ins or checkout an alternative like https://github.com/implodingduck/fastmcp-graph-server