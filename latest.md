# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T01:30:22Z**
- feed_generated_utc: 2026-10-15T01:30:24+00:00
- source_sha256: `11758b99a4f4618a08bc437d6cc6ada1fed19428dd34978b6aebfc311236e3e3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T01:30+00:00, close=81543.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T01:00+00:00, close=81624.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PONS_USDT|0.310300|-9.79|-24.40|-9.73|7024780|9.67|
|BAT_USDT|0.168460|-3.41|69.88|-3.35|23617661|0.59|
|FET_USDT|0.197800|-2.99|-12.67|-2.93|10972552|5.06|
|FARTCOIN_USDT|0.153390|-2.07|-4.23|-2.01|8010613|2.61|
|AAVE_USDT|153.450000|-1.56|-10.66|-1.50|25874709|1.30|
|NEAR_USDT|4.778000|-1.30|-5.08|-1.24|179632467|2.09|
|QNT_USDT|202.720000|-1.12|-16.50|-1.06|95087735|0.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.450000|153.330000|153.450000|0.40|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.168460|0.168550|0.168500|1.46|Y|Y/Y|N/N|Y|N|
|FARTCOIN_USDT|0.153390|0.153170|0.153390|1.62|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.197800|0.196700|0.197800|1.61|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.778000|4.809000|4.777000|1.48|Y|Y/Y|Y/Y|Y|Y|
|PONS_USDT|0.310300|0.308400|0.310400|0.95|N|Y/Y|N/N|Y|N|
|QNT_USDT|202.720000|202.170000|202.720000|1.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-15T01:30:00+00:00, last15m_closed_end=2026-10-15T01:30+00:00, prior8high=154.480000, depth_time=2026-10-15T01:30:16+00:00, book20_bid_proxy_usdt=285403, book20_ask_proxy_usdt=322781, funding_indicative=0.000045, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=25874709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-15T01:30:00+00:00, last15m_closed_end=2026-10-15T01:30+00:00, prior8high=0.178290, depth_time=2026-10-15T01:30:09+00:00, book20_bid_proxy_usdt=28209, book20_ask_proxy_usdt=26367, funding_indicative=0.000007, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=23617661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-15T01:30:00+00:00, last15m_closed_end=2026-10-15T01:30+00:00, prior8high=0.156870, depth_time=2026-10-15T01:30:14+00:00, book20_bid_proxy_usdt=48133, book20_ask_proxy_usdt=38150, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=8010613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-15T01:30:00+00:00, last15m_closed_end=2026-10-15T01:30+00:00, prior8high=0.200300, depth_time=2026-10-15T01:30:11+00:00, book20_bid_proxy_usdt=1345458, book20_ask_proxy_usdt=908750, funding_indicative=-0.000034, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=10972552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-15T01:30:00+00:00, last15m_closed_end=2026-10-15T01:30+00:00, prior8high=4.925000, depth_time=2026-10-15T01:30:19+00:00, book20_bid_proxy_usdt=767879, book20_ask_proxy_usdt=791740, funding_indicative=0.000100, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=179632467. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-15T01:30:00+00:00, last15m_closed_end=2026-10-15T01:30+00:00, prior8high=0.335800, depth_time=2026-10-15T01:30:06+00:00, book20_bid_proxy_usdt=165866, book20_ask_proxy_usdt=190709, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.79%, turnover=7024780. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-15T01:30:00+00:00, last15m_closed_end=2026-10-15T01:30+00:00, prior8high=206.710000, depth_time=2026-10-15T01:30:21+00:00, book20_bid_proxy_usdt=52485, book20_ask_proxy_usdt=65366, funding_indicative=0.000020, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=95087735. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
