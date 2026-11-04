# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T05:15:24Z**
- feed_generated_utc: 2026-11-04T05:15:26+00:00
- source_sha256: `d0f1d4b2cd6844f7c70a60fa87d31467db11ef8e79cb1275544ce93de7ba7af9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T05:15+00:00, close=77358.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T05:00+00:00, close=77357.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.037010|-31.22|-22.11|-30.83|11603273|2.70|
|AKE_USDT|0.003078|-25.93|-85.42|-25.54|12172048|3.25|
|ICNT_USDT|0.210700|-9.76|18.83|-9.37|5158530|4.75|
|TRUMPOFFICIAL_USDT|1.504000|-6.46|-10.90|-6.07|8182364|6.65|
|XPL_USDT|0.062200|-2.88|-15.74|-2.49|7397731|1.61|
|XLM_USDT|0.160830|-2.40|-4.95|-2.01|37579346|1.24|
|Q_USDT|0.027580|-2.09|-56.62|-1.70|7354812|3.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.037010|0.036380|0.037010|0.59|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003078|0.003124|0.003079|2.29|Y|Y/Y|Y/Y|Y|Y|
|ICNT_USDT|0.210700|0.209800|0.210200|0.45|N|Y/Y|N/N|Y|N|
|Q_USDT|0.027580|0.027600|0.027580|0.69|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.504000|1.475000|1.507000|0.24|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.160830|0.156990|0.160820|0.70|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.062200|0.060070|0.062200|1.16|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T05:15:03+00:00, last15m_closed_end=2026-11-04T05:15+00:00, prior8high=0.038690, depth_time=2026-11-04T05:15:08+00:00, book20_bid_proxy_usdt=24086, book20_ask_proxy_usdt=40620, funding_indicative=0.000075, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-31.22%, turnover=11603273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T05:15:03+00:00, last15m_closed_end=2026-11-04T05:15+00:00, prior8high=0.003654, depth_time=2026-11-04T05:15:10+00:00, book20_bid_proxy_usdt=64912, book20_ask_proxy_usdt=38497, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-25.93%, turnover=12172048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-11-04T05:15:03+00:00, last15m_closed_end=2026-11-04T05:15+00:00, prior8high=0.218200, depth_time=2026-11-04T05:15:12+00:00, book20_bid_proxy_usdt=156268, book20_ask_proxy_usdt=116987, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.76%, turnover=5158530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T05:15:03+00:00, last15m_closed_end=2026-11-04T05:15+00:00, prior8high=0.028470, depth_time=2026-11-04T05:15:22+00:00, book20_bid_proxy_usdt=83080, book20_ask_proxy_usdt=45034, funding_indicative=-0.000549, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=7354812. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T05:15:03+00:00, last15m_closed_end=2026-11-04T05:15+00:00, prior8high=1.519000, depth_time=2026-11-04T05:15:15+00:00, book20_bid_proxy_usdt=1939232, book20_ask_proxy_usdt=2030125, funding_indicative=-0.000217, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.46%, turnover=8182364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T05:15:03+00:00, last15m_closed_end=2026-11-04T05:15+00:00, prior8high=0.161230, depth_time=2026-11-04T05:15:20+00:00, book20_bid_proxy_usdt=148005, book20_ask_proxy_usdt=127826, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=37579346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T05:15:03+00:00, last15m_closed_end=2026-11-04T05:15+00:00, prior8high=0.062060, depth_time=2026-11-04T05:15:17+00:00, book20_bid_proxy_usdt=448010, book20_ask_proxy_usdt=508730, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.88%, turnover=7397731. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
