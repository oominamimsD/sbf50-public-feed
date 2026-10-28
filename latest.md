# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T22:30:18Z**
- feed_generated_utc: 2026-10-28T22:30:22+00:00
- source_sha256: `9c3d4d9fbce4a9ead703e1d12ed5a54ae8124178c9639e3b87f6de4d257581f8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T22:30+00:00, close=81230.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T22:00+00:00, close=81323.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.010846|-1.01|34.76|-1.88|23786542|8.29|
|HBAR_USDT|0.075140|-1.01|-12.56|-1.88|12654271|1.33|
|BCH_USDT|290.480000|-0.83|0.27|-1.70|5848438|3.79|
|BTW_USDT|1.726600|-0.65|17.47|-1.52|12249796|1.16|
|XMR_USDT|601.590000|-0.41|0.89|-1.28|5270428|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|290.480000|286.690000|290.490000|0.17|N|Y/Y|N/N|N|N|
|BLESS_USDT|0.010846|0.010825|0.010833|0.95|N|N/N|N/N|N|N|
|BTW_USDT|1.726600|1.721700|1.726200|1.14|N|N/N|N/N|N|N|
|HBAR_USDT|0.075140|0.075100|0.075140|1.15|N|Y/N|Y/Y|N|N|
|XMR_USDT|601.590000|595.790000|601.590000|1.34|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T22:30:02+00:00, last15m_closed_end=2026-10-28T22:30+00:00, prior8high=291.470000, depth_time=2026-10-28T22:30:13+00:00, book20_bid_proxy_usdt=49723, book20_ask_proxy_usdt=70875, funding_indicative=0.000011, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.83%, turnover=5848438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-28T22:30:01+00:00, last15m_closed_end=2026-10-28T22:30+00:00, prior8high=0.011275, depth_time=2026-10-28T22:30:08+00:00, book20_bid_proxy_usdt=8216, book20_ask_proxy_usdt=4598, funding_indicative=0.000145, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.01%, turnover=23786542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-28T22:30:01+00:00, last15m_closed_end=2026-10-28T22:30+00:00, prior8high=1.751000, depth_time=2026-10-28T22:30:15+00:00, book20_bid_proxy_usdt=27282, book20_ask_proxy_usdt=15732, funding_indicative=0.000050, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.65%, turnover=12249796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T22:30:02+00:00, last15m_closed_end=2026-10-28T22:30+00:00, prior8high=0.076200, depth_time=2026-10-28T22:30:09+00:00, book20_bid_proxy_usdt=1268714, book20_ask_proxy_usdt=1276502, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=12654271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T22:30:02+00:00, last15m_closed_end=2026-10-28T22:30+00:00, prior8high=601.750000, depth_time=2026-10-28T22:30:17+00:00, book20_bid_proxy_usdt=22321, book20_ask_proxy_usdt=9995, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.41%, turnover=5270428. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
