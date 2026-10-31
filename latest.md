# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T21:00:27Z**
- feed_generated_utc: 2026-10-31T21:00:29+00:00
- source_sha256: `cc2e75a1e2c856805715b325b75f2f5d8cebe42b20b4bd73055850e1ebdfe54a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T21:00+00:00, close=77523.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T21:00+00:00, close=77523.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.243730|-18.56|45.14|-18.74|27092680|2.05|
|IDOL_USDT|0.016664|-16.44|110.93|-16.62|6955643|1.20|
|BLESS_USDT|0.009573|-10.21|17.99|-10.39|7866932|1.05|
|TRX_USDT|0.303620|-3.69|-7.69|-3.87|9147263|0.33|
|Q_USDT|0.032250|-2.47|-59.14|-2.65|10455163|6.20|
|ENA_USDT|0.189120|-1.32|1.24|-1.50|46895880|0.53|
|FET_USDT|0.160200|-1.17|-7.02|-1.35|5349117|6.24|
|BTW_USDT|1.130400|-0.96|-35.08|-1.14|5849921|0.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009573|0.009882|0.009582|4.85|Y|Y/Y|Y/Y|Y|Y|
|BTW_USDT|1.130400|1.104400|1.130400|1.02|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.189120|0.188540|0.189120|0.15|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160200|0.160100|0.160200|0.97|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.016664|0.017265|0.016664|1.96|Y|Y/Y|N/N|Y|N|
|LSK_USDT|0.243730|0.237140|0.243730|0.64|N|Y/N|N/N|Y|N|
|Q_USDT|0.032250|0.032290|0.032250|0.18|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.303620|0.304670|0.303620|3.56|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-31T21:00:00+00:00, last15m_closed_end=2026-10-31T21:00+00:00, prior8high=0.010482, depth_time=2026-10-31T21:00:14+00:00, book20_bid_proxy_usdt=8941, book20_ask_proxy_usdt=7336, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.21%, turnover=7866932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T21:00:00+00:00, last15m_closed_end=2026-10-31T21:00+00:00, prior8high=1.134700, depth_time=2026-10-31T21:00:26+00:00, book20_bid_proxy_usdt=13400, book20_ask_proxy_usdt=14437, funding_indicative=-0.000072, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=5849921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-31T21:00:00+00:00, last15m_closed_end=2026-10-31T21:00+00:00, prior8high=0.191790, depth_time=2026-10-31T21:00:21+00:00, book20_bid_proxy_usdt=122407, book20_ask_proxy_usdt=300443, funding_indicative=-0.000015, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.32%, turnover=46895880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T21:00:00+00:00, last15m_closed_end=2026-10-31T21:00+00:00, prior8high=0.161800, depth_time=2026-10-31T21:00:22+00:00, book20_bid_proxy_usdt=1290825, book20_ask_proxy_usdt=1077531, funding_indicative=-0.000149, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=5349117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T21:00:00+00:00, last15m_closed_end=2026-10-31T21:00+00:00, prior8high=0.018263, depth_time=2026-10-31T21:00:11+00:00, book20_bid_proxy_usdt=6400, book20_ask_proxy_usdt=11668, funding_indicative=0.000064, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.44%, turnover=6955643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T21:00:00+00:00, last15m_closed_end=2026-10-31T21:00+00:00, prior8high=0.284740, depth_time=2026-10-31T21:00:08+00:00, book20_bid_proxy_usdt=10283, book20_ask_proxy_usdt=7165, funding_indicative=-0.000842, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-18.56%, turnover=27092680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T21:00:00+00:00, last15m_closed_end=2026-10-31T21:00+00:00, prior8high=0.033780, depth_time=2026-10-31T21:00:18+00:00, book20_bid_proxy_usdt=51369, book20_ask_proxy_usdt=56835, funding_indicative=-0.000696, next_funding_utc=2026-10-31T22:00:00+00:00, funding_cycle_h=1, 24h_change=-2.47%, turnover=10455163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T21:00:00+00:00, last15m_closed_end=2026-10-31T21:00+00:00, prior8high=0.310030, depth_time=2026-10-31T21:00:15+00:00, book20_bid_proxy_usdt=47326, book20_ask_proxy_usdt=66498, funding_indicative=-0.000453, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=9147263. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
