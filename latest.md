# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T13:30:37Z**
- feed_generated_utc: 2026-10-25T13:30:40+00:00
- source_sha256: `cab2cbd575c1efe312b849e4b618393a52223f9d225114add91488caf6c3a711`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T13:30+00:00, close=80245.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T13:00+00:00, close=80419.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.046480|-31.03|50.17|-31.63|6718762|6.46|
|IRYS_USDT|0.035010|-23.97|174.37|-24.57|25698636|5.71|
|BTW_USDT|1.688200|-3.04|-25.61|-3.64|12570593|1.19|
|STRK_USDT|0.045400|-2.84|-31.36|-3.44|10240780|2.20|
|DOT_USDT|1.025000|-1.35|-8.26|-1.95|12593344|0.98|
|APT_USDT|0.693500|-1.19|-13.04|-1.79|6094897|1.44|
|SEI_USDT|0.052260|-1.17|-15.72|-1.77|7770269|1.91|
|SUI_USDT|0.914700|-1.11|-6.83|-1.71|70153648|1.09|
|PENGU_USDT|0.007361|-1.10|-1.23|-1.70|6056568|2.72|
|ARB_USDT|0.164690|-0.63|-10.45|-1.23|15926267|0.61|
|TIA_USDT|0.522700|-0.57|-20.56|-1.17|20301741|1.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.693500|0.689400|0.693500|0.37|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164690|0.163860|0.164690|0.36|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.688200|1.638700|1.688200|1.55|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.025000|1.014400|1.025000|0.43|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035010|0.033150|0.034930|1.43|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.046480|0.045450|0.046470|1.03|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007361|0.007338|0.007361|2.99|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052260|0.052260|0.052270|2.01|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045400|0.044870|0.045400|0.94|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.914700|0.910400|0.914700|0.94|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.522700|0.522300|0.522900|0.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T13:30:04+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=0.698900, depth_time=2026-10-25T13:30:20+00:00, book20_bid_proxy_usdt=82878, book20_ask_proxy_usdt=152525, funding_indicative=-0.000134, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=6094897. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-25T13:30:03+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=0.166330, depth_time=2026-10-25T13:30:33+00:00, book20_bid_proxy_usdt=57177, book20_ask_proxy_usdt=72852, funding_indicative=0.000050, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.63%, turnover=15926267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T13:30:03+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=1.699100, depth_time=2026-10-25T13:30:14+00:00, book20_bid_proxy_usdt=12829, book20_ask_proxy_usdt=16056, funding_indicative=-0.010647, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=12570593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T13:30:03+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=1.028700, depth_time=2026-10-25T13:30:16+00:00, book20_bid_proxy_usdt=221706, book20_ask_proxy_usdt=280817, funding_indicative=-0.000074, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=12593344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T13:30:03+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=0.035750, depth_time=2026-10-25T13:30:11+00:00, book20_bid_proxy_usdt=57901, book20_ask_proxy_usdt=53736, funding_indicative=0.000012, next_funding_utc=2026-10-25T14:00:00+00:00, funding_cycle_h=1, 24h_change=-23.97%, turnover=25698636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T13:30:03+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=0.049970, depth_time=2026-10-25T13:30:08+00:00, book20_bid_proxy_usdt=87770, book20_ask_proxy_usdt=67554, funding_indicative=-0.000775, next_funding_utc=2026-10-25T14:00:00+00:00, funding_cycle_h=1, 24h_change=-31.03%, turnover=6718762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T13:30:04+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=0.007422, depth_time=2026-10-25T13:30:30+00:00, book20_bid_proxy_usdt=194061, book20_ask_proxy_usdt=228111, funding_indicative=-0.000060, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=6056568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T13:30:04+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=0.052880, depth_time=2026-10-25T13:30:22+00:00, book20_bid_proxy_usdt=232691, book20_ask_proxy_usdt=353935, funding_indicative=-0.000055, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=7770269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T13:30:04+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=0.046180, depth_time=2026-10-25T13:30:15+00:00, book20_bid_proxy_usdt=833760, book20_ask_proxy_usdt=828670, funding_indicative=0.000005, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=10240780. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T13:30:03+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=0.920400, depth_time=2026-10-25T13:30:24+00:00, book20_bid_proxy_usdt=1336785, book20_ask_proxy_usdt=913851, funding_indicative=-0.000038, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=70153648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T13:30:03+00:00, last15m_closed_end=2026-10-25T13:30+00:00, prior8high=0.532800, depth_time=2026-10-25T13:30:35+00:00, book20_bid_proxy_usdt=392278, book20_ask_proxy_usdt=298328, funding_indicative=-0.000014, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.57%, turnover=20301741. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
