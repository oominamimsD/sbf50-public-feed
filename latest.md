# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T11:30:21Z**
- feed_generated_utc: 2026-10-21T11:30:24+00:00
- source_sha256: `f69515458586ac0c2c6bf101461edbb9b8ac878261ed7dea404c48e492a6370a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T11:30+00:00, close=83453.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T11:00+00:00, close=83362.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.046456|-28.11|187.17|-29.17|6644285|4.33|
|BAT_USDT|0.182190|-15.56|2.71|-16.62|10631217|3.84|
|BR_USDT|0.587090|-9.77|35.58|-10.83|23111778|0.68|
|BTW_USDT|1.705700|-7.78|-12.64|-8.84|25262099|1.75|
|Q_USDT|0.118432|-3.52|187.96|-4.58|5378623|1.86|
|TIA_USDT|0.620700|-0.32|7.51|-1.38|47016191|1.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.046456|0.043233|0.046438|0.37|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.182190|0.181440|0.182220|0.28|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.587090|0.566870|0.587090|1.75|N|Y/Y|N/N|N|N|
|BTW_USDT|1.705700|1.665600|1.705700|1.26|N|Y/N|N/N|N|N|
|Q_USDT|0.118432|0.117302|0.118432|0.48|N|Y/Y|N/N|N|N|
|TIA_USDT|0.620700|0.614700|0.620700|0.78|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T11:30:02+00:00, last15m_closed_end=2026-10-21T11:30+00:00, prior8high=0.051865, depth_time=2026-10-21T11:30:08+00:00, book20_bid_proxy_usdt=6755, book20_ask_proxy_usdt=6599, funding_indicative=0.000047, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-28.11%, turnover=6644285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T11:30:02+00:00, last15m_closed_end=2026-10-21T11:30+00:00, prior8high=0.185160, depth_time=2026-10-21T11:30:11+00:00, book20_bid_proxy_usdt=31112, book20_ask_proxy_usdt=17838, funding_indicative=-0.000125, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.56%, turnover=10631217. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T11:30:02+00:00, last15m_closed_end=2026-10-21T11:30+00:00, prior8high=0.594360, depth_time=2026-10-21T11:30:13+00:00, book20_bid_proxy_usdt=2743, book20_ask_proxy_usdt=4255, funding_indicative=-0.000107, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.77%, turnover=23111778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T11:30:02+00:00, last15m_closed_end=2026-10-21T11:30+00:00, prior8high=2.135700, depth_time=2026-10-21T11:30:16+00:00, book20_bid_proxy_usdt=13093, book20_ask_proxy_usdt=12942, funding_indicative=-0.003353, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.78%, turnover=25262099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T11:30:02+00:00, last15m_closed_end=2026-10-21T11:30+00:00, prior8high=0.122802, depth_time=2026-10-21T11:30:14+00:00, book20_bid_proxy_usdt=21111, book20_ask_proxy_usdt=15122, funding_indicative=0.000024, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.52%, turnover=5378623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T11:30:02+00:00, last15m_closed_end=2026-10-21T11:30+00:00, prior8high=0.627200, depth_time=2026-10-21T11:30:21+00:00, book20_bid_proxy_usdt=218228, book20_ask_proxy_usdt=289009, funding_indicative=-0.000070, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.32%, turnover=47016191. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
