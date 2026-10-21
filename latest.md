# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T12:45:26Z**
- feed_generated_utc: 2026-10-21T12:45:29+00:00
- source_sha256: `b3c8fb66d93bbaed420d3eb33a5d79a3f1b835526d4c2f5dc68797bb5810fd51`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T12:45+00:00, close=83583.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.045977|-28.86|184.21|-30.07|6685291|2.82|
|BAT_USDT|0.180970|-16.12|2.02|-17.33|10737745|0.55|
|BTW_USDT|1.573700|-14.91|-19.40|-16.12|25087956|2.55|
|BR_USDT|0.618930|-4.87|42.93|-6.08|21131745|1.62|
|AKE_USDT|0.029581|-4.85|18.00|-6.06|8449139|0.68|
|Q_USDT|0.120237|-2.05|192.35|-3.26|5028737|1.58|
|SILVER_USDT|57.560000|-0.67|-3.08|-1.88|234912886|1.74|
|TIA_USDT|0.623200|0.08|7.95|-1.13|45807700|1.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.045977|0.044727|0.045977|0.35|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.029581|0.028134|0.029581|0.90|N|Y/N|Y/N|N|N|
|BAT_USDT|0.180970|0.180140|0.180920|0.85|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.618930|0.572580|0.618850|0.98|N|Y/Y|N/N|N|N|
|BTW_USDT|1.573700|1.573600|1.573400|1.33|Y|Y/Y|Y/Y|N|Y|
|Q_USDT|0.120237|0.117302|0.120237|0.56|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.560000|57.450000|57.560000|1.97|N|N/N|N/N|N|N|
|TIA_USDT|0.623200|0.615000|0.623400|0.90|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T12:45:00+00:00, last15m_closed_end=2026-10-21T12:45+00:00, prior8high=0.049359, depth_time=2026-10-21T12:45:08+00:00, book20_bid_proxy_usdt=2962, book20_ask_proxy_usdt=7965, funding_indicative=0.000047, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-28.86%, turnover=6685291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T12:45:00+00:00, last15m_closed_end=2026-10-21T12:45+00:00, prior8high=0.036656, depth_time=2026-10-21T12:45:18+00:00, book20_bid_proxy_usdt=11456, book20_ask_proxy_usdt=11645, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.85%, turnover=8449139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T12:45:00+00:00, last15m_closed_end=2026-10-21T12:45+00:00, prior8high=0.183270, depth_time=2026-10-21T12:45:11+00:00, book20_bid_proxy_usdt=20174, book20_ask_proxy_usdt=26201, funding_indicative=-0.000154, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-16.12%, turnover=10737745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T12:45:00+00:00, last15m_closed_end=2026-10-21T12:45+00:00, prior8high=0.611980, depth_time=2026-10-21T12:45:16+00:00, book20_bid_proxy_usdt=4316, book20_ask_proxy_usdt=3432, funding_indicative=-0.000060, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=21131745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T12:45:00+00:00, last15m_closed_end=2026-10-21T12:45+00:00, prior8high=1.787000, depth_time=2026-10-21T12:45:13+00:00, book20_bid_proxy_usdt=8310, book20_ask_proxy_usdt=13666, funding_indicative=-0.005104, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.91%, turnover=25087956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T12:45:00+00:00, last15m_closed_end=2026-10-21T12:45+00:00, prior8high=0.122261, depth_time=2026-10-21T12:45:20+00:00, book20_bid_proxy_usdt=19740, book20_ask_proxy_usdt=17975, funding_indicative=0.000000, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.05%, turnover=5028737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T12:45:00+00:00, last15m_closed_end=2026-10-21T12:45+00:00, prior8high=57.860000, depth_time=2026-10-21T12:45:22+00:00, book20_bid_proxy_usdt=42397977, book20_ask_proxy_usdt=38733626, funding_indicative=0.000039, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.67%, turnover=234912886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T12:45:00+00:00, last15m_closed_end=2026-10-21T12:45+00:00, prior8high=0.625900, depth_time=2026-10-21T12:45:25+00:00, book20_bid_proxy_usdt=231408, book20_ask_proxy_usdt=306143, funding_indicative=-0.000088, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=0.08%, turnover=45807700. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
