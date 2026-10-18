# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T04:00:30Z**
- feed_generated_utc: 2026-10-18T04:00:32+00:00
- source_sha256: `a40db6a6340ee11b07668f95e662aa65320c188dc0c1d04c972670fd0af221a8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T04:00+00:00, close=81919.1, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.176100|-4.91|77.69|-5.65|14298393|5.68|
|TIA_USDT|0.634300|-4.01|23.64|-4.75|69494681|1.57|
|STRK_USDT|0.063660|-3.76|-31.86|-4.50|14033643|1.57|
|FILECOIN_USDT|1.070000|-3.59|-5.12|-4.33|20712680|0.94|
|QNT_USDT|196.200000|-3.15|-19.96|-3.89|69715625|0.51|
|PUMPFUN_USDT|0.004380|-3.07|-23.49|-3.81|23192127|2.28|
|EIGEN_USDT|0.252800|-2.65|7.30|-3.39|9612319|3.96|
|APT_USDT|0.796500|-1.54|-3.66|-2.28|9885206|1.26|
|OP_USDT|0.129200|-0.64|-6.74|-1.38|9416665|0.77|
|WLD_USDT|0.496100|-0.52|-11.25|-1.26|63205798|2.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.796500|0.788100|0.796500|0.92|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.252800|0.247900|0.252800|1.03|N|Y/Y|N/Y|N|N|
|FILECOIN_USDT|1.070000|1.054300|1.069900|0.76|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.176100|0.152200|0.176300|1.63|N|Y/Y|N/N|N|N|
|OP_USDT|0.129200|0.127070|0.129210|1.66|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004380|0.004299|0.004380|5.13|N|Y/Y|Y/Y|N|N|
|QNT_USDT|196.200000|194.620000|196.200000|0.95|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.063660|0.063420|0.063670|2.65|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.634300|0.628300|0.634300|1.27|N|Y/Y|Y/N|N|N|
|WLD_USDT|0.496100|0.489400|0.496100|1.20|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T04:00:00+00:00, last15m_closed_end=2026-10-18T04:00+00:00, prior8high=0.800100, depth_time=2026-10-18T04:00:25+00:00, book20_bid_proxy_usdt=130577, book20_ask_proxy_usdt=120362, funding_indicative=-0.000081, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=9885206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T04:00:00+00:00, last15m_closed_end=2026-10-18T04:00+00:00, prior8high=0.253200, depth_time=2026-10-18T04:00:22+00:00, book20_bid_proxy_usdt=507739, book20_ask_proxy_usdt=302735, funding_indicative=0.000004, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=9612319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T04:00:00+00:00, last15m_closed_end=2026-10-18T04:00+00:00, prior8high=1.072600, depth_time=2026-10-18T04:00:14+00:00, book20_bid_proxy_usdt=836869, book20_ask_proxy_usdt=475797, funding_indicative=-0.000084, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.59%, turnover=20712680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T04:00:00+00:00, last15m_closed_end=2026-10-18T04:00+00:00, prior8high=0.171800, depth_time=2026-10-18T04:00:08+00:00, book20_bid_proxy_usdt=474377, book20_ask_proxy_usdt=135086, funding_indicative=0.000003, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.91%, turnover=14298393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T04:00:00+00:00, last15m_closed_end=2026-10-18T04:00+00:00, prior8high=0.129220, depth_time=2026-10-18T04:00:27+00:00, book20_bid_proxy_usdt=64968, book20_ask_proxy_usdt=50122, funding_indicative=-0.000149, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.64%, turnover=9416665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T04:00:00+00:00, last15m_closed_end=2026-10-18T04:00+00:00, prior8high=0.004390, depth_time=2026-10-18T04:00:18+00:00, book20_bid_proxy_usdt=1749603, book20_ask_proxy_usdt=1530694, funding_indicative=0.000037, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=23192127. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T04:00:00+00:00, last15m_closed_end=2026-10-18T04:00+00:00, prior8high=198.760000, depth_time=2026-10-18T04:00:17+00:00, book20_bid_proxy_usdt=80226, book20_ask_proxy_usdt=69578, funding_indicative=-0.000099, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.15%, turnover=69715625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T04:00:00+00:00, last15m_closed_end=2026-10-18T04:00+00:00, prior8high=0.064470, depth_time=2026-10-18T04:00:12+00:00, book20_bid_proxy_usdt=419359, book20_ask_proxy_usdt=289830, funding_indicative=0.000050, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.76%, turnover=14033643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T04:00:00+00:00, last15m_closed_end=2026-10-18T04:00+00:00, prior8high=0.640200, depth_time=2026-10-18T04:00:10+00:00, book20_bid_proxy_usdt=201495, book20_ask_proxy_usdt=301129, funding_indicative=-0.000017, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=69494681. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T04:00:00+00:00, last15m_closed_end=2026-10-18T04:00+00:00, prior8high=0.496400, depth_time=2026-10-18T04:00:29+00:00, book20_bid_proxy_usdt=1831920, book20_ask_proxy_usdt=2135979, funding_indicative=-0.000127, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.52%, turnover=63205798. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
