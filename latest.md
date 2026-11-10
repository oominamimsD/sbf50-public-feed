# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T21:15:41Z**
- feed_generated_utc: 2026-11-10T21:15:43+00:00
- source_sha256: `797367ebf48b3bce9881a95b687a26c1bf252be2975fa139bf2538e11ec6d533`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T21:15+00:00, close=73910.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T21:00+00:00, close=73756.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.836300|-9.36|56.22|-10.35|6099449|1.63|
|DASH_USDT|42.820000|-5.13|-7.19|-6.12|13460099|2.33|
|ZEC_USDT|1054.130000|-3.58|-12.43|-4.57|2248444228|0.38|
|AKE_USDT|0.002810|-3.56|-32.38|-4.55|15719586|3.56|
|UNI_USDT|6.717000|-1.65|-8.64|-2.64|29919325|1.49|
|ARB_USDT|0.159040|-1.44|-0.52|-2.43|34179682|0.63|
|ANTHROPIC_USDT|1300.450000|-1.29|-22.31|-2.28|8250601|3.62|
|JCT_USDT|0.005227|-0.90|25.10|-1.89|20261870|1.91|
|XAU_USDT|4038.190000|-0.27|2.35|-1.26|515321451|0.03|
|XAUT_USDT|4021.000000|-0.20|2.32|-1.19|113438450|0.07|
|NEAR_USDT|3.556000|-0.14|-7.85|-1.13|35058642|2.81|
|WLD_USDT|0.307800|-0.09|-17.28|-1.08|29373019|3.25|
|DOT_USDT|0.841000|-0.08|-10.77|-1.07|8836434|1.19|
|SILVER_USDT|51.600000|-0.05|3.24|-1.04|269419356|1.94|
|ENA_USDT|0.149140|-0.03|-13.38|-1.02|31609751|0.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002810|0.002786|0.002810|0.65|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1300.450000|1285.250000|1300.450000|5.52|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159040|0.158120|0.159040|1.03|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.820000|42.550000|42.820000|1.06|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.841000|0.831500|0.841000|0.78|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.149140|0.147450|0.149140|1.87|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005227|0.005022|0.005227|0.19|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.556000|3.545000|3.556000|0.25|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.836300|1.782100|1.836300|0.50|N|Y/Y|N/N|Y|N|
|SILVER_USDT|51.600000|51.380000|51.600000|0.52|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.717000|6.649000|6.717000|1.18|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.307800|0.304400|0.307800|0.95|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4021.000000|4015.640000|4021.000000|0.06|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4038.190000|4031.330000|4038.190000|0.73|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1054.130000|1020.790000|1054.130000|0.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=0.002911, depth_time=2026-11-10T21:15:14+00:00, book20_bid_proxy_usdt=49480, book20_ask_proxy_usdt=26308, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.56%, turnover=15719586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=1303.870000, depth_time=2026-11-10T21:15:21+00:00, book20_bid_proxy_usdt=14317, book20_ask_proxy_usdt=27740, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=8250601. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=0.160720, depth_time=2026-11-10T21:15:19+00:00, book20_bid_proxy_usdt=97108, book20_ask_proxy_usdt=80286, funding_indicative=-0.000214, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=34179682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=43.590000, depth_time=2026-11-10T21:15:08+00:00, book20_bid_proxy_usdt=711808, book20_ask_proxy_usdt=643692, funding_indicative=-0.000189, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.13%, turnover=13460099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=0.840300, depth_time=2026-11-10T21:15:28+00:00, book20_bid_proxy_usdt=617454, book20_ask_proxy_usdt=444966, funding_indicative=0.000047, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.08%, turnover=8836434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=0.149840, depth_time=2026-11-10T21:15:40+00:00, book20_bid_proxy_usdt=162431, book20_ask_proxy_usdt=176197, funding_indicative=0.000046, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.03%, turnover=31609751. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=0.005288, depth_time=2026-11-10T21:15:24+00:00, book20_bid_proxy_usdt=49456, book20_ask_proxy_usdt=41485, funding_indicative=0.000331, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.90%, turnover=20261870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=3.600000, depth_time=2026-11-10T21:15:29+00:00, book20_bid_proxy_usdt=2004313, book20_ask_proxy_usdt=2458367, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.14%, turnover=35058642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=1.856700, depth_time=2026-11-10T21:15:04+00:00, book20_bid_proxy_usdt=18817, book20_ask_proxy_usdt=21627, funding_indicative=0.000183, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.36%, turnover=6099449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=51.720000, depth_time=2026-11-10T21:15:34+00:00, book20_bid_proxy_usdt=40708822, book20_ask_proxy_usdt=34702458, funding_indicative=0.000033, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.05%, turnover=269419356. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=6.774000, depth_time=2026-11-10T21:15:16+00:00, book20_bid_proxy_usdt=2415266, book20_ask_proxy_usdt=2576547, funding_indicative=-0.000013, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=29919325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=0.310100, depth_time=2026-11-10T21:15:32+00:00, book20_bid_proxy_usdt=5451728, book20_ask_proxy_usdt=5098504, funding_indicative=-0.000009, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.09%, turnover=29373019. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=4026.090000, depth_time=2026-11-10T21:15:29+00:00, book20_bid_proxy_usdt=250293, book20_ask_proxy_usdt=159726, funding_indicative=0.000080, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.20%, turnover=113438450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=4043.650000, depth_time=2026-11-10T21:15:26+00:00, book20_bid_proxy_usdt=1149885, book20_ask_proxy_usdt=766606, funding_indicative=0.000101, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.27%, turnover=515321451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T21:15:00+00:00, last15m_closed_end=2026-11-10T21:15+00:00, prior8high=1055.830000, depth_time=2026-11-10T21:15:12+00:00, book20_bid_proxy_usdt=183691, book20_ask_proxy_usdt=154378, funding_indicative=0.000018, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=2248444228. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
