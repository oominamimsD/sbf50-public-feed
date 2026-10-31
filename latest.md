# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T00:45:19Z**
- feed_generated_utc: 2026-10-31T00:45:21+00:00
- source_sha256: `86ba34a2a306c5d8ee6fe43a1e14558af9d1f249b4fa7c4bc1855f38f8168842`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T00:45+00:00, close=77381.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013761|-27.27|-60.67|-27.01|5924854|0.73|
|Q_USDT|0.043180|-9.05|-63.51|-8.79|18961290|6.95|
|BTW_USDT|1.124300|-6.26|-33.95|-6.00|9856476|4.45|
|TRX_USDT|0.324450|-3.29|-1.48|-3.03|9821249|0.31|
|HYPE_USDT|89.998000|-2.54|14.78|-2.28|140066114|0.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013761|0.013043|0.013761|0.91|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.124300|1.135400|1.124000|0.95|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|89.998000|89.059000|90.011000|0.49|N|Y/Y|N/N|Y|N|
|Q_USDT|0.043180|0.047030|0.043090|3.74|Y|N/N|Y/Y|Y|N|
|TRX_USDT|0.324450|0.325870|0.324450|2.86|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T00:45:01+00:00, last15m_closed_end=2026-10-31T00:45+00:00, prior8high=0.014277, depth_time=2026-10-31T00:45:08+00:00, book20_bid_proxy_usdt=2638, book20_ask_proxy_usdt=6155, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-27.27%, turnover=5924854. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T00:45:01+00:00, last15m_closed_end=2026-10-31T00:45+00:00, prior8high=1.167400, depth_time=2026-10-31T00:45:13+00:00, book20_bid_proxy_usdt=20022, book20_ask_proxy_usdt=17132, funding_indicative=-0.000312, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.26%, turnover=9856476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T00:45:00+00:00, last15m_closed_end=2026-10-31T00:45+00:00, prior8high=90.278000, depth_time=2026-10-31T00:45:18+00:00, book20_bid_proxy_usdt=69413, book20_ask_proxy_usdt=89050, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=140066114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T00:45:00+00:00, last15m_closed_end=2026-10-31T00:45+00:00, prior8high=0.049970, depth_time=2026-10-31T00:45:11+00:00, book20_bid_proxy_usdt=17512, book20_ask_proxy_usdt=32028, funding_indicative=0.000051, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.05%, turnover=18961290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T00:45:00+00:00, last15m_closed_end=2026-10-31T00:45+00:00, prior8high=0.331360, depth_time=2026-10-31T00:45:13+00:00, book20_bid_proxy_usdt=72334, book20_ask_proxy_usdt=51810, funding_indicative=-0.000726, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=9821249. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
