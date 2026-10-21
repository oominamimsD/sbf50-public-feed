# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T02:30:22Z**
- feed_generated_utc: 2026-10-21T02:30:24+00:00
- source_sha256: `80a6a222d30f71fd7ecb866cc8190d94e21852bf87e33b76a215f77b6f8d4a75`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T02:30+00:00, close=82727.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T02:00+00:00, close=82965.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.186890|-13.38|5.36|-13.55|10420393|0.54|
|XMR_USDT|577.980000|-6.80|9.48|-6.97|20048548|2.25|
|BR_USDT|0.630760|-3.05|45.66|-3.22|36159530|0.79|
|AGT_USDT|0.063449|-1.82|292.21|-1.99|7135221|2.21|
|TIA_USDT|0.612000|-1.71|6.01|-1.88|49647722|1.63|
|SEI_USDT|0.060940|-1.11|-2.29|-1.28|6207965|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.063449|0.060101|0.063449|0.73|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.186890|0.187490|0.186890|0.66|N|Y/Y|N/N|N|N|
|BR_USDT|0.630760|0.614910|0.631150|0.51|N|Y/Y|N/N|N|N|
|SEI_USDT|0.060940|0.060950|0.060940|3.01|Y|N/N|Y/Y|N|N|
|TIA_USDT|0.612000|0.605800|0.612000|0.21|N|Y/Y|Y/Y|N|N|
|XMR_USDT|577.980000|572.610000|577.980000|0.56|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T02:30:00+00:00, last15m_closed_end=2026-10-21T02:30+00:00, prior8high=0.069341, depth_time=2026-10-21T02:30:15+00:00, book20_bid_proxy_usdt=8301, book20_ask_proxy_usdt=3898, funding_indicative=0.000050, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=7135221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T02:30:00+00:00, last15m_closed_end=2026-10-21T02:30+00:00, prior8high=0.194200, depth_time=2026-10-21T02:30:07+00:00, book20_bid_proxy_usdt=27154, book20_ask_proxy_usdt=23250, funding_indicative=0.000056, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.38%, turnover=10420393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T02:30:00+00:00, last15m_closed_end=2026-10-21T02:30+00:00, prior8high=0.664000, depth_time=2026-10-21T02:30:13+00:00, book20_bid_proxy_usdt=4100, book20_ask_proxy_usdt=1686, funding_indicative=0.000000, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=36159530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-21T02:30:00+00:00, last15m_closed_end=2026-10-21T02:30+00:00, prior8high=0.061880, depth_time=2026-10-21T02:30:21+00:00, book20_bid_proxy_usdt=283950, book20_ask_proxy_usdt=253286, funding_indicative=-0.000076, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=6207965. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T02:30:00+00:00, last15m_closed_end=2026-10-21T02:30+00:00, prior8high=0.623900, depth_time=2026-10-21T02:30:18+00:00, book20_bid_proxy_usdt=216020, book20_ask_proxy_usdt=221326, funding_indicative=-0.000046, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=49647722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T02:30:00+00:00, last15m_closed_end=2026-10-21T02:30+00:00, prior8high=601.630000, depth_time=2026-10-21T02:30:09+00:00, book20_bid_proxy_usdt=15047, book20_ask_proxy_usdt=17047, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.80%, turnover=20048548. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
