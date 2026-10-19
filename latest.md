# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T02:15:21Z**
- feed_generated_utc: 2026-10-19T02:15:23+00:00
- source_sha256: `e720690d76cfa45b16f98da2b3a84f501838597df82b52fbd4beb0879ee98561`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T02:15+00:00, close=82539.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T02:00+00:00, close=82415, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.111621|-8.48|294.11|-10.20|9459931|3.58|
|AGT_USDT|0.063247|-6.34|257.63|-8.06|9028500|9.96|
|BAT_USDT|0.171940|-1.96|3.18|-3.68|6371087|0.58|
|HBAR_USDT|0.084420|-1.58|-9.98|-3.30|51224466|1.19|
|ICNT_USDT|0.179100|-0.16|68.96|-1.88|7642257|5.59|
|BTW_USDT|2.311200|0.25|37.39|-1.47|22131088|1.73|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.063247|0.061150|0.063247|0.51|N|Y/Y|N/N|N|N|
|BAT_USDT|0.171940|0.173900|0.171940|1.63|Y|Y/Y|Y/Y|N|Y|
|BTW_USDT|2.311200|2.230700|2.311200|0.83|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084420|0.083840|0.084420|0.95|N|Y/Y|N/Y|N|N|
|ICNT_USDT|0.179100|0.175900|0.179100|1.15|N|Y/Y|N/N|N|N|
|Q_USDT|0.111621|0.106228|0.111479|1.45|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T02:15:01+00:00, last15m_closed_end=2026-10-19T02:15+00:00, prior8high=0.067363, depth_time=2026-10-19T02:15:11+00:00, book20_bid_proxy_usdt=4952, book20_ask_proxy_usdt=7688, funding_indicative=0.000141, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.34%, turnover=9028500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-19T02:15:01+00:00, last15m_closed_end=2026-10-19T02:15+00:00, prior8high=0.176800, depth_time=2026-10-19T02:15:14+00:00, book20_bid_proxy_usdt=21897, book20_ask_proxy_usdt=23604, funding_indicative=0.000100, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=6371087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T02:15:01+00:00, last15m_closed_end=2026-10-19T02:15+00:00, prior8high=2.408500, depth_time=2026-10-19T02:15:20+00:00, book20_bid_proxy_usdt=9208, book20_ask_proxy_usdt=8296, funding_indicative=-0.000369, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=0.25%, turnover=22131088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T02:15:01+00:00, last15m_closed_end=2026-10-19T02:15+00:00, prior8high=0.085430, depth_time=2026-10-19T02:15:15+00:00, book20_bid_proxy_usdt=644825, book20_ask_proxy_usdt=942299, funding_indicative=-0.000025, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=51224466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T02:15:01+00:00, last15m_closed_end=2026-10-19T02:15+00:00, prior8high=0.189900, depth_time=2026-10-19T02:15:18+00:00, book20_bid_proxy_usdt=160432, book20_ask_proxy_usdt=138767, funding_indicative=-0.000003, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.16%, turnover=7642257. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T02:15:01+00:00, last15m_closed_end=2026-10-19T02:15+00:00, prior8high=0.118711, depth_time=2026-10-19T02:15:09+00:00, book20_bid_proxy_usdt=7841, book20_ask_proxy_usdt=10356, funding_indicative=0.000050, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.48%, turnover=9459931. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
