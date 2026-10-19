# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T07:00:16Z**
- feed_generated_utc: 2026-10-19T07:00:18+00:00
- source_sha256: `1bb019887e39b6ecaa90cbd6324fb53da690425bdcef493d117c5261f6412d7a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T07:00+00:00, close=82812.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T07:00+00:00, close=82812.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.169700|-7.77|60.09|-9.83|7022868|5.89|
|BTW_USDT|2.246000|-4.35|33.51|-6.41|21523974|1.34|
|HBAR_USDT|0.084480|-3.23|-9.91|-5.29|49330853|1.18|
|STRK_USDT|0.059740|-1.77|-49.91|-3.83|17344739|1.68|
|TIA_USDT|0.609900|-0.31|3.60|-2.37|56489045|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.246000|2.166400|2.246000|1.45|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084480|0.083810|0.084480|0.62|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.169700|0.168800|0.169700|0.52|N|Y/Y|N/N|N|N|
|STRK_USDT|0.059740|0.059530|0.059740|0.77|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.609900|0.604400|0.609900|0.92|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T07:00:01+00:00, last15m_closed_end=2026-10-19T07:00+00:00, prior8high=2.321000, depth_time=2026-10-19T07:00:08+00:00, book20_bid_proxy_usdt=9868, book20_ask_proxy_usdt=13915, funding_indicative=-0.000189, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.35%, turnover=21523974. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T07:00:01+00:00, last15m_closed_end=2026-10-19T07:00+00:00, prior8high=0.084640, depth_time=2026-10-19T07:00:11+00:00, book20_bid_proxy_usdt=869160, book20_ask_proxy_usdt=1254421, funding_indicative=-0.000039, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=49330853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T07:00:01+00:00, last15m_closed_end=2026-10-19T07:00+00:00, prior8high=0.194500, depth_time=2026-10-19T07:00:07+00:00, book20_bid_proxy_usdt=139568, book20_ask_proxy_usdt=119485, funding_indicative=-0.000111, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.77%, turnover=7022868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T07:00:01+00:00, last15m_closed_end=2026-10-19T07:00+00:00, prior8high=0.060780, depth_time=2026-10-19T07:00:13+00:00, book20_bid_proxy_usdt=884885, book20_ask_proxy_usdt=644205, funding_indicative=0.000050, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=17344739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T07:00:01+00:00, last15m_closed_end=2026-10-19T07:00+00:00, prior8high=0.616500, depth_time=2026-10-19T07:00:15+00:00, book20_bid_proxy_usdt=164490, book20_ask_proxy_usdt=291832, funding_indicative=-0.000034, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.31%, turnover=56489045. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
