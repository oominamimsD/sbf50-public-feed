# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T22:15:29Z**
- feed_generated_utc: 2026-10-31T22:15:31+00:00
- source_sha256: `dcb1f75c1d483f232077618517e05bdc2f536b92e845d706f221eb52982e0b84`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T22:15+00:00, close=77611, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T22:00+00:00, close=77631.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.244500|-17.44|45.60|-17.50|27993504|2.86|
|BLESS_USDT|0.009440|-10.63|16.35|-10.69|7923004|3.18|
|TRX_USDT|0.302360|-3.19|-8.07|-3.25|10006140|0.33|
|IDOL_USDT|0.016968|-3.15|114.78|-3.21|6690364|4.72|
|BTW_USDT|1.095900|-2.31|-37.06|-2.37|5598021|1.82|
|FET_USDT|0.160400|-1.77|-6.90|-1.83|5666221|6.23|
|WLD_USDT|0.398700|-1.40|-13.70|-1.46|34435734|2.51|
|APT_USDT|0.632700|-1.26|-9.85|-1.32|5028661|1.58|
|FARTCOIN_USDT|0.120840|-0.94|-0.93|-1.00|6055598|0.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.632700|0.629300|0.632700|15.63|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009440|0.009313|0.009440|1.26|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.095900|1.107000|1.095900|0.99|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120840|0.120130|0.120840|4.88|N|N/Y|Y/Y|Y|N|
|FET_USDT|0.160400|0.159500|0.160400|0.34|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.016968|0.016323|0.016968|0.40|N|Y/Y|N/N|Y|N|
|LSK_USDT|0.244500|0.237060|0.244500|0.93|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.302360|0.301700|0.302370|0.43|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398700|0.394900|0.398700|3.31|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-31T22:15:02+00:00, last15m_closed_end=2026-10-31T22:15+00:00, prior8high=0.634500, depth_time=2026-10-31T22:15:24+00:00, book20_bid_proxy_usdt=177092, book20_ask_proxy_usdt=172475, funding_indicative=0.000060, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=5028661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T22:15:02+00:00, last15m_closed_end=2026-10-31T22:15+00:00, prior8high=0.010161, depth_time=2026-10-31T22:15:09+00:00, book20_bid_proxy_usdt=12543, book20_ask_proxy_usdt=13890, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.63%, turnover=7923004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T22:15:02+00:00, last15m_closed_end=2026-10-31T22:15+00:00, prior8high=1.131000, depth_time=2026-10-31T22:15:18+00:00, book20_bid_proxy_usdt=39746, book20_ask_proxy_usdt=35986, funding_indicative=-0.000152, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=5598021. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-31T22:15:02+00:00, last15m_closed_end=2026-10-31T22:15+00:00, prior8high=0.121100, depth_time=2026-10-31T22:15:28+00:00, book20_bid_proxy_usdt=96137, book20_ask_proxy_usdt=82782, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=6055598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T22:15:02+00:00, last15m_closed_end=2026-10-31T22:15+00:00, prior8high=0.161300, depth_time=2026-10-31T22:15:14+00:00, book20_bid_proxy_usdt=1216731, book20_ask_proxy_usdt=1080418, funding_indicative=-0.000200, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=5666221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T22:15:01+00:00, last15m_closed_end=2026-10-31T22:15+00:00, prior8high=0.017700, depth_time=2026-10-31T22:15:13+00:00, book20_bid_proxy_usdt=5710, book20_ask_proxy_usdt=8070, funding_indicative=0.000094, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=6690364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T22:15:01+00:00, last15m_closed_end=2026-10-31T22:15+00:00, prior8high=0.250280, depth_time=2026-10-31T22:15:08+00:00, book20_bid_proxy_usdt=4124, book20_ask_proxy_usdt=7659, funding_indicative=-0.000880, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-17.44%, turnover=27993504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T22:15:02+00:00, last15m_closed_end=2026-10-31T22:15+00:00, prior8high=0.307330, depth_time=2026-10-31T22:15:13+00:00, book20_bid_proxy_usdt=137966, book20_ask_proxy_usdt=52465, funding_indicative=-0.000794, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.19%, turnover=10006140. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T22:15:02+00:00, last15m_closed_end=2026-10-31T22:15+00:00, prior8high=0.397900, depth_time=2026-10-31T22:15:23+00:00, book20_bid_proxy_usdt=2759426, book20_ask_proxy_usdt=3135722, funding_indicative=0.000077, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=34435734. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
