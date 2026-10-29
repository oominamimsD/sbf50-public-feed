# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T02:00:43Z**
- feed_generated_utc: 2026-10-29T02:00:45+00:00
- source_sha256: `f56f410b5137c9ffbc87835cc884ad7a402602d1540de50ac9242b13b4461f3c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T02:00+00:00, close=79972.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T02:00+00:00, close=79972.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T00:00+00:00, close=81308.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.010069|-8.10|25.11|-7.41|25015406|8.94|
|LIT_USDT|2.793300|-4.91|-19.53|-4.22|5297578|0.36|
|BCH_USDT|282.820000|-3.45|-2.36|-2.76|5810898|4.60|
|HBAR_USDT|0.073440|-3.25|-14.54|-2.56|14680390|1.36|
|NEAR_USDT|4.482000|-3.17|-16.76|-2.48|97527283|2.23|
|ONDO_USDT|0.406000|-3.14|-12.98|-2.45|20545731|2.46|
|DOT_USDT|0.974000|-2.94|-17.45|-2.25|13183410|1.02|
|WLD_USDT|0.420200|-2.91|-26.74|-2.22|75853031|2.38|
|APT_USDT|0.670300|-2.67|-19.78|-1.98|7712225|4.47|
|FET_USDT|0.177100|-2.53|-11.71|-1.84|7879473|5.64|
|XMR_USDT|589.400000|-2.43|-1.14|-1.74|5532174|3.39|
|ADA_USDT|0.198000|-2.41|-13.49|-1.72|47147183|5.05|
|AAVE_USDT|129.550000|-2.38|-18.27|-1.69|18711161|0.77|
|STRK_USDT|0.045700|-2.35|-26.25|-1.66|5451141|2.19|
|AVAX_USDT|8.689000|-2.22|-12.37|-1.53|25700357|2.30|
|FARTCOIN_USDT|0.128110|-2.19|-16.60|-1.50|13597870|1.56|
|SHIB_USDT|0.000005|-1.89|-7.40|-1.20|6548096|2.06|
|TIA_USDT|0.529900|-1.88|-16.22|-1.19|19280139|1.89|
|DASH_USDT|52.040000|-1.88|-2.30|-1.19|10888712|1.92|
|OP_USDT|0.109190|-1.70|-17.21|-1.01|7660430|1.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.550000|131.800000|129.550000|5.99|Y|Y/Y|Y/Y|Y|Y|
|ADA_USDT|0.198000|0.201500|0.198000|20.55|Y|Y/Y|Y/Y|Y|Y|
|APT_USDT|0.670300|0.681600|0.670300|16.67|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|8.689000|8.815000|8.689000|10.25|Y|Y/Y|N/N|Y|N|
|BCH_USDT|282.820000|284.330000|282.820000|4.14|Y|Y/Y|N/N|Y|N|
|BLESS_USDT|0.010069|0.009790|0.010071|1.12|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.974000|0.992100|0.974000|9.14|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.177100|0.180500|0.177100|18.16|Y|Y/Y|N/N|Y|N|
|HBAR_USDT|0.073440|0.074100|0.073440|4.48|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|2.793300|2.874700|2.793300|6.90|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.482000|4.566000|4.482000|8.58|Y|Y/Y|N/N|Y|N|
|ONDO_USDT|0.406000|0.412500|0.405800|10.86|Y|Y/Y|N/N|Y|N|
|STRK_USDT|0.045700|0.045980|0.045700|7.67|Y|Y/Y|N/N|Y|N|
|WLD_USDT|0.420200|0.426200|0.420200|5.08|Y|Y/Y|Y/Y|Y|Y|
|XMR_USDT|589.400000|595.120000|589.400000|6.32|Y|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=134.540000, depth_time=2026-10-29T02:00:38+00:00, book20_bid_proxy_usdt=235650, book20_ask_proxy_usdt=428819, funding_indicative=0.000019, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=18711161. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=0.206400, depth_time=2026-10-29T02:00:35+00:00, book20_bid_proxy_usdt=4517145, book20_ask_proxy_usdt=5653706, funding_indicative=0.000058, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.41%, turnover=47147183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=0.701200, depth_time=2026-10-29T02:00:29+00:00, book20_bid_proxy_usdt=68170, book20_ask_proxy_usdt=88102, funding_indicative=0.000001, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=7712225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=9.017000, depth_time=2026-10-29T02:00:42+00:00, book20_bid_proxy_usdt=543031, book20_ask_proxy_usdt=1064605, funding_indicative=0.000070, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=25700357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=290.270000, depth_time=2026-10-29T02:00:14+00:00, book20_bid_proxy_usdt=96612, book20_ask_proxy_usdt=45278, funding_indicative=-0.000010, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=5810898. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=0.011202, depth_time=2026-10-29T02:00:08+00:00, book20_bid_proxy_usdt=2430, book20_ask_proxy_usdt=7832, funding_indicative=0.000050, next_funding_utc=2026-10-29T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.10%, turnover=25015406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=1.014000, depth_time=2026-10-29T02:00:24+00:00, book20_bid_proxy_usdt=102755, book20_ask_proxy_usdt=162800, funding_indicative=0.000015, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=13183410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=0.184700, depth_time=2026-10-29T02:00:30+00:00, book20_bid_proxy_usdt=1901353, book20_ask_proxy_usdt=1809673, funding_indicative=0.000016, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=7879473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=0.075460, depth_time=2026-10-29T02:00:16+00:00, book20_bid_proxy_usdt=400793, book20_ask_proxy_usdt=429375, funding_indicative=0.000100, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=14680390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=2.939500, depth_time=2026-10-29T02:00:11+00:00, book20_bid_proxy_usdt=18740, book20_ask_proxy_usdt=26683, funding_indicative=-0.000104, next_funding_utc=2026-10-29T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.91%, turnover=5297578. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=4.737000, depth_time=2026-10-29T02:00:19+00:00, book20_bid_proxy_usdt=3073258, book20_ask_proxy_usdt=631550, funding_indicative=0.000100, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=97527283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=0.422000, depth_time=2026-10-29T02:00:21+00:00, book20_bid_proxy_usdt=993993, book20_ask_proxy_usdt=1796454, funding_indicative=0.000050, next_funding_utc=2026-10-29T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=20545731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=0.047200, depth_time=2026-10-29T02:00:40+00:00, book20_bid_proxy_usdt=857283, book20_ask_proxy_usdt=623398, funding_indicative=0.000010, next_funding_utc=2026-10-29T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=5451141. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=0.438800, depth_time=2026-10-29T02:00:26+00:00, book20_bid_proxy_usdt=2001202, book20_ask_proxy_usdt=2175003, funding_indicative=0.000091, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=75853031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-29T01:59:59+00:00, last15m_closed_end=2026-10-29T02:00+00:00, prior8high=600.090000, depth_time=2026-10-29T02:00:33+00:00, book20_bid_proxy_usdt=7218, book20_ask_proxy_usdt=16438, funding_indicative=0.000100, next_funding_utc=2026-10-29T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=5532174. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
