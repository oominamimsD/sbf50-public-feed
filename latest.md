# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T14:30:43Z**
- feed_generated_utc: 2026-10-27T14:30:47+00:00
- source_sha256: `85c4b86a1d9ef38eb201d9f82158b3ec9ce572ffee86a7c153391670e81b4997`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T14:30+00:00, close=80268.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T14:00+00:00, close=80014.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.024970|-9.46|103.33|-9.30|6520089|4.01|
|QNT_USDT|198.750000|-5.48|1.55|-5.32|97982910|1.51|
|AAVE_USDT|131.670000|-3.70|-10.56|-3.54|27486500|0.76|
|DOT_USDT|0.987300|-3.45|-13.90|-3.29|11264224|1.01|
|WLD_USDT|0.430400|-3.28|-14.99|-3.12|72356426|2.32|
|FILECOIN_USDT|0.891900|-3.12|-11.86|-2.96|5980669|1.12|
|PUMPFUN_USDT|0.004206|-2.81|-5.61|-2.65|21337350|2.38|
|APT_USDT|0.682500|-2.77|-10.53|-2.61|5024312|1.47|
|ICP_USDT|2.578000|-1.97|-9.63|-1.81|5359800|3.88|
|HBAR_USDT|0.075980|-1.78|-7.19|-1.62|9723673|1.32|
|TAO_USDT|249.700000|-1.50|-6.93|-1.34|51636872|1.20|
|TIA_USDT|0.527900|-1.45|-13.24|-1.29|17491850|1.89|
|SOL_USDT|100.450000|-1.36|-3.49|-1.20|702140627|0.99|
|LINK_USDT|11.379000|-1.29|-4.72|-1.13|130974287|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.670000|130.180000|131.670000|0.33|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.682500|0.672700|0.682100|0.72|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.987300|0.977000|0.987300|1.00|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.891900|0.880500|0.891900|1.73|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075980|0.075590|0.075980|0.72|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.578000|2.552000|2.578000|0.75|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.024970|0.024590|0.024970|1.09|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.379000|11.274000|11.379000|0.81|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004206|0.004142|0.004206|1.35|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|198.750000|196.560000|198.750000|0.58|N|Y/Y|N/N|Y|N|
|SOL_USDT|100.450000|99.820000|100.460000|1.45|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|249.700000|247.440000|249.610000|0.43|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.527900|0.519500|0.527900|0.76|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.430400|0.424600|0.430400|1.02|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=133.100000, depth_time=2026-10-27T14:30:15+00:00, book20_bid_proxy_usdt=284214, book20_ask_proxy_usdt=360295, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.70%, turnover=27486500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=0.690800, depth_time=2026-10-27T14:30:27+00:00, book20_bid_proxy_usdt=80208, book20_ask_proxy_usdt=155110, funding_indicative=-0.000036, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=5024312. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=0.996900, depth_time=2026-10-27T14:30:17+00:00, book20_bid_proxy_usdt=165742, book20_ask_proxy_usdt=454455, funding_indicative=-0.000179, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=11264224. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T14:30:01+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=0.902000, depth_time=2026-10-27T14:30:21+00:00, book20_bid_proxy_usdt=820644, book20_ask_proxy_usdt=1260366, funding_indicative=0.000020, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=5980669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=0.076600, depth_time=2026-10-27T14:30:33+00:00, book20_bid_proxy_usdt=597361, book20_ask_proxy_usdt=1216094, funding_indicative=0.000073, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=9723673. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T14:30:01+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=2.608000, depth_time=2026-10-27T14:30:29+00:00, book20_bid_proxy_usdt=1027130, book20_ask_proxy_usdt=1074830, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=5359800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=0.025580, depth_time=2026-10-27T14:30:10+00:00, book20_bid_proxy_usdt=114966, book20_ask_proxy_usdt=110024, funding_indicative=-0.000350, next_funding_utc=2026-10-27T15:00:00+00:00, funding_cycle_h=1, 24h_change=-9.46%, turnover=6520089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=11.453000, depth_time=2026-10-27T14:30:42+00:00, book20_bid_proxy_usdt=514254, book20_ask_proxy_usdt=564349, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=130974287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=0.004256, depth_time=2026-10-27T14:30:25+00:00, book20_bid_proxy_usdt=1245718, book20_ask_proxy_usdt=1896999, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=21337350. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=203.620000, depth_time=2026-10-27T14:30:12+00:00, book20_bid_proxy_usdt=60291, book20_ask_proxy_usdt=53382, funding_indicative=-0.000205, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.48%, turnover=97982910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=101.160000, depth_time=2026-10-27T14:30:40+00:00, book20_bid_proxy_usdt=17459400, book20_ask_proxy_usdt=16445932, funding_indicative=0.000079, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=702140627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=251.610000, depth_time=2026-10-27T14:30:35+00:00, book20_bid_proxy_usdt=92898, book20_ask_proxy_usdt=74015, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=51636872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=0.531400, depth_time=2026-10-27T14:30:37+00:00, book20_bid_proxy_usdt=369303, book20_ask_proxy_usdt=304744, funding_indicative=-0.000003, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=17491850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T14:30:00+00:00, last15m_closed_end=2026-10-27T14:30+00:00, prior8high=0.438400, depth_time=2026-10-27T14:30:20+00:00, book20_bid_proxy_usdt=2182509, book20_ask_proxy_usdt=3945001, funding_indicative=-0.000043, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=72356426. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
