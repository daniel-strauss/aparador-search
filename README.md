# Aparador · picture search

The page the Aparador app (Android) opens to find a product's pictures on brand websites:

- `picker.html` — Google's Programmable Search Element, image search restricted to brand websites, shown unchanged
  with Google's ads and attribution. A tap opens the brand's own product page; the seller chooses a picture there.
- `engines.json` — the search engines (one per product category or market, up to 50 brand sites each) and their brands.
- `codes/<first three digits>.json` — barcode → brand product page, for brands whose public sitemaps list product
  addresses that carry the barcode (only those addresses are kept). A scanned code found here opens that page directly.

Made from Aparador's research tools; updated from there.
