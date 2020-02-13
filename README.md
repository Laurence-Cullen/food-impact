# food-impact
Experiments estimating the environmental impact of food products from barcodes

## Resources
- Open barcode food data https://world.openfoodfacts.org/data
- Latest metastudy estimates of major food category impacts https://science.sciencemag.org/content/360/6392/987

## Dev plan
- Deploy as mobile app with barcode scanner
- App gets barcode ID, extract product description from open dataset
- Use NLP model to map from product name and description to one of ~40 categories for which good impact numbers exist
- Use NLP to determine product volume/weight
- Compute and present to user estimated range of impact metrics
- Ask for user validation of extracted category and volume/weight
