# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T09:00:43Z**
- feed_generated_utc: 2026-10-18T09:00:46+00:00
- source_sha256: `3749bdbe51c940cb0846b5e569600e79a14f7fe389670e3559bac6594e0ac220`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T09:00+00:00, close=81705.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T09:00+00:00, close=81705.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.247200|-3.55|4.92|-4.03|7356650|4.05|
|FILECOIN_USDT|1.048800|-3.54|-7.00|-4.02|19745871|0.95|
|PUMPFUN_USDT|0.004272|-3.17|-25.37|-3.65|23559923|2.34|
|ZRO_USDT|1.832300|-2.81|-9.31|-3.29|7185728|0.55|
|STRK_USDT|0.064380|-2.67|-31.09|-3.15|14469382|1.55|
|QNT_USDT|195.210000|-2.59|-20.36|-3.07|69158750|0.51|
|XPL_USDT|0.078080|-2.55|-10.00|-3.03|5537445|1.28|
|OP_USDT|0.126180|-2.18|-8.92|-2.66|9344316|0.79|
|ARB_USDT|0.181210|-1.47|-2.92|-1.95|31765892|0.55|
|ZEC_USDT|1124.650000|-1.46|-8.69|-1.94|1204953761|0.09|
|DOT_USDT|1.101900|-1.38|-12.33|-1.86|16574172|1.81|
|ENA_USDT|0.187200|-1.03|-15.69|-1.51|28182177|0.53|
|WLD_USDT|0.490800|-0.96|-12.20|-1.44|59889015|2.04|
|FARTCOIN_USDT|0.146620|-0.96|-10.54|-1.44|5999647|2.05|
|ONDO_USDT|0.435800|-0.86|-11.88|-1.34|22314438|2.29|
|APT_USDT|0.791600|-0.73|-4.25|-1.21|10062430|1.26|
|PEPE_USDT|0.000004|-0.66|-4.24|-1.14|58259801|0.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181210|0.180730|0.181210|1.15|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.101900|1.098300|1.101900|1.25|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.247200|0.246100|0.247200|1.03|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.187200|0.186590|0.187210|1.44|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.146620|0.146190|0.146620|8.28|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.048800|1.045000|1.048800|1.05|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.435800|0.434800|0.435800|1.37|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.126180|0.125540|0.126180|1.39|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004272|0.004250|0.004272|2.08|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.210000|192.710000|195.210000|0.92|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064380|0.062200|0.064390|1.05|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.490800|0.487300|0.490800|2.29|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078080|0.077930|0.078080|0.15|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1124.650000|1119.150000|1124.670000|0.93|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.832300|1.824400|1.832300|0.99|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=0.183840, depth_time=2026-10-18T09:00:27+00:00, book20_bid_proxy_usdt=58069, book20_ask_proxy_usdt=94376, funding_indicative=-0.000030, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=31765892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=1.106900, depth_time=2026-10-18T09:00:32+00:00, book20_bid_proxy_usdt=405035, book20_ask_proxy_usdt=257818, funding_indicative=-0.000127, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=16574172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=0.248700, depth_time=2026-10-18T09:00:08+00:00, book20_bid_proxy_usdt=443683, book20_ask_proxy_usdt=343424, funding_indicative=0.000002, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=7356650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=0.188580, depth_time=2026-10-18T09:00:32+00:00, book20_bid_proxy_usdt=218638, book20_ask_proxy_usdt=185720, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.03%, turnover=28182177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=0.147880, depth_time=2026-10-18T09:00:40+00:00, book20_bid_proxy_usdt=44788, book20_ask_proxy_usdt=42136, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=5999647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=1.055200, depth_time=2026-10-18T09:00:09+00:00, book20_bid_proxy_usdt=723293, book20_ask_proxy_usdt=728085, funding_indicative=-0.000058, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=19745871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=0.440000, depth_time=2026-10-18T09:00:43+00:00, book20_bid_proxy_usdt=1746242, book20_ask_proxy_usdt=1963208, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.86%, turnover=22314438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=0.127170, depth_time=2026-10-18T09:00:24+00:00, book20_bid_proxy_usdt=84599, book20_ask_proxy_usdt=95643, funding_indicative=-0.000156, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=9344316. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=0.004295, depth_time=2026-10-18T09:00:11+00:00, book20_bid_proxy_usdt=1634886, book20_ask_proxy_usdt=1497335, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=23559923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=195.400000, depth_time=2026-10-18T09:00:20+00:00, book20_bid_proxy_usdt=53938, book20_ask_proxy_usdt=92779, funding_indicative=-0.000073, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.59%, turnover=69158750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=0.064330, depth_time=2026-10-18T09:00:17+00:00, book20_bid_proxy_usdt=336540, book20_ask_proxy_usdt=258721, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=14469382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=0.493600, depth_time=2026-10-18T09:00:37+00:00, book20_bid_proxy_usdt=1972161, book20_ask_proxy_usdt=1683647, funding_indicative=-0.000092, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=59889015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=0.078880, depth_time=2026-10-18T09:00:22+00:00, book20_bid_proxy_usdt=460662, book20_ask_proxy_usdt=464022, funding_indicative=0.000033, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=5537445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=1141.400000, depth_time=2026-10-18T09:00:31+00:00, book20_bid_proxy_usdt=680220, book20_ask_proxy_usdt=229785, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=1204953761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T08:59:59+00:00, last15m_closed_end=2026-10-18T09:00+00:00, prior8high=1.849400, depth_time=2026-10-18T09:00:15+00:00, book20_bid_proxy_usdt=39315, book20_ask_proxy_usdt=46018, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=7185728. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
