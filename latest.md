# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T13:00:32Z**
- feed_generated_utc: 2026-10-25T13:00:35+00:00
- source_sha256: `30015a9809ea8f53a19cb71f1b2ba69c693e6497545572784d8b381e5f5bb79c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T13:00+00:00, close=80419.2, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T13:00+00:00, close=80419.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.033710|-40.77|164.18|-41.59|25258100|8.89|
|ORDER_USDT|0.046370|-31.20|49.82|-32.02|6670186|6.47|
|STRK_USDT|0.045440|-3.95|-31.30|-4.77|10035693|2.20|
|BTW_USDT|1.687900|-3.06|-25.62|-3.88|12259171|2.37|
|DOT_USDT|1.026500|-2.15|-8.13|-2.97|12465455|1.95|
|TIA_USDT|0.523700|-1.92|-20.41|-2.74|20068435|1.91|
|SEI_USDT|0.052460|-1.57|-15.40|-2.39|7575112|3.81|
|SUI_USDT|0.917300|-1.12|-6.56|-1.94|69097481|1.09|
|APT_USDT|0.694100|-1.11|-12.96|-1.93|6061983|1.44|
|PENGU_USDT|0.007378|-0.87|-1.00|-1.69|5822484|1.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.694100|0.689400|0.694300|0.48|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.687900|1.638700|1.687400|1.02|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.026500|1.013200|1.026500|0.43|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.033710|0.033290|0.033710|1.32|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.046370|0.045690|0.046430|1.23|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007378|0.007333|0.007380|1.67|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052460|0.052220|0.052460|0.51|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045440|0.044870|0.045440|0.48|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.917300|0.907500|0.917300|0.47|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.523700|0.524500|0.523700|0.70|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T13:00:04+00:00, last15m_closed_end=2026-10-25T13:00+00:00, prior8high=0.698900, depth_time=2026-10-25T13:00:29+00:00, book20_bid_proxy_usdt=171511, book20_ask_proxy_usdt=163880, funding_indicative=-0.000130, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=6061983. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T13:00:04+00:00, last15m_closed_end=2026-10-25T13:00+00:00, prior8high=1.699100, depth_time=2026-10-25T13:00:15+00:00, book20_bid_proxy_usdt=9105, book20_ask_proxy_usdt=13678, funding_indicative=-0.012348, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=12259171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T13:00:04+00:00, last15m_closed_end=2026-10-25T13:00+00:00, prior8high=1.028700, depth_time=2026-10-25T13:00:16+00:00, book20_bid_proxy_usdt=357503, book20_ask_proxy_usdt=257368, funding_indicative=-0.000041, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=12465455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T13:00:04+00:00, last15m_closed_end=2026-10-25T13:00+00:00, prior8high=0.036110, depth_time=2026-10-25T13:00:08+00:00, book20_bid_proxy_usdt=78697, book20_ask_proxy_usdt=50926, funding_indicative=0.000012, next_funding_utc=2026-10-25T14:00:00+00:00, funding_cycle_h=1, 24h_change=-40.77%, turnover=25258100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T13:00:04+00:00, last15m_closed_end=2026-10-25T13:00+00:00, prior8high=0.050260, depth_time=2026-10-25T13:00:11+00:00, book20_bid_proxy_usdt=93336, book20_ask_proxy_usdt=83502, funding_indicative=-0.000914, next_funding_utc=2026-10-25T14:00:00+00:00, funding_cycle_h=1, 24h_change=-31.20%, turnover=6670186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T13:00:04+00:00, last15m_closed_end=2026-10-25T13:00+00:00, prior8high=0.007422, depth_time=2026-10-25T13:00:32+00:00, book20_bid_proxy_usdt=208843, book20_ask_proxy_usdt=225792, funding_indicative=-0.000062, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=5822484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T13:00:04+00:00, last15m_closed_end=2026-10-25T13:00+00:00, prior8high=0.052880, depth_time=2026-10-25T13:00:22+00:00, book20_bid_proxy_usdt=415690, book20_ask_proxy_usdt=333581, funding_indicative=-0.000075, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=7575112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T13:00:04+00:00, last15m_closed_end=2026-10-25T13:00+00:00, prior8high=0.046180, depth_time=2026-10-25T13:00:13+00:00, book20_bid_proxy_usdt=1124404, book20_ask_proxy_usdt=690951, funding_indicative=0.000002, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.95%, turnover=10035693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T13:00:04+00:00, last15m_closed_end=2026-10-25T13:00+00:00, prior8high=0.920400, depth_time=2026-10-25T13:00:26+00:00, book20_bid_proxy_usdt=901707, book20_ask_proxy_usdt=1747287, funding_indicative=-0.000034, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=69097481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T13:00:04+00:00, last15m_closed_end=2026-10-25T13:00+00:00, prior8high=0.532800, depth_time=2026-10-25T13:00:20+00:00, book20_bid_proxy_usdt=399744, book20_ask_proxy_usdt=355075, funding_indicative=-0.000031, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=20068435. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
