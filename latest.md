# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T02:45:44Z**
- feed_generated_utc: 2026-10-18T02:45:46+00:00
- source_sha256: `c8f3dc37eb649d5fa3ad9128b704f67007cd8d1539c7e1e6bb31fcdc4562455e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T02:45+00:00, close=81697.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T02:00+00:00, close=81618.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.154200|-16.73|55.60|-17.20|14673250|6.47|
|TIA_USDT|0.630200|-4.22|22.84|-4.69|74043941|1.59|
|STRK_USDT|0.063550|-3.93|-31.98|-4.40|15618646|3.15|
|EIGEN_USDT|0.248700|-2.96|5.56|-3.43|10778948|4.02|
|FILECOIN_USDT|1.057400|-2.75|-6.24|-3.22|20975538|0.95|
|QNT_USDT|195.320000|-2.53|-20.31|-3.00|70572723|0.51|
|PUMPFUN_USDT|0.004320|-2.08|-24.54|-2.55|23794210|2.31|
|XPL_USDT|0.078740|-1.73|-9.24|-2.20|5178044|1.27|
|ARB_USDT|0.181420|-1.35|-2.81|-1.82|31754352|0.55|
|WLD_USDT|0.489800|-1.17|-12.37|-1.64|66280186|2.04|
|OP_USDT|0.127500|-1.16|-7.97|-1.63|9682577|1.57|
|DOT_USDT|1.105700|-1.04|-12.02|-1.51|16738877|0.90|
|APT_USDT|0.789900|-0.95|-4.46|-1.42|10204679|1.27|
|ZRO_USDT|1.868600|-0.88|-7.52|-1.35|7446494|0.54|
|PEPE_USDT|0.000004|-0.78|-4.36|-1.25|59096301|0.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.789900|0.788100|0.789900|0.56|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.181420|0.180450|0.181420|0.22|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.105700|1.104200|1.105700|1.68|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.248700|0.248200|0.248700|0.75|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.057400|1.054300|1.057400|9.36|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.154200|0.153500|0.154100|0.49|N|Y/Y|N/N|Y|N|
|OP_USDT|0.127500|0.127070|0.127500|0.25|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.27|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004320|0.004299|0.004320|1.88|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.320000|194.070000|195.320000|0.36|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063550|0.063520|0.063550|0.76|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.630200|0.629300|0.630200|2.29|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.489800|0.487900|0.489700|0.51|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078740|0.078460|0.078740|0.31|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.868600|1.867700|1.868600|0.19|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-18T02:45:02+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.800100, depth_time=2026-10-18T02:45:38+00:00, book20_bid_proxy_usdt=94759, book20_ask_proxy_usdt=180897, funding_indicative=-0.000072, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=10204679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-18T02:45:02+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.183400, depth_time=2026-10-18T02:45:25+00:00, book20_bid_proxy_usdt=86963, book20_ask_proxy_usdt=79312, funding_indicative=0.000017, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=31754352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T02:45:02+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=1.119300, depth_time=2026-10-18T02:45:35+00:00, book20_bid_proxy_usdt=379231, book20_ask_proxy_usdt=257649, funding_indicative=0.000027, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=16738877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T02:45:02+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.253300, depth_time=2026-10-18T02:45:14+00:00, book20_bid_proxy_usdt=383351, book20_ask_proxy_usdt=321215, funding_indicative=0.000002, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.96%, turnover=10778948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T02:45:01+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=1.071500, depth_time=2026-10-18T02:45:18+00:00, book20_bid_proxy_usdt=515593, book20_ask_proxy_usdt=626517, funding_indicative=-0.000069, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=20975538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T02:45:01+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.171700, depth_time=2026-10-18T02:45:06+00:00, book20_bid_proxy_usdt=216100, book20_ask_proxy_usdt=99980, funding_indicative=-0.000059, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.73%, turnover=14673250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T02:45:02+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.129000, depth_time=2026-10-18T02:45:34+00:00, book20_bid_proxy_usdt=105717, book20_ask_proxy_usdt=70592, funding_indicative=-0.000139, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=9682577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-18T02:45:02+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.000004, depth_time=2026-10-18T02:45:44+00:00, book20_bid_proxy_usdt=55636, book20_ask_proxy_usdt=49688, funding_indicative=-0.000320, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.78%, turnover=59096301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T02:45:02+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.004390, depth_time=2026-10-18T02:45:22+00:00, book20_bid_proxy_usdt=1444965, book20_ask_proxy_usdt=1309464, funding_indicative=0.000023, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.08%, turnover=23794210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T02:45:02+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=198.820000, depth_time=2026-10-18T02:45:20+00:00, book20_bid_proxy_usdt=65406, book20_ask_proxy_usdt=63537, funding_indicative=-0.000123, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=70572723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T02:45:02+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.064470, depth_time=2026-10-18T02:45:13+00:00, book20_bid_proxy_usdt=260635, book20_ask_proxy_usdt=328295, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.93%, turnover=15618646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T02:45:01+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.649100, depth_time=2026-10-18T02:45:09+00:00, book20_bid_proxy_usdt=215340, book20_ask_proxy_usdt=319946, funding_indicative=-0.000030, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.22%, turnover=74043941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T02:45:01+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.496400, depth_time=2026-10-18T02:45:30+00:00, book20_bid_proxy_usdt=1984032, book20_ask_proxy_usdt=1723032, funding_indicative=-0.000147, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=66280186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T02:45:02+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=0.079650, depth_time=2026-10-18T02:45:25+00:00, book20_bid_proxy_usdt=413369, book20_ask_proxy_usdt=435258, funding_indicative=0.000042, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=5178044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T02:45:01+00:00, last15m_closed_end=2026-10-18T02:45+00:00, prior8high=1.913500, depth_time=2026-10-18T02:45:41+00:00, book20_bid_proxy_usdt=34572, book20_ask_proxy_usdt=56818, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=7446494. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
