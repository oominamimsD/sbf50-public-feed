# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-22T23:45:43Z**
- feed_generated_utc: 2026-10-22T23:45:45+00:00
- source_sha256: `480babb34d49a2ef0ebbc4e904db6a81a65ea115898e6641886bc6c5a7f6eaee`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-22T23:45+00:00, close=81327.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-22T23:00+00:00, close=81314.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-22T20:00+00:00, close=81462.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.404900|-5.79|10.14|-5.40|14977385|0.29|
|PUMPFUN_USDT|0.004547|-2.82|0.46|-2.43|37117948|2.20|
|XPL_USDT|0.075430|-2.67|-10.98|-2.28|5731509|1.33|
|ARB_USDT|0.178740|-2.66|-5.89|-2.27|33064095|0.56|
|APT_USDT|0.751700|-2.65|-9.07|-2.26|9079012|1.33|
|QNT_USDT|185.950000|-2.49|-10.56|-2.10|60365455|1.61|
|STRK_USDT|0.053120|-2.28|-44.87|-1.89|13689808|1.88|
|EIGEN_USDT|0.216800|-2.07|-12.58|-1.68|6094788|4.62|
|XMR_USDT|600.490000|-2.02|10.39|-1.63|27113752|0.17|
|OP_USDT|0.117510|-1.95|-15.38|-1.56|6988782|0.85|
|SEI_USDT|0.056940|-1.94|-7.35|-1.55|10793302|1.76|
|TIA_USDT|0.557600|-1.90|-7.45|-1.51|24261064|1.79|
|ICP_USDT|2.696000|-1.85|-11.95|-1.46|8050093|3.71|
|PHA_USDT|0.061100|-1.53|20.94|-1.14|8414255|1.64|
|ZEC_USDT|1216.190000|-1.46|3.09|-1.07|1898937918|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.751700|0.750400|0.751700|0.51|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.178740|0.177500|0.178740|0.42|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.216800|0.216300|0.216800|1.10|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.696000|2.700000|2.697000|6.08|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.404900|3.378800|3.404900|0.55|N|Y/Y|N/N|Y|N|
|OP_USDT|0.117510|0.117250|0.117470|0.29|N|Y/Y|Y/Y|Y|N|
|PHA_USDT|0.061100|0.060560|0.061100|0.23|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004547|0.004525|0.004547|1.10|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|185.950000|185.680000|185.950000|0.58|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.056940|0.056840|0.056940|0.22|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.053120|0.052550|0.053120|0.38|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.557600|0.555400|0.557600|0.52|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|600.490000|586.430000|600.490000|0.54|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.075430|0.075210|0.075430|2.33|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1216.190000|1203.410000|1216.290000|1.25|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=0.762900, depth_time=2026-10-22T23:45:16+00:00, book20_bid_proxy_usdt=138538, book20_ask_proxy_usdt=147060, funding_indicative=-0.000056, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=9079012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=0.181730, depth_time=2026-10-22T23:45:14+00:00, book20_bid_proxy_usdt=52169, book20_ask_proxy_usdt=61960, funding_indicative=-0.000139, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=33064095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=0.219900, depth_time=2026-10-22T23:45:23+00:00, book20_bid_proxy_usdt=794604, book20_ask_proxy_usdt=454745, funding_indicative=-0.000017, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=6094788. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=2.734000, depth_time=2026-10-22T23:45:33+00:00, book20_bid_proxy_usdt=847139, book20_ask_proxy_usdt=1038592, funding_indicative=-0.000105, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=8050093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=3.555800, depth_time=2026-10-22T23:45:05+00:00, book20_bid_proxy_usdt=31553, book20_ask_proxy_usdt=31716, funding_indicative=0.000050, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.79%, turnover=14977385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=0.119250, depth_time=2026-10-22T23:45:29+00:00, book20_bid_proxy_usdt=90375, book20_ask_proxy_usdt=107186, funding_indicative=-0.000199, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=6988782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=0.061600, depth_time=2026-10-22T23:45:37+00:00, book20_bid_proxy_usdt=63354, book20_ask_proxy_usdt=76086, funding_indicative=-0.000475, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=8414255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=0.004649, depth_time=2026-10-22T23:45:09+00:00, book20_bid_proxy_usdt=1697708, book20_ask_proxy_usdt=2024643, funding_indicative=0.000019, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=37117948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=189.940000, depth_time=2026-10-22T23:45:18+00:00, book20_bid_proxy_usdt=68444, book20_ask_proxy_usdt=109640, funding_indicative=-0.000147, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=60365455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=0.057600, depth_time=2026-10-22T23:45:32+00:00, book20_bid_proxy_usdt=337459, book20_ask_proxy_usdt=537006, funding_indicative=-0.000007, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=10793302. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=0.053310, depth_time=2026-10-22T23:45:20+00:00, book20_bid_proxy_usdt=565038, book20_ask_proxy_usdt=615317, funding_indicative=0.000043, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=13689808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=0.565100, depth_time=2026-10-22T23:45:34+00:00, book20_bid_proxy_usdt=363611, book20_ask_proxy_usdt=345051, funding_indicative=-0.000011, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=24261064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=601.900000, depth_time=2026-10-22T23:45:25+00:00, book20_bid_proxy_usdt=8891, book20_ask_proxy_usdt=12884, funding_indicative=0.000100, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=27113752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=0.076300, depth_time=2026-10-22T23:45:11+00:00, book20_bid_proxy_usdt=501983, book20_ask_proxy_usdt=628679, funding_indicative=-0.000018, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=5731509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-22T23:44:59+00:00, last15m_closed_end=2026-10-22T23:45+00:00, prior8high=1222.000000, depth_time=2026-10-22T23:45:41+00:00, book20_bid_proxy_usdt=290314, book20_ask_proxy_usdt=357331, funding_indicative=0.000055, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=1898937918. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
