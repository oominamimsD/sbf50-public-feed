# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T10:30:35Z**
- feed_generated_utc: 2026-11-08T10:30:37+00:00
- source_sha256: `d0646bd32450add9e2e63ce8a0541cec3aaa011cb5eb53302f9860932cf3671b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T10:30+00:00, close=75840.5, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T10:00+00:00, close=75899.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.424900|-3.78|-13.30|-3.93|7447357|2.35|
|ENA_USDT|0.152950|-3.30|-21.16|-3.45|29105932|0.65|
|WLD_USDT|0.327600|-2.38|-18.99|-2.53|24114035|3.05|
|AAVE_USDT|130.070000|-1.63|-4.01|-1.78|10363810|0.77|
|IDOL_USDT|0.032898|-1.19|87.76|-1.34|16384461|0.30|
|ADA_USDT|0.179500|-1.15|-7.28|-1.30|10002301|5.57|
|SUI_USDT|0.847300|-1.14|-6.06|-1.29|21845163|1.18|
|DOGE_USDT|0.070780|-1.11|-6.42|-1.26|40128881|1.41|
|ONDO_USDT|0.359200|-1.07|-12.90|-1.22|8064475|2.78|
|LINK_USDT|10.738000|-0.97|-7.19|-1.12|63692425|0.93|
|XLM_USDT|0.149790|-0.95|-12.78|-1.10|16855417|0.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.070000|129.470000|130.070000|0.84|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179500|0.178900|0.179500|2.72|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.070780|0.070450|0.070780|0.61|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.152950|0.152950|0.152950|9.20|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.032898|0.032213|0.032898|0.85|N|N/N|N/N|Y|N|
|LINK_USDT|10.738000|10.704000|10.738000|0.79|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359200|0.358000|0.359200|0.87|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.847300|0.846700|0.847300|1.83|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.424900|0.424900|0.424900|1.34|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.327600|0.325700|0.327600|0.52|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.149790|0.149640|0.149790|1.88|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T10:30:01+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=130.820000, depth_time=2026-11-08T10:30:15+00:00, book20_bid_proxy_usdt=1117626, book20_ask_proxy_usdt=410708, funding_indicative=0.000028, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=10363810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T10:30:01+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=0.180300, depth_time=2026-11-08T10:30:20+00:00, book20_bid_proxy_usdt=11594650, book20_ask_proxy_usdt=7942927, funding_indicative=-0.000058, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=10002301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-08T10:30:01+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=0.071200, depth_time=2026-11-08T10:30:25+00:00, book20_bid_proxy_usdt=3789520, book20_ask_proxy_usdt=6128284, funding_indicative=0.000066, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=40128881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T10:30:01+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=0.154630, depth_time=2026-11-08T10:30:09+00:00, book20_bid_proxy_usdt=323824, book20_ask_proxy_usdt=315532, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=29105932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T10:30:00+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=0.034724, depth_time=2026-11-08T10:30:17+00:00, book20_bid_proxy_usdt=4826, book20_ask_proxy_usdt=11429, funding_indicative=0.000459, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.19%, turnover=16384461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T10:30:01+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=10.775000, depth_time=2026-11-08T10:30:32+00:00, book20_bid_proxy_usdt=886217, book20_ask_proxy_usdt=422953, funding_indicative=0.000037, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=63692425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T10:30:01+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=0.360700, depth_time=2026-11-08T10:30:23+00:00, book20_bid_proxy_usdt=1970683, book20_ask_proxy_usdt=1612434, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.07%, turnover=8064475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T10:30:01+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=0.853300, depth_time=2026-11-08T10:30:21+00:00, book20_bid_proxy_usdt=1616888, book20_ask_proxy_usdt=1193313, funding_indicative=-0.000006, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=21845163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T10:30:00+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=0.429600, depth_time=2026-11-08T10:30:04+00:00, book20_bid_proxy_usdt=389592, book20_ask_proxy_usdt=339230, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.78%, turnover=7447357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T10:30:01+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=0.330000, depth_time=2026-11-08T10:30:09+00:00, book20_bid_proxy_usdt=4100188, book20_ask_proxy_usdt=4317651, funding_indicative=-0.000061, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=24114035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-08T10:30:01+00:00, last15m_closed_end=2026-11-08T10:30+00:00, prior8high=0.150640, depth_time=2026-11-08T10:30:32+00:00, book20_bid_proxy_usdt=209386, book20_ask_proxy_usdt=186064, funding_indicative=-0.000067, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=16855417. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
