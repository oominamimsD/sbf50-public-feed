# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T10:15:24Z**
- feed_generated_utc: 2026-10-14T10:15:26+00:00
- source_sha256: `1d76e676ba42450d94ba9bc3e4cfd753120fa7265c9429a8d67e8f85b84468b1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T10:15+00:00, close=83275.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T10:00+00:00, close=83219.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078940|-9.19|51.25|-9.06|29155719|1.27|
|TIA_USDT|0.546000|-5.42|14.63|-5.29|36676132|3.66|
|W_USDT|0.016161|-3.82|11.36|-3.69|6793508|2.48|
|UNI_USDT|7.371000|-2.65|-14.93|-2.52|19045139|1.36|
|DOT_USDT|1.132500|-2.10|-5.73|-1.97|20171900|0.88|
|XLM_USDT|0.188490|-1.30|-11.78|-1.17|9897171|0.53|
|SILVER_USDT|58.680000|-1.19|-4.38|-1.06|255184982|1.70|
|ICP_USDT|3.076000|-1.15|-9.58|-1.02|9713220|3.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.132500|1.130400|1.132500|2.01|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|3.076000|3.053000|3.076000|2.22|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|58.680000|58.570000|58.680000|1.49|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.078940|0.078190|0.078940|0.48|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.546000|0.544200|0.545900|1.17|N|Y/Y|Y/N|Y|N|
|UNI_USDT|7.371000|7.328000|7.371000|1.18|N|Y/Y|Y/Y|Y|N|
|W_USDT|0.016161|0.015659|0.016163|1.21|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.188490|0.188210|0.188490|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T10:15:03+00:00, last15m_closed_end=2026-10-14T10:15+00:00, prior8high=1.164200, depth_time=2026-10-14T10:15:16+00:00, book20_bid_proxy_usdt=311832, book20_ask_proxy_usdt=296644, funding_indicative=0.000026, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=20171900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T10:15:03+00:00, last15m_closed_end=2026-10-14T10:15+00:00, prior8high=3.139000, depth_time=2026-10-14T10:15:22+00:00, book20_bid_proxy_usdt=818438, book20_ask_proxy_usdt=749325, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=9713220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T10:15:02+00:00, last15m_closed_end=2026-10-14T10:15+00:00, prior8high=59.010000, depth_time=2026-10-14T10:15:19+00:00, book20_bid_proxy_usdt=59186350, book20_ask_proxy_usdt=36641590, funding_indicative=0.000094, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.19%, turnover=255184982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T10:15:02+00:00, last15m_closed_end=2026-10-14T10:15+00:00, prior8high=0.082970, depth_time=2026-10-14T10:15:06+00:00, book20_bid_proxy_usdt=337254, book20_ask_proxy_usdt=222805, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.19%, turnover=29155719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T10:15:02+00:00, last15m_closed_end=2026-10-14T10:15+00:00, prior8high=0.564000, depth_time=2026-10-14T10:15:10+00:00, book20_bid_proxy_usdt=117601, book20_ask_proxy_usdt=203533, funding_indicative=0.000000, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.42%, turnover=36676132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T10:15:02+00:00, last15m_closed_end=2026-10-14T10:15+00:00, prior8high=7.502000, depth_time=2026-10-14T10:15:14+00:00, book20_bid_proxy_usdt=1626923, book20_ask_proxy_usdt=1564762, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=19045139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T10:15:02+00:00, last15m_closed_end=2026-10-14T10:15+00:00, prior8high=0.016686, depth_time=2026-10-14T10:15:12+00:00, book20_bid_proxy_usdt=31235, book20_ask_proxy_usdt=38085, funding_indicative=-0.000338, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.82%, turnover=6793508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T10:15:03+00:00, last15m_closed_end=2026-10-14T10:15+00:00, prior8high=0.192050, depth_time=2026-10-14T10:15:18+00:00, book20_bid_proxy_usdt=171489, book20_ask_proxy_usdt=166232, funding_indicative=-0.000103, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=9897171. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
