# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T11:45:24Z**
- feed_generated_utc: 2026-10-21T11:45:29+00:00
- source_sha256: `72155ea8a423742493e1c442ed6f84e45f3293496e93b95d46466c16d80cdca4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.09 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T11:45+00:00, close=83448.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T11:00+00:00, close=83362.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.181270|-15.98|2.19|-17.02|10861849|1.66|
|BTW_USDT|1.633000|-11.71|-16.36|-12.75|25774037|6.12|
|BR_USDT|0.597750|-8.13|38.04|-9.17|23254807|1.67|
|Q_USDT|0.119466|-2.67|190.48|-3.71|5411695|2.76|
|TIA_USDT|0.617500|-0.83|6.96|-1.87|47539166|3.24|
|DOT_USDT|1.152400|-0.44|-0.38|-1.48|14985573|0.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.181270|0.181440|0.181370|2.30|Y|Y/Y|Y/Y|N|Y|
|BR_USDT|0.597750|0.566870|0.597950|1.21|N|Y/Y|N/N|N|N|
|BTW_USDT|1.633000|1.665600|1.632900|2.17|Y|Y/N|N/N|N|N|
|DOT_USDT|1.152400|1.140800|1.152400|0.56|N|Y/Y|N/N|N|N|
|Q_USDT|0.119466|0.117302|0.119389|0.50|N|Y/Y|N/N|N|N|
|TIA_USDT|0.617500|0.614700|0.617900|1.41|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-21T11:45:04+00:00, last15m_closed_end=2026-10-21T11:45+00:00, prior8high=0.183780, depth_time=2026-10-21T11:45:10+00:00, book20_bid_proxy_usdt=19524, book20_ask_proxy_usdt=35712, funding_indicative=-0.000122, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.98%, turnover=10861849. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T11:45:03+00:00, last15m_closed_end=2026-10-21T11:45+00:00, prior8high=0.592830, depth_time=2026-10-21T11:45:15+00:00, book20_bid_proxy_usdt=3796, book20_ask_proxy_usdt=4016, funding_indicative=-0.000117, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.13%, turnover=23254807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T11:45:03+00:00, last15m_closed_end=2026-10-21T11:45+00:00, prior8high=2.125300, depth_time=2026-10-21T11:45:12+00:00, book20_bid_proxy_usdt=36849, book20_ask_proxy_usdt=10164, funding_indicative=-0.003780, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.71%, turnover=25774037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T11:45:04+00:00, last15m_closed_end=2026-10-21T11:45+00:00, prior8high=1.159200, depth_time=2026-10-21T11:45:23+00:00, book20_bid_proxy_usdt=386406, book20_ask_proxy_usdt=304536, funding_indicative=-0.000207, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.44%, turnover=14985573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T11:45:04+00:00, last15m_closed_end=2026-10-21T11:45+00:00, prior8high=0.122248, depth_time=2026-10-21T11:45:16+00:00, book20_bid_proxy_usdt=13411, book20_ask_proxy_usdt=14676, funding_indicative=0.000018, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=5411695. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T11:45:04+00:00, last15m_closed_end=2026-10-21T11:45+00:00, prior8high=0.627200, depth_time=2026-10-21T11:45:19+00:00, book20_bid_proxy_usdt=225837, book20_ask_proxy_usdt=377794, funding_indicative=-0.000081, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.83%, turnover=47539166. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
