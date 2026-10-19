# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T02:30:23Z**
- feed_generated_utc: 2026-10-19T02:30:25+00:00
- source_sha256: `9278cd9a5f5069126dbadad648a947f1f47e8d5452c521ea89af732b9e6ab398`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T02:30+00:00, close=82342.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T02:00+00:00, close=82415, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T00:00+00:00, close=82076.8, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.110646|-9.28|290.67|-10.75|9474604|0.63|
|AGT_USDT|0.063201|-6.40|257.37|-7.87|9039264|1.90|
|HBAR_USDT|0.083830|-2.27|-10.60|-3.74|51511853|1.19|
|BAT_USDT|0.171700|-2.09|3.03|-3.56|6388799|1.17|
|STRK_USDT|0.060880|-1.10|-48.95|-2.57|17219808|1.64|
|BTW_USDT|2.285600|-0.85|35.86|-2.32|22197338|0.88|
|ICNT_USDT|0.179100|-0.16|68.96|-1.63|7676197|5.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.063201|0.061150|0.063201|0.32|N|Y/Y|N/N|N|N|
|BAT_USDT|0.171700|0.171530|0.171700|0.51|N|Y/Y|Y/Y|N|N|
|BTW_USDT|2.285600|2.230700|2.289800|0.41|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.083830|0.083840|0.083830|1.29|N|Y/Y|N/Y|N|N|
|ICNT_USDT|0.179100|0.175900|0.179100|1.85|N|Y/Y|N/N|N|N|
|Q_USDT|0.110646|0.106082|0.110646|0.51|N|Y/Y|N/N|N|N|
|STRK_USDT|0.060880|0.059770|0.060880|0.35|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-19T02:30:00+00:00, last15m_closed_end=2026-10-19T02:30+00:00, prior8high=0.066453, depth_time=2026-10-19T02:30:08+00:00, book20_bid_proxy_usdt=5858, book20_ask_proxy_usdt=3505, funding_indicative=0.000134, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.40%, turnover=9039264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-19T02:30:00+00:00, last15m_closed_end=2026-10-19T02:30+00:00, prior8high=0.176680, depth_time=2026-10-19T02:30:14+00:00, book20_bid_proxy_usdt=17481, book20_ask_proxy_usdt=28541, funding_indicative=0.000100, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=6388799. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-19T02:30:00+00:00, last15m_closed_end=2026-10-19T02:30+00:00, prior8high=2.381700, depth_time=2026-10-19T02:30:20+00:00, book20_bid_proxy_usdt=13222, book20_ask_proxy_usdt=13920, funding_indicative=-0.000333, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.85%, turnover=22197338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T02:30:00+00:00, last15m_closed_end=2026-10-19T02:30+00:00, prior8high=0.085000, depth_time=2026-10-19T02:30:12+00:00, book20_bid_proxy_usdt=383992, book20_ask_proxy_usdt=1041873, funding_indicative=-0.000027, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=51511853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T02:30:00+00:00, last15m_closed_end=2026-10-19T02:30+00:00, prior8high=0.189900, depth_time=2026-10-19T02:30:22+00:00, book20_bid_proxy_usdt=198811, book20_ask_proxy_usdt=136417, funding_indicative=0.000000, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.16%, turnover=7676197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T02:30:00+00:00, last15m_closed_end=2026-10-19T02:30+00:00, prior8high=0.118711, depth_time=2026-10-19T02:30:08+00:00, book20_bid_proxy_usdt=6497, book20_ask_proxy_usdt=6995, funding_indicative=0.000050, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.28%, turnover=9474604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T02:30:00+00:00, last15m_closed_end=2026-10-19T02:30+00:00, prior8high=0.061960, depth_time=2026-10-19T02:30:17+00:00, book20_bid_proxy_usdt=428504, book20_ask_proxy_usdt=255471, funding_indicative=0.000016, next_funding_utc=2026-10-19T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=17219808. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
