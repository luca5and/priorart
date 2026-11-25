# Prior-Art Search

Free, experimental prior-art search for patents in CPC A47J (kitchen equipment).

**Open the tool: https://luca5and.github.io/priorart/**

This repository only holds the web page. Searches run on small open models (BM25, PaECTER, bge-small
and a patent-trained reranker) on our own server; no paid AI service sees your text. `api.json` holds
the current address of that server and is updated automatically.

Data: Google Patents Public Data (IFI CLAIMS Patent Services and Google), CC BY 4.0.
Search aid only, not legal advice.
