# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T12:00:44Z**
- feed_generated_utc: 2026-11-06T12:00:46+00:00
- source_sha256: `b1a150cf13fe1b6f08d5790adb2181044f803e4df5c5bfe8826c30fe5c014dbd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XPL_USDT|0.058170|-7.62|-26.30|-7.75|12058725|1.72|
|XRP_USDT|1.197200|-6.51|-8.57|-6.64|482075385|0.83|
|BCH_USDT|267.720000|-5.99|-7.13|-6.12|7086355|1.87|
|QNT_USDT|189.470000|-5.09|-4.66|-5.22|34287038|0.53|
|DASH_USDT|45.610000|-4.36|-11.41|-4.49|15855260|2.19|
|ATOM_USDT|1.412000|-4.33|-13.42|-4.46|6839417|7.08|
|ZRO_USDT|1.626300|-4.14|-7.82|-4.27|7399433|1.23|
|XLM_USDT|0.154260|-3.71|-10.69|-3.84|37500539|0.65|
|NEAR_USDT|3.735000|-3.43|-19.66|-3.56|71903309|2.68|
|PUMPFUN_USDT|0.003994|-3.15|-11.73|-3.28|11208397|2.50|
|WLD_USDT|0.347500|-2.90|-20.35|-3.03|71575735|2.88|
|SOL_USDT|90.380000|-2.77|-11.94|-2.90|859765332|1.11|
|LINK_USDT|10.869000|-2.46|-9.13|-2.59|180794684|0.92|
|HYPE_USDT|78.599000|-2.36|-16.32|-2.49|77152745|0.13|
|DOGE_USDT|0.072590|-2.23|-9.97|-2.36|150371137|1.38|
|SUI_USDT|0.867400|-1.83|-9.04|-1.96|72265696|1.15|
|HBAR_USDT|0.068670|-1.35|-8.76|-1.48|9736396|1.46|
|XAU_USDT|4071.050000|-1.12|1.00|-1.25|653612655|0.03|
|XAUT_USDT|4048.040000|-1.11|0.65|-1.24|183758469|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ATOM_USDT|1.412000|1.403000|1.412000|0.06|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|267.720000|266.560000|267.720000|0.30|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.610000|45.150000|45.610000|2.08|N|N/N|Y/Y|Y|N|
|DOGE_USDT|0.072590|0.072180|0.072590|1.19|N|N/Y|Y/Y|Y|N|
|HYPE_USDT|78.599000|77.778000|78.599000|5.29|N|N/Y|Y/Y|Y|N|
|LINK_USDT|10.869000|10.763000|10.869000|0.85|N|N/Y|Y/Y|Y|N|
|NEAR_USDT|3.735000|3.715000|3.735000|1.03|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003994|0.003937|0.003994|1.34|N|N/Y|Y/Y|Y|N|
|QNT_USDT|189.470000|188.460000|189.470000|2.05|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|90.380000|89.870000|90.380000|1.27|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.347500|0.343300|0.347500|1.60|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.154260|0.153400|0.154260|0.75|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.058170|0.057550|0.058170|0.45|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.197200|1.189600|1.197200|0.60|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.626300|1.609400|1.626300|2.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ATOM_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=1.423000, depth_time=2026-11-06T12:00:18+00:00, book20_bid_proxy_usdt=1861914, book20_ask_proxy_usdt=2135363, funding_indicative=0.000077, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.33%, turnover=6839417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=269.310000, depth_time=2026-11-06T12:00:12+00:00, book20_bid_proxy_usdt=47464, book20_ask_proxy_usdt=133145, funding_indicative=-0.000048, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.99%, turnover=7086355. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=45.790000, depth_time=2026-11-06T12:00:17+00:00, book20_bid_proxy_usdt=897770, book20_ask_proxy_usdt=653252, funding_indicative=0.000032, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.36%, turnover=15855260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=0.072670, depth_time=2026-11-06T12:00:42+00:00, book20_bid_proxy_usdt=6326526, book20_ask_proxy_usdt=5400417, funding_indicative=0.000037, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=150371137. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=78.533000, depth_time=2026-11-06T12:00:40+00:00, book20_bid_proxy_usdt=87099, book20_ask_proxy_usdt=103015, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.36%, turnover=77152745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=10.897000, depth_time=2026-11-06T12:00:38+00:00, book20_bid_proxy_usdt=612763, book20_ask_proxy_usdt=601089, funding_indicative=0.000030, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=180794684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=3.758000, depth_time=2026-11-06T12:00:28+00:00, book20_bid_proxy_usdt=3563400, book20_ask_proxy_usdt=3730339, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=71903309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=0.003985, depth_time=2026-11-06T12:00:29+00:00, book20_bid_proxy_usdt=2232982, book20_ask_proxy_usdt=1607029, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=11208397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=189.600000, depth_time=2026-11-06T12:00:14+00:00, book20_bid_proxy_usdt=62020, book20_ask_proxy_usdt=92813, funding_indicative=0.000000, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.09%, turnover=34287038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=90.520000, depth_time=2026-11-06T12:00:35+00:00, book20_bid_proxy_usdt=15867285, book20_ask_proxy_usdt=15260577, funding_indicative=0.000014, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=859765332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=0.349600, depth_time=2026-11-06T12:00:31+00:00, book20_bid_proxy_usdt=2980976, book20_ask_proxy_usdt=2918257, funding_indicative=-0.000112, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=71575735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=0.154870, depth_time=2026-11-06T12:00:21+00:00, book20_bid_proxy_usdt=192328, book20_ask_proxy_usdt=225587, funding_indicative=-0.000090, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.71%, turnover=37500539. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=0.058270, depth_time=2026-11-06T12:00:06+00:00, book20_bid_proxy_usdt=506318, book20_ask_proxy_usdt=379445, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.62%, turnover=12058725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=1.201800, depth_time=2026-11-06T12:00:10+00:00, book20_bid_proxy_usdt=2693953, book20_ask_proxy_usdt=2938107, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.51%, turnover=482075385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T12:00:01+00:00, last15m_closed_end=2026-11-06T12:00+00:00, prior8high=1.634300, depth_time=2026-11-06T12:00:21+00:00, book20_bid_proxy_usdt=79028, book20_ask_proxy_usdt=58276, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=7399433. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
