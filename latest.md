# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T19:00:23Z**
- feed_generated_utc: 2026-10-30T19:00:25+00:00
- source_sha256: `5fd30cd47dca5826385d144de152a4dad3e60e6674d321c8dd2cbd257f463691`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T19:00+00:00, close=76616.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T19:00+00:00, close=76616.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EVAA_USDT|1.144100|-11.30|117.96|-10.09|6639658|4.36|
|BLESS_USDT|0.008964|-9.00|9.83|-7.79|14859888|3.35|
|Q_USDT|0.044900|-5.43|-62.05|-4.22|24252851|4.46|
|PUMPFUN_USDT|0.003952|-3.77|-13.39|-2.56|25237610|2.53|
|LIT_USDT|2.729700|-3.34|-17.87|-2.13|12352363|0.37|
|HYPE_USDT|89.839000|-2.71|14.58|-1.50|205493073|0.11|
|INJ_USDT|6.964000|-2.39|-11.54|-1.18|32860758|1.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.008964|0.008535|0.008919|0.56|N|Y/Y|Y/N|Y|N|
|EVAA_USDT|1.144100|1.085100|1.144100|2.14|N|Y/Y|N/N|Y|N|
|HYPE_USDT|89.839000|89.302000|89.826000|1.18|N|Y/Y|N/N|Y|N|
|INJ_USDT|6.964000|6.880000|6.964000|2.69|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.729700|2.687900|2.728400|1.11|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003952|0.003952|0.003946|1.20|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.044900|0.044540|0.044780|1.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T19:00:03+00:00, last15m_closed_end=2026-10-30T19:00+00:00, prior8high=0.009789, depth_time=2026-10-30T19:00:10+00:00, book20_bid_proxy_usdt=10285, book20_ask_proxy_usdt=9707, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.00%, turnover=14859888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T19:00:03+00:00, last15m_closed_end=2026-10-30T19:00+00:00, prior8high=1.298300, depth_time=2026-10-30T19:00:08+00:00, book20_bid_proxy_usdt=7807, book20_ask_proxy_usdt=11340, funding_indicative=0.000160, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-11.30%, turnover=6639658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T19:00:03+00:00, last15m_closed_end=2026-10-30T19:00+00:00, prior8high=92.342000, depth_time=2026-10-30T19:00:19+00:00, book20_bid_proxy_usdt=51019, book20_ask_proxy_usdt=184478, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=205493073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T19:00:03+00:00, last15m_closed_end=2026-10-30T19:00+00:00, prior8high=7.167000, depth_time=2026-10-30T19:00:22+00:00, book20_bid_proxy_usdt=289712, book20_ask_proxy_usdt=222914, funding_indicative=0.000007, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=32860758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T19:00:03+00:00, last15m_closed_end=2026-10-30T19:00+00:00, prior8high=2.811200, depth_time=2026-10-30T19:00:17+00:00, book20_bid_proxy_usdt=25219, book20_ask_proxy_usdt=30168, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=12352363. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T19:00:03+00:00, last15m_closed_end=2026-10-30T19:00+00:00, prior8high=0.004086, depth_time=2026-10-30T19:00:15+00:00, book20_bid_proxy_usdt=287254, book20_ask_proxy_usdt=576771, funding_indicative=-0.000011, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=25237610. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T19:00:03+00:00, last15m_closed_end=2026-10-30T19:00+00:00, prior8high=0.048450, depth_time=2026-10-30T19:00:12+00:00, book20_bid_proxy_usdt=16730, book20_ask_proxy_usdt=30332, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.43%, turnover=24252851. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
