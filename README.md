# Kaara-Auto-Gold-Price-Updator

/Connect to Gold Rate API
Calculate 18KT gold rate ans stone rate
/Fetch todays 22KT Gold Rate
/Connected securely to your Shopify Admin API
/Update store metafields

/Pulled live product and metafield data
/Calculated prices based on gold rate, stone price, and making charges
/Updated every product automatically

/Generated a timestamped CSV report of all updates
/Send Automatic email attached with Report after Each Run

______________________________________________________________

/Update Gold Rate and Stone Rate for Product Page Display Pricing (Price Breakup Table)
______________________________________________________________

/Schuduled Daily Run at 2AM - 3 to 4 mins for all 300 products (Active and Draft)
______________________________________________________________

shopify_auto_pricing/
│
├── 1_fetch_gold_rate.py        # Step 1: Fetch 22K, 18K, stone rate
├── 2_update_metafields.py      # Step 2: Update shop metafields
├── 3_update_product_prices.py  # Step 3: Update all products (your current working script)
├── 4_send_report_email.py      # Step 4: Send report via email
├── config.py                   # Common constants (Shop URL, Token, Email settings)
└── run_all.py                  # Orchestrator - runs all 4 scripts sequentially


