# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T11:15:26Z**
- feed_generated_utc: 2026-10-28T11:15:32+00:00
- source_sha256: `ec7a5e42b556dbd507665f381900e227b7bd01c2accc65cc9f69b3959036ea92`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.1 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T11:15+00:00, close=81340.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T11:00+00:00, close=81460.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.055750|-12.32|-54.58|-13.32|20507449|3.59|
|BEAT_USDT|0.084500|-7.23|13.10|-8.23|15540214|4.73|
|AKE_USDT|0.019774|-6.39|-36.39|-7.39|6389149|5.05|
|ENA_USDT|0.204060|-4.09|7.46|-5.09|70245621|0.49|
|INJ_USDT|7.913000|-3.40|-7.98|-4.40|24537038|2.53|
|SILVER_USDT|53.870000|-1.40|-7.04|-2.40|227763641|1.86|
|DASH_USDT|53.560000|-1.12|7.24|-2.12|16002484|1.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.019774|0.019671|0.019748|1.10|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.084500|0.084080|0.084640|0.94|N|Y/Y|N/N|N|N|
|DASH_USDT|53.560000|53.550000|53.570000|2.45|N|Y/Y|N/N|N|N|
|ENA_USDT|0.204060|0.204750|0.204190|5.59|Y|Y/Y|N/N|N|N|
|INJ_USDT|7.913000|7.895000|7.913000|1.95|N|Y/Y|N/N|N|N|
|Q_USDT|0.055750|0.055820|0.055750|1.72|Y|Y/Y|Y/Y|N|Y|
|SILVER_USDT|53.870000|53.750000|53.860000|0.38|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T11:15:03+00:00, last15m_closed_end=2026-10-28T11:15+00:00, prior8high=0.021104, depth_time=2026-10-28T11:15:15+00:00, book20_bid_proxy_usdt=4514, book20_ask_proxy_usdt=4975, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.39%, turnover=6389149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T11:15:03+00:00, last15m_closed_end=2026-10-28T11:15+00:00, prior8high=0.104960, depth_time=2026-10-28T11:15:10+00:00, book20_bid_proxy_usdt=9141, book20_ask_proxy_usdt=5575, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.23%, turnover=15540214. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T11:15:04+00:00, last15m_closed_end=2026-10-28T11:15+00:00, prior8high=54.240000, depth_time=2026-10-28T11:15:21+00:00, book20_bid_proxy_usdt=773091, book20_ask_proxy_usdt=604204, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=16002484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T11:15:03+00:00, last15m_closed_end=2026-10-28T11:15+00:00, prior8high=0.208250, depth_time=2026-10-28T11:15:18+00:00, book20_bid_proxy_usdt=119023, book20_ask_proxy_usdt=192961, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.09%, turnover=70245621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T11:15:03+00:00, last15m_closed_end=2026-10-28T11:15+00:00, prior8high=7.998000, depth_time=2026-10-28T11:15:19+00:00, book20_bid_proxy_usdt=250376, book20_ask_proxy_usdt=234860, funding_indicative=0.000236, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.40%, turnover=24537038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T11:15:03+00:00, last15m_closed_end=2026-10-28T11:15+00:00, prior8high=0.060270, depth_time=2026-10-28T11:15:10+00:00, book20_bid_proxy_usdt=40075, book20_ask_proxy_usdt=26211, funding_indicative=-0.000332, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.32%, turnover=20507449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-28T11:15:03+00:00, last15m_closed_end=2026-10-28T11:15+00:00, prior8high=54.170000, depth_time=2026-10-28T11:15:21+00:00, book20_bid_proxy_usdt=63742889, book20_ask_proxy_usdt=51363030, funding_indicative=0.000007, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=227763641. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
