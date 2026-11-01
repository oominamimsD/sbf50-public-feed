# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T03:45:24Z**
- feed_generated_utc: 2026-11-01T03:45:26+00:00
- source_sha256: `e68b6defe030738af1f41e82abc1bd543ecd993830e7b4066cda7c083462d79d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T03:45+00:00, close=77793.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T03:00+00:00, close=77690, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.231880|-21.70|38.08|-22.00|30023213|4.75|
|AKE_USDT|0.009080|-18.47|-68.93|-18.77|11683199|2.20|
|BLESS_USDT|0.009479|-10.27|16.83|-10.57|7273570|8.42|
|ZEC_USDT|1246.070000|-2.99|8.80|-3.29|984753789|0.08|
|ENA_USDT|0.188890|-2.63|1.12|-2.93|44652775|0.53|
|XLM_USDT|0.169090|-1.54|0.40|-1.84|20095366|0.59|
|TRX_USDT|0.307980|-1.39|-6.36|-1.69|10957085|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009080|0.008372|0.009081|2.82|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009479|0.009219|0.009479|1.84|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188890|0.186020|0.188820|0.59|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.231880|0.226590|0.231880|0.91|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.307980|0.307600|0.307900|0.17|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.169090|0.168390|0.169090|0.62|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1246.070000|1238.980000|1245.890000|0.74|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T03:45:02+00:00, last15m_closed_end=2026-11-01T03:45+00:00, prior8high=0.011493, depth_time=2026-11-01T03:45:11+00:00, book20_bid_proxy_usdt=11471, book20_ask_proxy_usdt=18816, funding_indicative=-0.003275, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-18.47%, turnover=11683199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T03:45:02+00:00, last15m_closed_end=2026-11-01T03:45+00:00, prior8high=0.009478, depth_time=2026-11-01T03:45:13+00:00, book20_bid_proxy_usdt=12248, book20_ask_proxy_usdt=10266, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.27%, turnover=7273570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T03:45:02+00:00, last15m_closed_end=2026-11-01T03:45+00:00, prior8high=0.190060, depth_time=2026-11-01T03:45:18+00:00, book20_bid_proxy_usdt=208815, book20_ask_proxy_usdt=142659, funding_indicative=0.000041, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=44652775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T03:45:02+00:00, last15m_closed_end=2026-11-01T03:45+00:00, prior8high=0.240150, depth_time=2026-11-01T03:45:09+00:00, book20_bid_proxy_usdt=36604, book20_ask_proxy_usdt=26430, funding_indicative=-0.000713, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.70%, turnover=30023213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T03:45:02+00:00, last15m_closed_end=2026-11-01T03:45+00:00, prior8high=0.309960, depth_time=2026-11-01T03:45:22+00:00, book20_bid_proxy_usdt=112809, book20_ask_proxy_usdt=210610, funding_indicative=-0.001274, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.39%, turnover=10957085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T03:45:02+00:00, last15m_closed_end=2026-11-01T03:45+00:00, prior8high=0.169340, depth_time=2026-11-01T03:45:21+00:00, book20_bid_proxy_usdt=154045, book20_ask_proxy_usdt=282489, funding_indicative=-0.000001, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=20095366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T03:45:02+00:00, last15m_closed_end=2026-11-01T03:45+00:00, prior8high=1262.810000, depth_time=2026-11-01T03:45:16+00:00, book20_bid_proxy_usdt=365498, book20_ask_proxy_usdt=3269816, funding_indicative=-0.000103, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=984753789. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
