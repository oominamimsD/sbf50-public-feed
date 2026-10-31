# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T01:00:28Z**
- feed_generated_utc: 2026-10-31T01:00:30+00:00
- source_sha256: `4ed565c14394b2f428dac16871c6c0076d0711a964850cae07a98d64919f8bdf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T01:00+00:00, close=77521.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T01:00+00:00, close=77521.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013321|-29.59|-61.93|-29.52|5868512|0.75|
|BLESS_USDT|0.009607|-28.86|17.71|-28.79|12222619|3.12|
|EVAA_USDT|1.147400|-10.50|118.59|-10.43|6553985|3.49|
|Q_USDT|0.042650|-10.17|-63.95|-10.10|18592266|4.70|
|BTW_USDT|1.109500|-8.85|-34.82|-8.78|9500505|0.90|
|TRX_USDT|0.323080|-3.70|-1.90|-3.63|8491317|1.55|
|HYPE_USDT|89.520000|-3.47|14.17|-3.40|128611343|0.11|
|LIT_USDT|2.774300|-3.13|-16.53|-3.06|6713954|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013321|0.013132|0.013307|0.95|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009607|0.009456|0.009606|1.14|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.109500|1.121700|1.109500|1.01|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.147400|1.114800|1.147400|0.68|N|Y/Y|N/N|Y|N|
|HYPE_USDT|89.520000|89.059000|89.520000|1.20|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.774300|2.731800|2.774300|0.66|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.042650|0.042540|0.042700|6.56|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.323080|0.324160|0.323050|2.85|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T01:00:00+00:00, last15m_closed_end=2026-10-31T01:00+00:00, prior8high=0.014277, depth_time=2026-10-31T01:00:09+00:00, book20_bid_proxy_usdt=5064, book20_ask_proxy_usdt=6235, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-29.59%, turnover=5868512. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T01:00:00+00:00, last15m_closed_end=2026-10-31T01:00+00:00, prior8high=0.010008, depth_time=2026-10-31T01:00:12+00:00, book20_bid_proxy_usdt=10502, book20_ask_proxy_usdt=15136, funding_indicative=0.000177, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-28.86%, turnover=12222619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T01:00:00+00:00, last15m_closed_end=2026-10-31T01:00+00:00, prior8high=1.164800, depth_time=2026-10-31T01:00:19+00:00, book20_bid_proxy_usdt=19928, book20_ask_proxy_usdt=17308, funding_indicative=-0.000325, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.85%, turnover=9500505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T01:00:00+00:00, last15m_closed_end=2026-10-31T01:00+00:00, prior8high=1.176200, depth_time=2026-10-31T01:00:14+00:00, book20_bid_proxy_usdt=7860, book20_ask_proxy_usdt=16747, funding_indicative=0.000143, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.50%, turnover=6553985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T01:00:00+00:00, last15m_closed_end=2026-10-31T01:00+00:00, prior8high=90.278000, depth_time=2026-10-31T01:00:25+00:00, book20_bid_proxy_usdt=130233, book20_ask_proxy_usdt=58543, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.47%, turnover=128611343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T01:00:01+00:00, last15m_closed_end=2026-10-31T01:00+00:00, prior8high=2.784400, depth_time=2026-10-31T01:00:27+00:00, book20_bid_proxy_usdt=40480, book20_ask_proxy_usdt=22650, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.13%, turnover=6713954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T01:00:00+00:00, last15m_closed_end=2026-10-31T01:00+00:00, prior8high=0.049970, depth_time=2026-10-31T01:00:17+00:00, book20_bid_proxy_usdt=18410, book20_ask_proxy_usdt=21054, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.17%, turnover=18592266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T01:00:00+00:00, last15m_closed_end=2026-10-31T01:00+00:00, prior8high=0.331360, depth_time=2026-10-31T01:00:22+00:00, book20_bid_proxy_usdt=209728, book20_ask_proxy_usdt=209730, funding_indicative=-0.000844, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.70%, turnover=8491317. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
