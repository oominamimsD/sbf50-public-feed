# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T06:15:33Z**
- feed_generated_utc: 2026-10-17T06:15:35+00:00
- source_sha256: `357ed4602e604f00e1654d0b3ee34816ef10bcfcee2a75e71faeab794ae04e07`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T06:15+00:00, close=81579.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T06:00+00:00, close=81542.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.969100|-6.29|-3.32|-6.61|13953683|1.02|
|BAT_USDT|0.196480|-4.17|61.49|-4.49|14212025|3.06|
|STRK_USDT|0.070920|-4.09|-5.82|-4.41|21554586|1.41|
|ARB_USDT|0.189570|-2.75|4.85|-3.07|32267760|0.53|
|FET_USDT|0.194800|-2.40|-10.23|-2.72|12024898|5.13|
|OP_USDT|0.136970|-2.16|11.15|-2.48|14624022|0.73|
|APT_USDT|0.839500|-1.93|4.87|-2.25|11778716|1.19|
|ZEC_USDT|1165.220000|-1.91|-4.36|-2.23|1355450228|0.09|
|TAO_USDT|275.760000|-1.73|0.39|-2.05|70275461|1.09|
|SUI_USDT|1.010300|-0.99|-4.47|-1.31|92812834|0.99|
|AVAX_USDT|10.002000|-0.80|-1.86|-1.12|116162764|2.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.839500|0.837900|0.839500|1.96|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189570|0.189070|0.189570|1.20|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|10.002000|9.968000|10.003000|0.59|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.196480|0.194790|0.196500|0.20|N|Y/N|N/N|Y|N|
|FET_USDT|0.194800|0.194100|0.194800|5.55|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.136970|0.136910|0.136970|1.73|N|Y/N|Y/Y|Y|N|
|STRK_USDT|0.070920|0.070440|0.070920|0.27|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.010300|1.009200|1.010300|1.10|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.760000|274.400000|275.800000|0.40|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1165.220000|1150.950000|1165.070000|1.11|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.969100|1.960500|1.969100|0.34|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=0.856200, depth_time=2026-10-17T06:15:22+00:00, book20_bid_proxy_usdt=127115, book20_ask_proxy_usdt=128976, funding_indicative=0.000070, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=11778716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=0.192330, depth_time=2026-10-17T06:15:14+00:00, book20_bid_proxy_usdt=80265, book20_ask_proxy_usdt=59309, funding_indicative=-0.000026, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=32267760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=10.037000, depth_time=2026-10-17T06:15:32+00:00, book20_bid_proxy_usdt=632031, book20_ask_proxy_usdt=576034, funding_indicative=0.000048, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.80%, turnover=116162764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=0.203010, depth_time=2026-10-17T06:15:08+00:00, book20_bid_proxy_usdt=19158, book20_ask_proxy_usdt=16944, funding_indicative=-0.000061, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.17%, turnover=14212025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=0.196300, depth_time=2026-10-17T06:15:17+00:00, book20_bid_proxy_usdt=1780378, book20_ask_proxy_usdt=1482619, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=12024898. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=0.140730, depth_time=2026-10-17T06:15:19+00:00, book20_bid_proxy_usdt=47701, book20_ask_proxy_usdt=51452, funding_indicative=-0.000055, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=14624022. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=0.072130, depth_time=2026-10-17T06:15:12+00:00, book20_bid_proxy_usdt=463054, book20_ask_proxy_usdt=258239, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.09%, turnover=21554586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=1.019400, depth_time=2026-10-17T06:15:29+00:00, book20_bid_proxy_usdt=1023639, book20_ask_proxy_usdt=724289, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=92812834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=277.150000, depth_time=2026-10-17T06:15:25+00:00, book20_bid_proxy_usdt=143162, book20_ask_proxy_usdt=71281, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=70275461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=1168.180000, depth_time=2026-10-17T06:15:25+00:00, book20_bid_proxy_usdt=77226, book20_ask_proxy_usdt=701290, funding_indicative=0.000007, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=1355450228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T06:15:01+00:00, last15m_closed_end=2026-10-17T06:15+00:00, prior8high=1.992900, depth_time=2026-10-17T06:15:07+00:00, book20_bid_proxy_usdt=77352, book20_ask_proxy_usdt=26848, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.29%, turnover=13953683. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
