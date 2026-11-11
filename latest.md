# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T07:00:43Z**
- feed_generated_utc: 2026-11-11T07:00:45+00:00
- source_sha256: `2c90e210d5b5614f8b6e96dca5da518a884f35cc00cd7d26eb2e3d8c4c0c8b4c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T07:00+00:00, close=73586.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T07:00+00:00, close=73586.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|982.250000|-10.16|-18.40|-10.71|2224917136|0.10|
|UNI_USDT|6.451000|-8.69|-12.26|-9.24|38078082|1.55|
|AKE_USDT|0.002665|-8.54|-35.87|-9.09|9453010|3.75|
|DASH_USDT|43.570000|-6.40|-5.57|-6.95|15268754|2.29|
|VVV_USDT|18.952000|-4.36|-15.24|-4.91|5301483|1.05|
|ARB_USDT|0.158910|-3.72|-0.60|-4.27|31164932|0.63|
|DOT_USDT|0.833300|-3.38|-11.59|-3.93|8283046|1.20|
|HBAR_USDT|0.065120|-2.68|-7.01|-3.23|5945753|1.54|
|WLD_USDT|0.309800|-2.54|-16.74|-3.09|28419571|3.23|
|QNT_USDT|178.450000|-2.53|-8.68|-3.08|45572457|0.56|
|DOGE_USDT|0.067660|-2.49|-10.36|-3.04|108870899|2.96|
|LINK_USDT|10.274000|-2.24|-7.88|-2.79|89909914|0.97|
|ADA_USDT|0.173900|-1.91|-8.90|-2.46|22308388|5.75|
|AAVE_USDT|122.630000|-1.88|-4.53|-2.43|10202852|1.63|
|BNB_USDT|677.890000|-1.69|-3.37|-2.24|7710614|0.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|122.630000|122.470000|122.630000|0.56|N|Y/Y|Y/Y|Y|N|
|ADA_USDT|0.173900|0.173800|0.173900|3.20|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002665|0.002607|0.002665|0.75|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158910|0.158960|0.158910|0.39|N|Y/Y|Y/Y|Y|N|
|BNB_USDT|677.890000|677.970000|677.890000|0.56|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.570000|43.720000|43.570000|0.73|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.067660|0.067650|0.067670|0.85|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.833300|0.831700|0.833400|4.28|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065120|0.065270|0.065120|6.05|Y|Y/Y|Y/Y|Y|Y|
|LINK_USDT|10.274000|10.275000|10.274000|1.52|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|178.450000|178.540000|178.450000|0.99|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.451000|6.447000|6.451000|1.23|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|18.952000|18.914000|18.952000|0.77|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.309800|0.308100|0.309800|1.20|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|982.250000|977.100000|982.250000|0.89|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=124.420000, depth_time=2026-11-11T07:00:39+00:00, book20_bid_proxy_usdt=327234, book20_ask_proxy_usdt=371569, funding_indicative=0.000045, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=10202852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=0.175700, depth_time=2026-11-11T07:00:38+00:00, book20_bid_proxy_usdt=10705111, book20_ask_proxy_usdt=10799645, funding_indicative=-0.000012, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=22308388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=0.002864, depth_time=2026-11-11T07:00:12+00:00, book20_bid_proxy_usdt=49809, book20_ask_proxy_usdt=48010, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.54%, turnover=9453010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=0.164540, depth_time=2026-11-11T07:00:21+00:00, book20_bid_proxy_usdt=52341, book20_ask_proxy_usdt=70807, funding_indicative=-0.000011, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=31164932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BNB_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=682.800000, depth_time=2026-11-11T07:00:41+00:00, book20_bid_proxy_usdt=218564, book20_ask_proxy_usdt=147970, funding_indicative=0.000068, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=7710614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=45.400000, depth_time=2026-11-11T07:00:13+00:00, book20_bid_proxy_usdt=741690, book20_ask_proxy_usdt=489274, funding_indicative=-0.000169, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.40%, turnover=15268754. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=0.068390, depth_time=2026-11-11T07:00:31+00:00, book20_bid_proxy_usdt=4248554, book20_ask_proxy_usdt=4534189, funding_indicative=0.000037, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=108870899. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=0.847600, depth_time=2026-11-11T07:00:22+00:00, book20_bid_proxy_usdt=576785, book20_ask_proxy_usdt=560250, funding_indicative=0.000035, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.38%, turnover=8283046. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=0.065870, depth_time=2026-11-11T07:00:22+00:00, book20_bid_proxy_usdt=545156, book20_ask_proxy_usdt=755851, funding_indicative=-0.000010, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.68%, turnover=5945753. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=10.414000, depth_time=2026-11-11T07:00:35+00:00, book20_bid_proxy_usdt=406866, book20_ask_proxy_usdt=905230, funding_indicative=0.000029, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=89909914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=181.050000, depth_time=2026-11-11T07:00:31+00:00, book20_bid_proxy_usdt=35649, book20_ask_proxy_usdt=83336, funding_indicative=-0.000112, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=45572457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=6.694000, depth_time=2026-11-11T07:00:11+00:00, book20_bid_proxy_usdt=2572656, book20_ask_proxy_usdt=2682943, funding_indicative=0.000005, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.69%, turnover=38078082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=19.229000, depth_time=2026-11-11T07:00:14+00:00, book20_bid_proxy_usdt=23708, book20_ask_proxy_usdt=15016, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.36%, turnover=5301483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-11T07:00:00+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=0.313500, depth_time=2026-11-11T07:00:25+00:00, book20_bid_proxy_usdt=4753952, book20_ask_proxy_usdt=5035337, funding_indicative=0.000048, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=28419571. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T06:59:59+00:00, last15m_closed_end=2026-11-11T07:00+00:00, prior8high=1024.940000, depth_time=2026-11-11T07:00:08+00:00, book20_bid_proxy_usdt=629484, book20_ask_proxy_usdt=53129, funding_indicative=0.000073, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.16%, turnover=2224917136. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
