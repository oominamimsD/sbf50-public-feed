# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T14:15:29Z**
- feed_generated_utc: 2026-10-25T14:15:33+00:00
- source_sha256: `0d7bc1e6435ab003db5056671604932b58478fff077d90d4598dad03b841a34c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T14:15+00:00, close=80378.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T14:00+00:00, close=80346.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.047640|-29.31|53.92|-30.08|5833334|2.10|
|IRYS_USDT|0.037740|-18.04|195.76|-18.81|24854946|2.65|
|BTW_USDT|1.690000|-2.94|-25.53|-3.71|12294085|2.37|
|STRK_USDT|0.045390|-2.86|-31.38|-3.63|10283227|4.41|
|SUI_USDT|0.911800|-1.42|-7.12|-2.19|70783189|1.10|
|DOT_USDT|1.026300|-1.23|-8.15|-2.00|12654292|0.97|
|APT_USDT|0.693900|-1.13|-12.99|-1.90|5906346|1.44|
|PENGU_USDT|0.007362|-1.08|-1.22|-1.85|5974604|1.36|
|SEI_USDT|0.052400|-0.90|-15.49|-1.67|6168099|1.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.693900|0.692600|0.693900|1.15|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.690000|1.638700|1.690000|1.59|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.026300|1.021400|1.026300|0.42|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.037740|0.033150|0.037740|2.48|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.047640|0.045450|0.047640|0.89|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007362|0.007341|0.007362|0.86|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052400|0.052220|0.052400|0.17|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045390|0.045250|0.045400|0.79|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.911800|0.911600|0.911800|1.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T14:15:01+00:00, last15m_closed_end=2026-10-25T14:15+00:00, prior8high=0.698900, depth_time=2026-10-25T14:15:24+00:00, book20_bid_proxy_usdt=156751, book20_ask_proxy_usdt=115847, funding_indicative=-0.000119, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=5906346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T14:15:00+00:00, last15m_closed_end=2026-10-25T14:15+00:00, prior8high=1.701100, depth_time=2026-10-25T14:15:14+00:00, book20_bid_proxy_usdt=13847, book20_ask_proxy_usdt=10654, funding_indicative=-0.009056, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.94%, turnover=12294085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T14:15:00+00:00, last15m_closed_end=2026-10-25T14:15+00:00, prior8high=1.031100, depth_time=2026-10-25T14:15:20+00:00, book20_bid_proxy_usdt=249283, book20_ask_proxy_usdt=230160, funding_indicative=-0.000097, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=12654292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T14:15:00+00:00, last15m_closed_end=2026-10-25T14:15+00:00, prior8high=0.038380, depth_time=2026-10-25T14:15:11+00:00, book20_bid_proxy_usdt=38161, book20_ask_proxy_usdt=47761, funding_indicative=-0.000019, next_funding_utc=2026-10-25T15:00:00+00:00, funding_cycle_h=1, 24h_change=-18.04%, turnover=24854946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T14:15:00+00:00, last15m_closed_end=2026-10-25T14:15+00:00, prior8high=0.048120, depth_time=2026-10-25T14:15:08+00:00, book20_bid_proxy_usdt=87763, book20_ask_proxy_usdt=81707, funding_indicative=-0.000809, next_funding_utc=2026-10-25T15:00:00+00:00, funding_cycle_h=1, 24h_change=-29.31%, turnover=5833334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T14:15:01+00:00, last15m_closed_end=2026-10-25T14:15+00:00, prior8high=0.007409, depth_time=2026-10-25T14:15:26+00:00, book20_bid_proxy_usdt=290027, book20_ask_proxy_usdt=197918, funding_indicative=-0.000054, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=5974604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T14:15:01+00:00, last15m_closed_end=2026-10-25T14:15+00:00, prior8high=0.052830, depth_time=2026-10-25T14:15:27+00:00, book20_bid_proxy_usdt=214227, book20_ask_proxy_usdt=227612, funding_indicative=-0.000025, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=6168099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T14:15:01+00:00, last15m_closed_end=2026-10-25T14:15+00:00, prior8high=0.046010, depth_time=2026-10-25T14:15:16+00:00, book20_bid_proxy_usdt=889961, book20_ask_proxy_usdt=903887, funding_indicative=0.000024, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=10283227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T14:15:00+00:00, last15m_closed_end=2026-10-25T14:15+00:00, prior8high=0.920200, depth_time=2026-10-25T14:15:18+00:00, book20_bid_proxy_usdt=1536044, book20_ask_proxy_usdt=716847, funding_indicative=-0.000068, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=70783189. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
