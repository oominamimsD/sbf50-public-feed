# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T08:15:34Z**
- feed_generated_utc: 2026-11-01T08:15:38+00:00
- source_sha256: `8c0f93e34f12365b4ee0ee0c7cba1d75d82c6c73bd9f8117d231d65eaec0eaeb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T08:15+00:00, close=77869.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.222560|-24.85|32.53|-25.24|30833554|1.80|
|AKE_USDT|0.009346|-16.08|-68.02|-16.47|9997071|3.20|
|BLESS_USDT|0.009460|-10.45|16.60|-10.84|6261805|5.29|
|XPL_USDT|0.074190|-8.75|2.74|-9.14|6296704|1.35|
|ENA_USDT|0.187560|-3.32|0.41|-3.71|42903432|0.53|
|ZEC_USDT|1243.880000|-3.16|8.61|-3.55|913371577|0.08|
|NEAR_USDT|4.364000|-2.50|-0.86|-2.89|52335602|2.29|
|TIA_USDT|0.478600|-2.34|-8.95|-2.73|8263820|2.09|
|XLM_USDT|0.169040|-1.57|0.37|-1.96|19892886|0.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009346|0.009211|0.009335|1.18|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009460|0.009395|0.009460|2.13|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187560|0.186980|0.187650|0.87|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.222560|0.228710|0.222380|2.82|Y|Y/Y|N/N|Y|N|
|NEAR_USDT|4.364000|4.359000|4.364000|2.92|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.478600|0.478000|0.478600|1.08|N|N/N|Y/Y|Y|N|
|XLM_USDT|0.169040|0.168690|0.169030|0.69|N|N/Y|N/Y|Y|N|
|XPL_USDT|0.074190|0.072520|0.074190|1.69|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1243.880000|1239.270000|1244.740000|1.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T08:15:02+00:00, last15m_closed_end=2026-11-01T08:15+00:00, prior8high=0.010220, depth_time=2026-11-01T08:15:15+00:00, book20_bid_proxy_usdt=7392, book20_ask_proxy_usdt=11030, funding_indicative=-0.002417, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.08%, turnover=9997071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T08:15:02+00:00, last15m_closed_end=2026-11-01T08:15+00:00, prior8high=0.009785, depth_time=2026-11-01T08:15:18+00:00, book20_bid_proxy_usdt=22278, book20_ask_proxy_usdt=15643, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.45%, turnover=6261805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T08:15:02+00:00, last15m_closed_end=2026-11-01T08:15+00:00, prior8high=0.190760, depth_time=2026-11-01T08:15:23+00:00, book20_bid_proxy_usdt=133604, book20_ask_proxy_usdt=159646, funding_indicative=-0.000005, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.32%, turnover=42903432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T08:15:02+00:00, last15m_closed_end=2026-11-01T08:15+00:00, prior8high=0.243440, depth_time=2026-11-01T08:15:13+00:00, book20_bid_proxy_usdt=3969, book20_ask_proxy_usdt=20140, funding_indicative=-0.002127, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-24.85%, turnover=30833554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T08:15:02+00:00, last15m_closed_end=2026-11-01T08:15+00:00, prior8high=4.410000, depth_time=2026-11-01T08:15:24+00:00, book20_bid_proxy_usdt=4732186, book20_ask_proxy_usdt=3352897, funding_indicative=0.000100, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=52335602. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-01T08:15:02+00:00, last15m_closed_end=2026-11-01T08:15+00:00, prior8high=0.486200, depth_time=2026-11-01T08:15:29+00:00, book20_bid_proxy_usdt=187988, book20_ask_proxy_usdt=250309, funding_indicative=-0.000106, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=8263820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T08:15:02+00:00, last15m_closed_end=2026-11-01T08:15+00:00, prior8high=0.169690, depth_time=2026-11-01T08:15:33+00:00, book20_bid_proxy_usdt=276788, book20_ask_proxy_usdt=179586, funding_indicative=0.000100, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=19892886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T08:15:02+00:00, last15m_closed_end=2026-11-01T08:15+00:00, prior8high=0.074940, depth_time=2026-11-01T08:15:20+00:00, book20_bid_proxy_usdt=407358, book20_ask_proxy_usdt=286700, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.75%, turnover=6296704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T08:15:02+00:00, last15m_closed_end=2026-11-01T08:15+00:00, prior8high=1254.820000, depth_time=2026-11-01T08:15:26+00:00, book20_bid_proxy_usdt=301944, book20_ask_proxy_usdt=558395, funding_indicative=-0.000081, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=913371577. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
