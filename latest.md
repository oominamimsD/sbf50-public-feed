# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T16:00:19Z**
- feed_generated_utc: 2026-11-03T16:00:21+00:00
- source_sha256: `30569f3fa7db3e4e14a108f936a80b20768f5e2604d7e22882da78d1f625eefb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004156|-24.46|-86.49|-24.69|12707893|2.41|
|BEAT_USDT|0.094800|-4.70|4.07|-4.93|8056748|3.16|
|NEAR_USDT|3.859000|-3.76|-15.61|-3.99|83026011|2.59|
|QNT_USDT|195.420000|-3.47|-7.06|-3.70|55386366|1.53|
|TIA_USDT|0.435800|-0.93|-18.70|-1.16|13110182|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004156|0.003997|0.004156|1.22|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.094800|0.092610|0.094800|0.75|N|Y/Y|Y/N|N|N|
|NEAR_USDT|3.859000|3.822000|3.859000|0.68|N|Y/Y|Y/Y|N|N|
|QNT_USDT|195.420000|193.330000|195.420000|0.65|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.435800|0.432900|0.435800|0.99|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T15:59:59+00:00, last15m_closed_end=2026-11-03T16:00+00:00, prior8high=0.004239, depth_time=2026-11-03T16:00:08+00:00, book20_bid_proxy_usdt=29188, book20_ask_proxy_usdt=43284, funding_indicative=-0.000071, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-24.46%, turnover=12707893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T16:00:00+00:00, last15m_closed_end=2026-11-03T16:00+00:00, prior8high=0.103310, depth_time=2026-11-03T16:00:10+00:00, book20_bid_proxy_usdt=26209, book20_ask_proxy_usdt=16681, funding_indicative=0.000354, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.70%, turnover=8056748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T15:59:59+00:00, last15m_closed_end=2026-11-03T16:00+00:00, prior8high=3.913000, depth_time=2026-11-03T16:00:13+00:00, book20_bid_proxy_usdt=3089982, book20_ask_proxy_usdt=3784040, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=83026011. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T15:59:59+00:00, last15m_closed_end=2026-11-03T16:00+00:00, prior8high=198.500000, depth_time=2026-11-03T16:00:15+00:00, book20_bid_proxy_usdt=112470, book20_ask_proxy_usdt=67789, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.47%, turnover=55386366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T16:00:00+00:00, last15m_closed_end=2026-11-03T16:00+00:00, prior8high=0.445800, depth_time=2026-11-03T16:00:17+00:00, book20_bid_proxy_usdt=434388, book20_ask_proxy_usdt=396960, funding_indicative=-0.000004, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.93%, turnover=13110182. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
