# Tidewatch public package (G1-1)

- data_as_of: **2026-09-15**
- generated_at: `2026-09-16T03:52:44Z`
- no Tide Notes / no Q&A / no claim-watch
- same render source as local `output/` (public mode)
- do not commit secrets; push is **G1-2** / `tidewatch promote`

Preview:
```bash
python3 -m http.server 8767 --bind 127.0.0.1 --directory public_site
open http://127.0.0.1:8767/site/
```
