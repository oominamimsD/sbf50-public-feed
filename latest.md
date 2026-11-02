# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T16:30:19Z**
- feed_generated_utc: 2026-11-02T16:30:20+00:00
- source_sha256: `6b2e30493640f9d11d9bb75108da18b74a6c2e277b5c1af393db7f483690b2df`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T16:30+00:00, close=77298.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.130100|-1.95|-47.70|-1.73|8009644|7.68|
|ENA_USDT|0.171640|-1.94|-18.41|-1.72|65456165|0.58|
|ZEC_USDT|1230.890000|-1.85|-1.34|-1.63|1558750910|0.08|
|LSK_USDT|0.183500|-1.67|16.33|-1.45|5028417|2.18|
|QNT_USDT|199.300000|-1.55|-5.22|-1.33|46370980|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.171640|0.173360|0.171640|1.50|Y|Y/Y|Y/Y|Y|Y|
|LSK_USDT|0.183500|0.184630|0.183500|1.16|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|199.300000|200.620000|199.290000|4.03|Y|N/N|N/N|Y|N|
|UAI_USDT|0.130100|0.130000|0.130100|1.29|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1230.890000|1245.610000|1230.300000|1.15|N|N/N|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-02T16:30:01+00:00, last15m_closed_end=2026-11-02T16:30+00:00, prior8high=0.178850, depth_time=2026-11-02T16:30:11+00:00, book20_bid_proxy_usdt=58753, book20_ask_proxy_usdt=240600, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=65456165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-02T16:30:01+00:00, last15m_closed_end=2026-11-02T16:30+00:00, prior8high=0.191090, depth_time=2026-11-02T16:30:16+00:00, book20_bid_proxy_usdt=21081, book20_ask_proxy_usdt=23773, funding_indicative=-0.001894, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=5028417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T16:30:01+00:00, last15m_closed_end=2026-11-02T16:30+00:00, prior8high=205.450000, depth_time=2026-11-02T16:30:18+00:00, book20_bid_proxy_usdt=70782, book20_ask_proxy_usdt=96415, funding_indicative=0.000041, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=46370980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T16:30:01+00:00, last15m_closed_end=2026-11-02T16:30+00:00, prior8high=0.139200, depth_time=2026-11-02T16:30:08+00:00, book20_bid_proxy_usdt=152163, book20_ask_proxy_usdt=156888, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=8009644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T16:30:00+00:00, last15m_closed_end=2026-11-02T16:30+00:00, prior8high=1273.850000, depth_time=2026-11-02T16:30:13+00:00, book20_bid_proxy_usdt=663841, book20_ask_proxy_usdt=258327, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=1558750910. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
