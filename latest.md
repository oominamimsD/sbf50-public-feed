# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T22:00:23Z**
- feed_generated_utc: 2026-10-21T22:00:26+00:00
- source_sha256: `b03d5a05bd1c73170deeec2b0bc7c01137e7ec359b03cfcaaa7927c12b10dfd2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T22:00+00:00, close=84800, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T22:00+00:00, close=84800, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.501870|-13.35|23.08|-13.70|14668656|1.79|
|DOOD_USDT|0.002480|-12.79|74.89|-13.14|9102351|8.06|
|AKE_USDT|0.025018|-8.45|-3.33|-8.80|10427850|0.80|
|ZRO_USDT|1.986900|-2.99|4.91|-3.34|6944677|1.51|
|TIA_USDT|0.619200|-2.10|16.06|-2.45|38834872|1.61|
|LDO_USDT|0.410200|-1.20|1.08|-1.55|5035912|2.44|
|INJ_USDT|8.674000|-0.86|13.54|-1.21|53154400|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025018|0.025195|0.025019|2.65|Y|Y/Y|Y/Y|N|Y|
|BR_USDT|0.501870|0.476600|0.501870|1.80|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002480|0.002430|0.002476|0.20|N|Y/Y|N/N|N|N|
|INJ_USDT|8.674000|8.489000|8.674000|0.44|N|Y/Y|Y/N|N|N|
|LDO_USDT|0.410200|0.409900|0.410000|1.40|N|Y/Y|N/N|N|N|
|TIA_USDT|0.619200|0.616100|0.619000|0.96|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.986900|1.986800|1.986900|0.73|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T22:00:03+00:00, last15m_closed_end=2026-10-21T22:00+00:00, prior8high=0.026307, depth_time=2026-10-21T22:00:10+00:00, book20_bid_proxy_usdt=16756, book20_ask_proxy_usdt=23370, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.45%, turnover=10427850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T22:00:02+00:00, last15m_closed_end=2026-10-21T22:00+00:00, prior8high=0.502760, depth_time=2026-10-21T22:00:08+00:00, book20_bid_proxy_usdt=4464, book20_ask_proxy_usdt=5221, funding_indicative=-0.000115, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.35%, turnover=14668656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T22:00:02+00:00, last15m_closed_end=2026-10-21T22:00+00:00, prior8high=0.002549, depth_time=2026-10-21T22:00:09+00:00, book20_bid_proxy_usdt=153042, book20_ask_proxy_usdt=95827, funding_indicative=-0.000011, next_funding_utc=2026-10-21T23:00:00+00:00, funding_cycle_h=1, 24h_change=-12.79%, turnover=9102351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T22:00:02+00:00, last15m_closed_end=2026-10-21T22:00+00:00, prior8high=8.739000, depth_time=2026-10-21T22:00:22+00:00, book20_bid_proxy_usdt=242570, book20_ask_proxy_usdt=182868, funding_indicative=0.000128, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=53154400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-21T22:00:03+00:00, last15m_closed_end=2026-10-21T22:00+00:00, prior8high=0.412800, depth_time=2026-10-21T22:00:19+00:00, book20_bid_proxy_usdt=369474, book20_ask_proxy_usdt=397312, funding_indicative=0.000018, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=5035912. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T22:00:03+00:00, last15m_closed_end=2026-10-21T22:00+00:00, prior8high=0.626800, depth_time=2026-10-21T22:00:18+00:00, book20_bid_proxy_usdt=217944, book20_ask_proxy_usdt=119857, funding_indicative=-0.000110, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=38834872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-21T22:00:03+00:00, last15m_closed_end=2026-10-21T22:00+00:00, prior8high=2.028300, depth_time=2026-10-21T22:00:15+00:00, book20_bid_proxy_usdt=41796, book20_ask_proxy_usdt=29313, funding_indicative=0.000003, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.99%, turnover=6944677. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
