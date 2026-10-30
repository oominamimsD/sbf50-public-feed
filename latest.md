# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T18:45:32Z**
- feed_generated_utc: 2026-10-30T18:45:35+00:00
- source_sha256: `cce1991e86303ff02b5a3a64c49fb2085c9332971a6992f758e9770697041701`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T18:45+00:00, close=76683.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T18:00+00:00, close=77152, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.087200|-15.20|107.12|-14.06|6745077|2.75|
|BLESS_USDT|0.008831|-10.35|8.20|-9.21|16946664|1.14|
|Q_USDT|0.045730|-3.68|-61.35|-2.54|24870791|2.18|
|LIT_USDT|2.728500|-3.38|-17.91|-2.24|12629066|0.37|
|PUMPFUN_USDT|0.003970|-3.33|-12.99|-2.19|25907146|2.52|
|HYPE_USDT|89.430000|-3.15|14.06|-2.01|215862645|0.11|
|ENA_USDT|0.183980|-3.10|-11.10|-1.96|113373748|0.54|
|INJ_USDT|6.909000|-3.00|-12.24|-1.86|33276771|1.45|
|FARTCOIN_USDT|0.117000|-2.74|-20.73|-1.60|15772208|0.85|
|ETHFI_USDT|0.585800|-2.46|-10.26|-1.32|6533499|1.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.008831|0.008535|0.008825|0.85|N|Y/Y|Y/N|Y|N|
|ENA_USDT|0.183980|0.184340|0.184020|0.81|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.585800|0.587600|0.585800|1.17|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.087200|1.212900|1.087200|2.82|Y|Y/N|N/N|Y|N|
|FARTCOIN_USDT|0.117000|0.117390|0.116960|1.07|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|89.430000|89.882000|89.318000|0.96|N|Y/N|N/N|Y|N|
|INJ_USDT|6.909000|6.954000|6.909000|3.26|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|2.728500|2.687900|2.728500|0.41|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003970|0.003954|0.003970|0.14|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.045730|0.044540|0.045730|0.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T18:45:02+00:00, last15m_closed_end=2026-10-30T18:45+00:00, prior8high=0.009789, depth_time=2026-10-30T18:45:12+00:00, book20_bid_proxy_usdt=10610, book20_ask_proxy_usdt=16336, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-10.35%, turnover=16946664. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-30T18:45:02+00:00, last15m_closed_end=2026-10-30T18:45+00:00, prior8high=0.191630, depth_time=2026-10-30T18:45:24+00:00, book20_bid_proxy_usdt=109895, book20_ask_proxy_usdt=177768, funding_indicative=0.000004, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.10%, turnover=113373748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T18:45:03+00:00, last15m_closed_end=2026-10-30T18:45+00:00, prior8high=0.601100, depth_time=2026-10-30T18:45:29+00:00, book20_bid_proxy_usdt=271234, book20_ask_proxy_usdt=164541, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=6533499. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T18:45:02+00:00, last15m_closed_end=2026-10-30T18:45+00:00, prior8high=1.298300, depth_time=2026-10-30T18:45:10+00:00, book20_bid_proxy_usdt=5849, book20_ask_proxy_usdt=8050, funding_indicative=0.000170, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-15.20%, turnover=6745077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T18:45:02+00:00, last15m_closed_end=2026-10-30T18:45+00:00, prior8high=0.121510, depth_time=2026-10-30T18:45:28+00:00, book20_bid_proxy_usdt=52811, book20_ask_proxy_usdt=56859, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=15772208. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T18:45:02+00:00, last15m_closed_end=2026-10-30T18:45+00:00, prior8high=92.513000, depth_time=2026-10-30T18:45:21+00:00, book20_bid_proxy_usdt=254507, book20_ask_proxy_usdt=139166, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=215862645. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T18:45:02+00:00, last15m_closed_end=2026-10-30T18:45+00:00, prior8high=7.167000, depth_time=2026-10-30T18:45:26+00:00, book20_bid_proxy_usdt=126388, book20_ask_proxy_usdt=320306, funding_indicative=0.000016, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=33276771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T18:45:02+00:00, last15m_closed_end=2026-10-30T18:45+00:00, prior8high=2.830000, depth_time=2026-10-30T18:45:16+00:00, book20_bid_proxy_usdt=23297, book20_ask_proxy_usdt=21776, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=12629066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T18:45:02+00:00, last15m_closed_end=2026-10-30T18:45+00:00, prior8high=0.004103, depth_time=2026-10-30T18:45:19+00:00, book20_bid_proxy_usdt=475213, book20_ask_proxy_usdt=1090570, funding_indicative=-0.000008, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=25907146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T18:45:02+00:00, last15m_closed_end=2026-10-30T18:45+00:00, prior8high=0.049120, depth_time=2026-10-30T18:45:13+00:00, book20_bid_proxy_usdt=21536, book20_ask_proxy_usdt=18321, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.68%, turnover=24870791. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
