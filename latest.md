# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T10:45:32Z**
- feed_generated_utc: 2026-10-31T10:45:34+00:00
- source_sha256: `91d5c3967915d7c92eab7e46ce73cb9c82df7181809784dee207b2f31c8bf330`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T10:45+00:00, close=77455.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T10:00+00:00, close=77434.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010794|-42.95|-69.15|-42.79|10239750|0.93|
|Q_USDT|0.032440|-31.67|-72.58|-31.51|14358041|3.07|
|IDOL_USDT|0.018642|-7.90|135.37|-7.74|16039761|6.44|
|BTW_USDT|1.130700|-5.73|-33.58|-5.57|9081445|0.89|
|TRX_USDT|0.316750|-5.58|-3.82|-5.42|7308411|0.32|
|HYPE_USDT|87.826000|-4.89|12.01|-4.73|106262253|0.11|
|WLD_USDT|0.395800|-3.90|-25.65|-3.74|48334861|2.53|
|FET_USDT|0.161800|-2.88|-13.61|-2.72|5928537|6.18|
|DASH_USDT|47.880000|-2.36|-11.08|-2.20|13178600|2.09|
|LTC_USDT|54.930000|-1.41|-6.02|-1.25|6398524|3.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010794|0.010360|0.010794|0.60|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.130700|1.118100|1.130800|0.66|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.880000|47.590000|47.880000|2.21|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161800|0.161100|0.161900|0.28|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.826000|86.343000|87.826000|1.02|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.018642|0.017952|0.018642|1.00|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.930000|54.520000|54.930000|1.97|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.032440|0.031080|0.032440|0.45|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.316750|0.315970|0.316750|0.70|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.395800|0.394600|0.395800|0.44|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T10:45:02+00:00, last15m_closed_end=2026-10-31T10:45+00:00, prior8high=0.011090, depth_time=2026-10-31T10:45:08+00:00, book20_bid_proxy_usdt=11314, book20_ask_proxy_usdt=6522, funding_indicative=-0.000341, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-42.95%, turnover=10239750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T10:45:02+00:00, last15m_closed_end=2026-10-31T10:45+00:00, prior8high=1.167600, depth_time=2026-10-31T10:45:16+00:00, book20_bid_proxy_usdt=21928, book20_ask_proxy_usdt=18912, funding_indicative=-0.000218, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.73%, turnover=9081445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T10:45:02+00:00, last15m_closed_end=2026-10-31T10:45+00:00, prior8high=48.060000, depth_time=2026-10-31T10:45:25+00:00, book20_bid_proxy_usdt=844313, book20_ask_proxy_usdt=723097, funding_indicative=-0.000126, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=13178600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T10:45:02+00:00, last15m_closed_end=2026-10-31T10:45+00:00, prior8high=0.162400, depth_time=2026-10-31T10:45:22+00:00, book20_bid_proxy_usdt=1062714, book20_ask_proxy_usdt=918416, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.88%, turnover=5928537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T10:45:02+00:00, last15m_closed_end=2026-10-31T10:45+00:00, prior8high=88.106000, depth_time=2026-10-31T10:45:21+00:00, book20_bid_proxy_usdt=311644, book20_ask_proxy_usdt=40780, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.89%, turnover=106262253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T10:45:01+00:00, last15m_closed_end=2026-10-31T10:45+00:00, prior8high=0.021875, depth_time=2026-10-31T10:45:13+00:00, book20_bid_proxy_usdt=6607, book20_ask_proxy_usdt=8116, funding_indicative=0.000254, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.90%, turnover=16039761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T10:45:02+00:00, last15m_closed_end=2026-10-31T10:45+00:00, prior8high=55.000000, depth_time=2026-10-31T10:45:30+00:00, book20_bid_proxy_usdt=1444016, book20_ask_proxy_usdt=1502058, funding_indicative=-0.000040, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=6398524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T10:45:02+00:00, last15m_closed_end=2026-10-31T10:45+00:00, prior8high=0.033810, depth_time=2026-10-31T10:45:10+00:00, book20_bid_proxy_usdt=50724, book20_ask_proxy_usdt=48410, funding_indicative=-0.000528, next_funding_utc=2026-10-31T11:00:00+00:00, funding_cycle_h=1, 24h_change=-31.67%, turnover=14358041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T10:45:02+00:00, last15m_closed_end=2026-10-31T10:45+00:00, prior8high=0.321200, depth_time=2026-10-31T10:45:12+00:00, book20_bid_proxy_usdt=60538, book20_ask_proxy_usdt=71368, funding_indicative=-0.001019, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.58%, turnover=7308411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T10:45:02+00:00, last15m_closed_end=2026-10-31T10:45+00:00, prior8high=0.399000, depth_time=2026-10-31T10:45:24+00:00, book20_bid_proxy_usdt=5333271, book20_ask_proxy_usdt=4503805, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=48334861. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
