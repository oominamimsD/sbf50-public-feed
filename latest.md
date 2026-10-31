# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T14:00:40Z**
- feed_generated_utc: 2026-10-31T14:00:43+00:00
- source_sha256: `5e00fcb57ca74535f7ae2accd268203afe30eff04574f489cafbdf45bac1ee2d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T14:00+00:00, close=77477.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T14:00+00:00, close=77477.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011751|-38.87|-66.42|-38.74|11608828|2.55|
|Q_USDT|0.032610|-31.31|-72.44|-31.18|11702554|3.06|
|BLESS_USDT|0.010661|-21.05|30.63|-20.92|12229335|4.69|
|BTW_USDT|1.115300|-8.37|-34.48|-8.24|7962242|2.69|
|HYPE_USDT|86.978000|-5.81|10.93|-5.68|94556290|0.12|
|TRX_USDT|0.317830|-5.26|-3.49|-5.13|6538629|0.32|
|BEAT_USDT|0.099690|-5.19|37.33|-5.06|6782810|1.00|
|PEPE_USDT|0.000005|-3.82|1.75|-3.69|100663462|0.81|
|WLD_USDT|0.396600|-3.71|-25.50|-3.58|39505515|2.52|
|FET_USDT|0.161100|-2.42|-13.98|-2.29|5831235|6.21|
|DASH_USDT|48.070000|-2.23|-10.73|-2.10|7855285|2.08|
|ARB_USDT|0.161310|-1.37|-10.34|-1.24|16104765|0.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011751|0.011295|0.011751|0.67|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.161310|0.160760|0.161310|2.46|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.099690|0.098720|0.099740|0.29|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.010661|0.010361|0.010661|0.42|N|N/N|N/Y|Y|N|
|BTW_USDT|1.115300|1.081300|1.114900|1.37|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.070000|47.750000|48.070000|0.56|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161100|0.160400|0.161100|0.45|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|86.978000|87.035000|86.975000|6.94|Y|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.84|N|Y/N|N/N|Y|N|
|Q_USDT|0.032610|0.031490|0.032680|0.68|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.317830|0.317290|0.317740|0.21|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396600|0.394800|0.396500|1.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=0.012080, depth_time=2026-10-31T14:00:09+00:00, book20_bid_proxy_usdt=90344, book20_ask_proxy_usdt=11366, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-38.87%, turnover=11608828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=0.162530, depth_time=2026-10-31T14:00:39+00:00, book20_bid_proxy_usdt=56585, book20_ask_proxy_usdt=92526, funding_indicative=0.000030, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=16104765. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=0.101510, depth_time=2026-10-31T14:00:28+00:00, book20_bid_proxy_usdt=14610, book20_ask_proxy_usdt=10380, funding_indicative=0.000157, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.19%, turnover=6782810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=0.011049, depth_time=2026-10-31T14:00:14+00:00, book20_bid_proxy_usdt=16486, book20_ask_proxy_usdt=16265, funding_indicative=0.000118, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.05%, turnover=12229335. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=1.204600, depth_time=2026-10-31T14:00:19+00:00, book20_bid_proxy_usdt=16681, book20_ask_proxy_usdt=11254, funding_indicative=-0.000336, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.37%, turnover=7962242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=48.210000, depth_time=2026-10-31T14:00:36+00:00, book20_bid_proxy_usdt=719203, book20_ask_proxy_usdt=577535, funding_indicative=-0.000138, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=7855285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=0.161800, depth_time=2026-10-31T14:00:33+00:00, book20_bid_proxy_usdt=1388143, book20_ask_proxy_usdt=1145690, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=5831235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=88.782000, depth_time=2026-10-31T14:00:23+00:00, book20_bid_proxy_usdt=103849, book20_ask_proxy_usdt=104088, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.81%, turnover=94556290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=0.000005, depth_time=2026-10-31T14:00:30+00:00, book20_bid_proxy_usdt=24984, book20_ask_proxy_usdt=40797, funding_indicative=-0.000796, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.82%, turnover=100663462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=0.032280, depth_time=2026-10-31T14:00:12+00:00, book20_bid_proxy_usdt=50164, book20_ask_proxy_usdt=64619, funding_indicative=-0.000464, next_funding_utc=2026-10-31T15:00:00+00:00, funding_cycle_h=1, 24h_change=-31.31%, turnover=11702554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=0.322470, depth_time=2026-10-31T14:00:25+00:00, book20_bid_proxy_usdt=99139, book20_ask_proxy_usdt=58261, funding_indicative=-0.000776, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.26%, turnover=6538629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T14:00:03+00:00, last15m_closed_end=2026-10-31T14:00+00:00, prior8high=0.398800, depth_time=2026-10-31T14:00:29+00:00, book20_bid_proxy_usdt=3136836, book20_ask_proxy_usdt=2629310, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.71%, turnover=39505515. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
