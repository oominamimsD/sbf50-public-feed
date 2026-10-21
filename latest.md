# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T09:45:26Z**
- feed_generated_utc: 2026-10-21T09:45:28+00:00
- source_sha256: `7220357f717e474cd92921a145e514a11615a3301d5a1aad666750cd6906321a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T09:45+00:00, close=83400, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T09:00+00:00, close=83217, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.182670|-15.34|2.98|-16.33|11093536|1.64|
|BR_USDT|0.585820|-9.96|35.29|-10.95|26707909|0.17|
|Q_USDT|0.120692|-1.68|193.46|-2.67|5891551|9.85|
|SILVER_USDT|57.490000|-0.79|-3.19|-1.78|216859831|1.74|
|DOT_USDT|1.153000|-0.39|-0.33|-1.38|13814016|0.87|
|XAU_USDT|4130.210000|-0.22|-0.84|-1.21|391565695|0.02|
|TIA_USDT|0.621900|-0.12|7.72|-1.11|47028950|1.61|
|XAUT_USDT|4124.060000|-0.09|-0.78|-1.08|163380780|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.182670|0.182390|0.182740|0.90|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.585820|0.575440|0.585450|0.68|N|Y/Y|N/N|N|N|
|DOT_USDT|1.153000|1.154900|1.153000|0.63|N|N/N|N/N|N|N|
|Q_USDT|0.120692|0.120575|0.120692|0.58|N|Y/N|N/N|N|N|
|SILVER_USDT|57.490000|57.310000|57.500000|2.52|N|Y/Y|N/N|N|N|
|TIA_USDT|0.621900|0.623400|0.622300|2.25|Y|N/N|N/Y|N|N|
|XAUT_USDT|4124.060000|4117.940000|4124.060000|1.65|N|Y/Y|Y/Y|N|N|
|XAU_USDT|4130.210000|4125.700000|4130.210000|1.31|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-21T09:45:01+00:00, last15m_closed_end=2026-10-21T09:45+00:00, prior8high=0.190510, depth_time=2026-10-21T09:45:07+00:00, book20_bid_proxy_usdt=21943, book20_ask_proxy_usdt=34280, funding_indicative=-0.000116, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.34%, turnover=11093536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T09:45:01+00:00, last15m_closed_end=2026-10-21T09:45+00:00, prior8high=0.627970, depth_time=2026-10-21T09:45:10+00:00, book20_bid_proxy_usdt=5533, book20_ask_proxy_usdt=2989, funding_indicative=-0.000018, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.96%, turnover=26707909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T09:45:01+00:00, last15m_closed_end=2026-10-21T09:45+00:00, prior8high=1.169700, depth_time=2026-10-21T09:45:18+00:00, book20_bid_proxy_usdt=474100, book20_ask_proxy_usdt=304894, funding_indicative=-0.000191, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.39%, turnover=13814016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T09:45:01+00:00, last15m_closed_end=2026-10-21T09:45+00:00, prior8high=0.146637, depth_time=2026-10-21T09:45:12+00:00, book20_bid_proxy_usdt=15161, book20_ask_proxy_usdt=17295, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=5891551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T09:45:01+00:00, last15m_closed_end=2026-10-21T09:45+00:00, prior8high=57.550000, depth_time=2026-10-21T09:45:15+00:00, book20_bid_proxy_usdt=34576092, book20_ask_proxy_usdt=35049205, funding_indicative=0.000037, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.79%, turnover=216859831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T09:45:01+00:00, last15m_closed_end=2026-10-21T09:45+00:00, prior8high=0.642000, depth_time=2026-10-21T09:45:23+00:00, book20_bid_proxy_usdt=374811, book20_ask_proxy_usdt=352988, funding_indicative=-0.000076, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.12%, turnover=47028950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-21T09:45:01+00:00, last15m_closed_end=2026-10-21T09:45+00:00, prior8high=4125.380000, depth_time=2026-10-21T09:45:24+00:00, book20_bid_proxy_usdt=202183, book20_ask_proxy_usdt=135086, funding_indicative=0.000048, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.09%, turnover=163380780. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-21T09:45:01+00:00, last15m_closed_end=2026-10-21T09:45+00:00, prior8high=4132.430000, depth_time=2026-10-21T09:45:18+00:00, book20_bid_proxy_usdt=368184, book20_ask_proxy_usdt=1505837, funding_indicative=0.000060, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.22%, turnover=391565695. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
