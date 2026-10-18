# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T02:30:44Z**
- feed_generated_utc: 2026-10-18T02:30:46+00:00
- source_sha256: `6af4a00f8228c3010cf4b9644caf49230715becfbf8eebe861adbd1ae7d22a0b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T02:30+00:00, close=81704.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T02:00+00:00, close=81618.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.154900|-16.36|56.30|-16.83|14652464|6.46|
|TIA_USDT|0.630300|-4.20|22.86|-4.67|73438534|1.59|
|STRK_USDT|0.063860|-3.46|-31.64|-3.93|15575084|1.57|
|EIGEN_USDT|0.248400|-3.08|5.43|-3.55|10761061|4.03|
|FILECOIN_USDT|1.058300|-2.67|-6.16|-3.14|20442305|0.94|
|QNT_USDT|195.880000|-2.26|-20.09|-2.73|70282305|1.53|
|PUMPFUN_USDT|0.004327|-1.92|-24.41|-2.39|23561915|2.31|
|XPL_USDT|0.078950|-1.47|-9.00|-1.94|5162877|1.27|
|ARB_USDT|0.182100|-0.98|-2.44|-1.45|31710838|0.55|
|OP_USDT|0.127750|-0.96|-7.79|-1.43|9669849|0.78|
|APT_USDT|0.790300|-0.90|-4.41|-1.37|10171234|1.26|
|WLD_USDT|0.491700|-0.78|-12.03|-1.25|66098532|2.03|
|PEPE_USDT|0.000004|-0.62|-4.21|-1.09|58989070|0.26|
|DOT_USDT|1.110400|-0.62|-11.65|-1.09|16557052|0.90|
|DNA_USDT|0.270500|-0.58|UNKNOWN|-1.05|5229728|7.40|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.790300|0.788600|0.790300|1.60|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.182100|0.180450|0.182000|0.67|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.270500|0.256600|0.270500|1.47|N|Y/Y|?|Y|N|
|DOT_USDT|1.110400|1.104200|1.110400|0.08|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.248400|0.248600|0.248400|0.91|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.058300|1.054300|1.058300|7.84|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.154900|0.153500|0.154900|0.29|N|Y/Y|N/N|Y|N|
|OP_USDT|0.127750|0.127070|0.127750|0.13|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.90|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004327|0.004299|0.004328|0.17|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.880000|194.070000|195.880000|0.33|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063860|0.063520|0.063860|0.23|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.630300|0.629300|0.630200|1.11|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.491700|0.487900|0.491700|1.55|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078950|0.078460|0.078950|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.800100, depth_time=2026-10-18T02:30:32+00:00, book20_bid_proxy_usdt=155998, book20_ask_proxy_usdt=139391, funding_indicative=-0.000066, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.90%, turnover=10171234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.183400, depth_time=2026-10-18T02:30:28+00:00, book20_bid_proxy_usdt=93517, book20_ask_proxy_usdt=82423, funding_indicative=0.000024, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=31710838. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.269200, depth_time=2026-10-18T02:30:42+00:00, book20_bid_proxy_usdt=100801, book20_ask_proxy_usdt=109427, funding_indicative=-0.002405, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.58%, turnover=5229728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=1.119300, depth_time=2026-10-18T02:30:40+00:00, book20_bid_proxy_usdt=313122, book20_ask_proxy_usdt=130125, funding_indicative=0.000048, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.62%, turnover=16557052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.253300, depth_time=2026-10-18T02:30:14+00:00, book20_bid_proxy_usdt=382075, book20_ask_proxy_usdt=389294, funding_indicative=0.000000, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=10761061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=1.071500, depth_time=2026-10-18T02:30:18+00:00, book20_bid_proxy_usdt=529004, book20_ask_proxy_usdt=635503, funding_indicative=-0.000059, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=20442305. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.173300, depth_time=2026-10-18T02:30:08+00:00, book20_bid_proxy_usdt=234532, book20_ask_proxy_usdt=125660, funding_indicative=-0.000046, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.36%, turnover=14652464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.129170, depth_time=2026-10-18T02:30:31+00:00, book20_bid_proxy_usdt=59464, book20_ask_proxy_usdt=39502, funding_indicative=-0.000128, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=9669849. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.000004, depth_time=2026-10-18T02:30:38+00:00, book20_bid_proxy_usdt=59298, book20_ask_proxy_usdt=90401, funding_indicative=-0.000307, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.62%, turnover=58989070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.004390, depth_time=2026-10-18T02:30:23+00:00, book20_bid_proxy_usdt=1295631, book20_ask_proxy_usdt=1267016, funding_indicative=0.000029, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=23561915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=198.820000, depth_time=2026-10-18T02:30:21+00:00, book20_bid_proxy_usdt=62314, book20_ask_proxy_usdt=49207, funding_indicative=-0.000119, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=70282305. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.064470, depth_time=2026-10-18T02:30:12+00:00, book20_bid_proxy_usdt=485729, book20_ask_proxy_usdt=260488, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=15575084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.649100, depth_time=2026-10-18T02:30:10+00:00, book20_bid_proxy_usdt=232978, book20_ask_proxy_usdt=186392, funding_indicative=-0.000028, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.20%, turnover=73438534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T02:30:00+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.496400, depth_time=2026-10-18T02:30:35+00:00, book20_bid_proxy_usdt=1625549, book20_ask_proxy_usdt=1480526, funding_indicative=-0.000136, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.78%, turnover=66098532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T02:30:01+00:00, last15m_closed_end=2026-10-18T02:30+00:00, prior8high=0.079650, depth_time=2026-10-18T02:30:26+00:00, book20_bid_proxy_usdt=418363, book20_ask_proxy_usdt=355038, funding_indicative=0.000048, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=5162877. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
