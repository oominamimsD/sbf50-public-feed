# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T22:45:36Z**
- feed_generated_utc: 2026-10-31T22:45:39+00:00
- source_sha256: `450742c5c7326b88406ed48d9ec3521d32175461e0265f431d2daadf73978c6d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T22:45+00:00, close=77615.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T22:00+00:00, close=77631.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.243470|-17.79|44.99|-17.86|28256024|0.82|
|BLESS_USDT|0.009385|-11.16|15.67|-11.23|8015512|3.19|
|IDOL_USDT|0.016860|-3.77|113.41|-3.84|6726061|0.59|
|TRX_USDT|0.300850|-3.67|-8.53|-3.74|10285585|0.33|
|INJ_USDT|7.236000|-3.33|-3.69|-3.40|20991404|1.38|
|ENA_USDT|0.188470|-2.85|0.89|-2.92|47788520|0.53|
|FET_USDT|0.160000|-2.02|-7.13|-2.09|5767444|6.25|
|WLD_USDT|0.397700|-1.65|-13.91|-1.72|34717640|2.52|
|BTW_USDT|1.104200|-1.57|-36.58|-1.64|5697644|2.72|
|APT_USDT|0.631600|-1.43|-10.01|-1.50|5086560|1.58|
|FARTCOIN_USDT|0.120380|-1.31|-1.31|-1.38|6197629|0.83|
|Q_USDT|0.031700|-1.18|-59.83|-1.25|10603607|3.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.631600|0.629300|0.631600|2.35|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009385|0.009313|0.009386|1.28|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.104200|1.086300|1.104200|1.51|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188470|0.187500|0.188470|0.88|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120380|0.120130|0.120410|1.14|N|N/Y|Y/Y|Y|N|
|FET_USDT|0.160000|0.159500|0.160000|1.38|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.016860|0.016323|0.016860|0.64|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.236000|7.198000|7.241000|0.92|N|N/N|Y/Y|Y|N|
|LSK_USDT|0.243470|0.237060|0.243470|0.56|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031700|0.031610|0.031680|1.20|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.300850|0.300840|0.300850|0.24|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397700|0.394900|0.397700|1.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=0.638000, depth_time=2026-10-31T22:45:31+00:00, book20_bid_proxy_usdt=217073, book20_ask_proxy_usdt=132306, funding_indicative=0.000059, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=5086560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=0.010161, depth_time=2026-10-31T22:45:10+00:00, book20_bid_proxy_usdt=8235, book20_ask_proxy_usdt=17054, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.16%, turnover=8015512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=1.131000, depth_time=2026-10-31T22:45:27+00:00, book20_bid_proxy_usdt=33052, book20_ask_proxy_usdt=14791, funding_indicative=-0.000178, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.57%, turnover=5697644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=0.191470, depth_time=2026-10-31T22:45:21+00:00, book20_bid_proxy_usdt=177729, book20_ask_proxy_usdt=123985, funding_indicative=-0.000032, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.85%, turnover=47788520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=0.121480, depth_time=2026-10-31T22:45:33+00:00, book20_bid_proxy_usdt=83183, book20_ask_proxy_usdt=162342, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=6197629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=0.161300, depth_time=2026-10-31T22:45:23+00:00, book20_bid_proxy_usdt=1222906, book20_ask_proxy_usdt=1097799, funding_indicative=-0.000225, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=5767444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=0.017618, depth_time=2026-10-31T22:45:13+00:00, book20_bid_proxy_usdt=3525, book20_ask_proxy_usdt=9707, funding_indicative=0.000083, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=6726061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=7.312000, depth_time=2026-10-31T22:45:19+00:00, book20_bid_proxy_usdt=402321, book20_ask_proxy_usdt=202178, funding_indicative=0.000133, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=20991404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=0.249390, depth_time=2026-10-31T22:45:08+00:00, book20_bid_proxy_usdt=6335, book20_ask_proxy_usdt=9227, funding_indicative=-0.000942, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-17.79%, turnover=28256024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=0.032660, depth_time=2026-10-31T22:45:35+00:00, book20_bid_proxy_usdt=84647, book20_ask_proxy_usdt=47219, funding_indicative=-0.001236, next_funding_utc=2026-10-31T23:00:00+00:00, funding_cycle_h=1, 24h_change=-1.18%, turnover=10603607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=0.306170, depth_time=2026-10-31T22:45:13+00:00, book20_bid_proxy_usdt=135799, book20_ask_proxy_usdt=205556, funding_indicative=-0.000962, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=10285585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T22:45:02+00:00, last15m_closed_end=2026-10-31T22:45+00:00, prior8high=0.400500, depth_time=2026-10-31T22:45:25+00:00, book20_bid_proxy_usdt=3485565, book20_ask_proxy_usdt=2400447, funding_indicative=0.000059, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=34717640. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
