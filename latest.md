# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T02:30:46Z**
- feed_generated_utc: 2026-10-23T02:30:48+00:00
- source_sha256: `005d5aae715923b65a32c0394a2d698e924a23f5a5ddee94fba4a9d70c78d88f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T02:30+00:00, close=81600, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T02:00+00:00, close=81311.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T00:00+00:00, close=81384.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004361|-5.36|119.69|-5.31|9593535|6.88|
|LIT_USDT|3.452400|-4.47|11.67|-4.42|11471023|0.29|
|PHA_USDT|0.059830|-3.57|18.42|-3.52|8286283|1.67|
|STRK_USDT|0.052720|-3.01|-45.28|-2.96|12210768|1.90|
|SILVER_USDT|54.140000|-2.02|-5.25|-1.97|387002146|1.85|
|ARB_USDT|0.181300|-1.27|-4.54|-1.22|30414882|0.55|
|PUMPFUN_USDT|0.004625|-1.15|2.18|-1.10|38070229|2.16|
|TIA_USDT|0.561900|-1.14|-6.73|-1.09|23422530|1.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181300|0.179050|0.181280|0.79|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004361|0.004323|0.004362|0.57|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.452400|3.364500|3.452400|0.44|N|Y/Y|Y/N|Y|N|
|PHA_USDT|0.059830|0.059620|0.059820|1.15|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004625|0.004539|0.004625|6.58|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.140000|53.570000|54.120000|3.41|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052720|0.052330|0.052720|0.13|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.561900|0.554300|0.561800|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T02:30:01+00:00, last15m_closed_end=2026-10-23T02:30+00:00, prior8high=0.182060, depth_time=2026-10-23T02:30:40+00:00, book20_bid_proxy_usdt=72499, book20_ask_proxy_usdt=58498, funding_indicative=-0.000113, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=30414882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T02:30:01+00:00, last15m_closed_end=2026-10-23T02:30+00:00, prior8high=0.004594, depth_time=2026-10-23T02:30:28+00:00, book20_bid_proxy_usdt=54288, book20_ask_proxy_usdt=41258, funding_indicative=0.000072, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.36%, turnover=9593535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T02:30:01+00:00, last15m_closed_end=2026-10-23T02:30+00:00, prior8high=3.472900, depth_time=2026-10-23T02:30:29+00:00, book20_bid_proxy_usdt=23786, book20_ask_proxy_usdt=23586, funding_indicative=0.000050, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.47%, turnover=11471023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-23T02:30:01+00:00, last15m_closed_end=2026-10-23T02:30+00:00, prior8high=0.061510, depth_time=2026-10-23T02:30:33+00:00, book20_bid_proxy_usdt=39607, book20_ask_proxy_usdt=71196, funding_indicative=-0.000543, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=8286283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T02:30:01+00:00, last15m_closed_end=2026-10-23T02:30+00:00, prior8high=0.004670, depth_time=2026-10-23T02:30:43+00:00, book20_bid_proxy_usdt=1265340, book20_ask_proxy_usdt=1506047, funding_indicative=0.000022, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=38070229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T02:30:01+00:00, last15m_closed_end=2026-10-23T02:30+00:00, prior8high=54.870000, depth_time=2026-10-23T02:30:38+00:00, book20_bid_proxy_usdt=27665717, book20_ask_proxy_usdt=31398180, funding_indicative=0.000093, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=387002146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T02:30:01+00:00, last15m_closed_end=2026-10-23T02:30+00:00, prior8high=0.053310, depth_time=2026-10-23T02:30:35+00:00, book20_bid_proxy_usdt=545662, book20_ask_proxy_usdt=599479, funding_indicative=0.000042, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=12210768. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T02:30:01+00:00, last15m_closed_end=2026-10-23T02:30+00:00, prior8high=0.567500, depth_time=2026-10-23T02:30:45+00:00, book20_bid_proxy_usdt=372906, book20_ask_proxy_usdt=379807, funding_indicative=0.000003, next_funding_utc=2026-10-23T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=23422530. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
