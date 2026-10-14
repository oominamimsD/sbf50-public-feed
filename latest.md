# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T13:15:43Z**
- feed_generated_utc: 2026-10-14T13:15:46+00:00
- source_sha256: `5fa11326d32345c5d138a1db7beac85b04a478015900de0fda93be8f4fa80670`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T13:15+00:00, close=82375.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T13:00+00:00, close=82699.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078630|-9.54|50.66|-8.32|26401345|1.27|
|W_USDT|0.015360|-8.58|5.84|-7.36|6270443|0.65|
|TIA_USDT|0.544000|-5.76|14.21|-4.54|33786245|1.84|
|ENA_USDT|0.198670|-5.19|-16.53|-3.97|36478499|0.50|
|UNI_USDT|7.204000|-4.86|-16.86|-3.64|20911650|1.39|
|SILVER_USDT|56.930000|-4.14|-7.23|-2.92|331224758|1.76|
|ONDO_USDT|0.449600|-3.43|-10.75|-2.21|31350203|2.22|
|RENDER_USDT|1.924000|-3.17|-9.67|-1.95|8916366|5.19|
|ICP_USDT|3.022000|-2.89|-11.16|-1.67|8957412|3.31|
|AVAX_USDT|9.939000|-2.85|-13.61|-1.63|33706530|1.01|
|APT_USDT|0.797500|-2.80|-3.42|-1.58|11306093|5.01|
|XLM_USDT|0.185710|-2.75|-13.08|-1.53|10892702|1.61|
|LDO_USDT|0.408200|-2.53|-12.74|-1.31|5774847|2.45|
|HBAR_USDT|0.084720|-2.34|-15.34|-1.12|14343352|1.18|
|FARTCOIN_USDT|0.157100|-2.33|-10.02|-1.11|6322080|1.91|
|FILECOIN_USDT|1.107000|-2.30|-3.78|-1.08|25591836|0.90|
|SOL_USDT|104.930000|-2.23|-12.89|-1.01|789259149|0.95|
|ADA_USDT|0.228800|-2.22|-15.69|-1.00|37029695|4.37|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.797500|0.800000|0.797500|8.53|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|9.939000|9.984000|9.939000|3.21|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.198670|0.187500|0.198790|2.12|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.157100|0.157810|0.156990|3.80|Y|Y/Y|Y/Y|Y|Y|
|HBAR_USDT|0.084720|0.085150|0.084700|4.86|Y|Y/Y|Y/Y|Y|Y|
|ICP_USDT|3.022000|3.029000|3.022000|2.56|Y|Y/Y|Y/Y|Y|Y|
|LDO_USDT|0.408200|0.409300|0.408200|1.37|Y|Y/Y|Y/Y|Y|Y|
|ONDO_USDT|0.449600|0.452400|0.449600|2.96|Y|Y/Y|Y/Y|Y|Y|
|RENDER_USDT|1.924000|1.942000|1.923000|4.29|Y|Y/Y|Y/Y|Y|Y|
|SILVER_USDT|56.930000|57.500000|56.940000|15.72|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.078630|0.077420|0.078630|0.83|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.544000|0.540500|0.543900|0.96|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.204000|7.188000|7.202000|6.77|N|Y/Y|Y/Y|Y|N|
|W_USDT|0.015360|0.015559|0.015357|2.15|Y|Y/Y|Y/Y|Y|Y|
|XLM_USDT|0.185710|0.186600|0.185720|2.55|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=0.828800, depth_time=2026-10-14T13:15:33+00:00, book20_bid_proxy_usdt=93383, book20_ask_proxy_usdt=141636, funding_indicative=-0.000004, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=11306093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=10.294000, depth_time=2026-10-14T13:15:31+00:00, book20_bid_proxy_usdt=510088, book20_ask_proxy_usdt=564421, funding_indicative=0.000005, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=33706530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=0.212000, depth_time=2026-10-14T13:15:15+00:00, book20_bid_proxy_usdt=83992, book20_ask_proxy_usdt=99824, funding_indicative=0.000013, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.19%, turnover=36478499. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=0.162820, depth_time=2026-10-14T13:15:43+00:00, book20_bid_proxy_usdt=44107, book20_ask_proxy_usdt=32899, funding_indicative=0.000050, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=6322080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=0.087070, depth_time=2026-10-14T13:15:40+00:00, book20_bid_proxy_usdt=262419, book20_ask_proxy_usdt=650019, funding_indicative=0.000033, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=14343352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=3.118000, depth_time=2026-10-14T13:15:28+00:00, book20_bid_proxy_usdt=623453, book20_ask_proxy_usdt=721757, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=8957412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=0.422000, depth_time=2026-10-14T13:15:38+00:00, book20_bid_proxy_usdt=454119, book20_ask_proxy_usdt=375450, funding_indicative=0.000089, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=5774847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=0.467700, depth_time=2026-10-14T13:15:23+00:00, book20_bid_proxy_usdt=1068964, book20_ask_proxy_usdt=1528357, funding_indicative=-0.000027, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=31350203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=2.007000, depth_time=2026-10-14T13:15:24+00:00, book20_bid_proxy_usdt=1437494, book20_ask_proxy_usdt=1765557, funding_indicative=0.000046, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=8916366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=58.910000, depth_time=2026-10-14T13:15:20+00:00, book20_bid_proxy_usdt=35022619, book20_ask_proxy_usdt=34450934, funding_indicative=0.000122, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=331224758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=0.080580, depth_time=2026-10-14T13:15:07+00:00, book20_bid_proxy_usdt=227928, book20_ask_proxy_usdt=205283, funding_indicative=0.000050, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.54%, turnover=26401345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=0.560900, depth_time=2026-10-14T13:15:13+00:00, book20_bid_proxy_usdt=141456, book20_ask_proxy_usdt=124826, funding_indicative=-0.000007, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.76%, turnover=33786245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=7.406000, depth_time=2026-10-14T13:15:18+00:00, book20_bid_proxy_usdt=981811, book20_ask_proxy_usdt=957766, funding_indicative=0.000075, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.86%, turnover=20911650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=0.016122, depth_time=2026-10-14T13:15:11+00:00, book20_bid_proxy_usdt=42422, book20_ask_proxy_usdt=32577, funding_indicative=-0.000211, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.58%, turnover=6270443. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T13:15:01+00:00, last15m_closed_end=2026-10-14T13:15+00:00, prior8high=0.190870, depth_time=2026-10-14T13:15:36+00:00, book20_bid_proxy_usdt=50117, book20_ask_proxy_usdt=147176, funding_indicative=-0.000080, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=10892702. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
