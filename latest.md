# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T01:45:29Z**
- feed_generated_utc: 2026-11-01T01:45:32+00:00
- source_sha256: `24c4e1a387f40fd69dd728121578340097074b816bbf461c8687a3d1fbfa3559`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T01:45+00:00, close=77720.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T01:00+00:00, close=77641.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.238940|-19.32|42.29|-19.52|29786532|1.25|
|BLESS_USDT|0.009473|-10.32|16.76|-10.52|7782489|2.11|
|ENA_USDT|0.188870|-2.64|1.11|-2.84|44354744|0.53|
|ZEC_USDT|1255.930000|-2.22|9.66|-2.42|1020265251|7.32|
|BTW_USDT|1.100700|-1.88|-36.78|-2.08|5475251|0.91|
|XLM_USDT|0.168670|-1.78|0.15|-1.98|20954567|0.59|
|Q_USDT|0.031620|-1.43|-59.94|-1.63|10013966|6.33|
|FARTCOIN_USDT|0.120750|-1.01|-1.00|-1.21|6450373|0.83|
|TRX_USDT|0.309390|-0.94|-5.94|-1.14|11178654|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009473|0.009328|0.009473|0.92|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.100700|1.049300|1.101700|1.76|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188870|0.188460|0.188870|0.61|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120750|0.119930|0.120750|0.40|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.238940|0.233000|0.238940|0.90|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031620|0.030180|0.031630|1.70|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.309390|0.301110|0.309390|0.29|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168670|0.168810|0.168690|1.49|Y|Y/N|N/N|Y|N|
|ZEC_USDT|1255.930000|1248.040000|1257.120000|0.97|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-11-01T01:45:02+00:00, last15m_closed_end=2026-11-01T01:45+00:00, prior8high=0.009626, depth_time=2026-11-01T01:45:10+00:00, book20_bid_proxy_usdt=15033, book20_ask_proxy_usdt=11251, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.32%, turnover=7782489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T01:45:02+00:00, last15m_closed_end=2026-11-01T01:45+00:00, prior8high=1.104900, depth_time=2026-11-01T01:45:17+00:00, book20_bid_proxy_usdt=16155, book20_ask_proxy_usdt=12662, funding_indicative=-0.000468, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=5475251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T01:45:02+00:00, last15m_closed_end=2026-11-01T01:45+00:00, prior8high=0.189790, depth_time=2026-11-01T01:45:13+00:00, book20_bid_proxy_usdt=185885, book20_ask_proxy_usdt=124030, funding_indicative=0.000044, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=44354744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T01:45:03+00:00, last15m_closed_end=2026-11-01T01:45+00:00, prior8high=0.120690, depth_time=2026-11-01T01:45:24+00:00, book20_bid_proxy_usdt=88489, book20_ask_proxy_usdt=82741, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.01%, turnover=6450373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T01:45:02+00:00, last15m_closed_end=2026-11-01T01:45+00:00, prior8high=0.253830, depth_time=2026-11-01T01:45:08+00:00, book20_bid_proxy_usdt=6776, book20_ask_proxy_usdt=4600, funding_indicative=-0.001648, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-19.32%, turnover=29786532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-01T01:45:02+00:00, last15m_closed_end=2026-11-01T01:45+00:00, prior8high=0.031540, depth_time=2026-11-01T01:45:23+00:00, book20_bid_proxy_usdt=55242, book20_ask_proxy_usdt=26913, funding_indicative=-0.000933, next_funding_utc=2026-11-01T02:00:00+00:00, funding_cycle_h=1, 24h_change=-1.43%, turnover=10013966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T01:45:02+00:00, last15m_closed_end=2026-11-01T01:45+00:00, prior8high=0.309020, depth_time=2026-11-01T01:45:25+00:00, book20_bid_proxy_usdt=61292, book20_ask_proxy_usdt=124945, funding_indicative=-0.001805, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=11178654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T01:45:03+00:00, last15m_closed_end=2026-11-01T01:45+00:00, prior8high=0.170090, depth_time=2026-11-01T01:45:20+00:00, book20_bid_proxy_usdt=196976, book20_ask_proxy_usdt=207089, funding_indicative=-0.000033, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=20954567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T01:45:02+00:00, last15m_closed_end=2026-11-01T01:45+00:00, prior8high=1263.460000, depth_time=2026-11-01T01:45:16+00:00, book20_bid_proxy_usdt=326580, book20_ask_proxy_usdt=500707, funding_indicative=-0.000094, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=1020265251. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
