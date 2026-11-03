# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T14:30:32Z**
- feed_generated_utc: 2026-11-03T14:30:34+00:00
- source_sha256: `6a90dc5a0b3befd664a34723f1fe22154c0abc5800b4d2f8b2098095939b8b8d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T14:30+00:00, close=77116.5, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T14:00+00:00, close=77368.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004127|-24.99|-86.59|-24.51|12477507|2.42|
|UAI_USDT|0.104200|-21.47|-58.11|-20.99|9013126|9.58|
|BTW_USDT|0.988800|-9.84|-17.30|-9.36|8567182|3.04|
|XPL_USDT|0.064190|-7.74|-13.59|-7.26|11499468|1.56|
|TIA_USDT|0.439100|-3.89|-18.03|-3.41|13608829|4.55|
|NEAR_USDT|3.860000|-3.74|-15.59|-3.26|82379641|2.59|
|QNT_USDT|195.010000|-3.67|-7.26|-3.19|53723978|0.51|
|ENA_USDT|0.169730|-3.03|-19.31|-2.55|71324516|0.59|
|WLD_USDT|0.371400|-2.57|-16.53|-2.09|49509013|2.69|
|DASH_USDT|46.100000|-2.33|-11.71|-1.85|9314353|4.34|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004127|0.004076|0.004128|1.39|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.988800|0.937700|0.988800|0.40|N|N/N|Y/Y|Y|N|
|DASH_USDT|46.100000|45.940000|46.120000|1.49|N|N/N|Y/Y|Y|N|
|ENA_USDT|0.169730|0.169980|0.169880|1.43|Y|Y/N|Y/Y|Y|N|
|NEAR_USDT|3.860000|3.854000|3.865000|0.74|N|N/N|Y/Y|Y|N|
|QNT_USDT|195.010000|195.680000|195.100000|2.32|Y|N/N|Y/Y|Y|N|
|TIA_USDT|0.439100|0.440200|0.439200|0.99|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.104200|0.114400|0.104600|6.43|Y|Y/N|Y/Y|Y|N|
|WLD_USDT|0.371400|0.370900|0.371600|1.31|N|Y/N|Y/Y|Y|N|
|XPL_USDT|0.064190|0.064300|0.064210|0.47|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T14:30:02+00:00, last15m_closed_end=2026-11-03T14:30+00:00, prior8high=0.004535, depth_time=2026-11-03T14:30:08+00:00, book20_bid_proxy_usdt=50572, book20_ask_proxy_usdt=47962, funding_indicative=-0.000851, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.99%, turnover=12477507. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T14:30:03+00:00, last15m_closed_end=2026-11-03T14:30+00:00, prior8high=1.032400, depth_time=2026-11-03T14:30:13+00:00, book20_bid_proxy_usdt=14435, book20_ask_proxy_usdt=27828, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.84%, turnover=8567182. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T14:30:03+00:00, last15m_closed_end=2026-11-03T14:30+00:00, prior8high=46.820000, depth_time=2026-11-03T14:30:31+00:00, book20_bid_proxy_usdt=418317, book20_ask_proxy_usdt=654959, funding_indicative=0.000093, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=9314353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T14:30:02+00:00, last15m_closed_end=2026-11-03T14:30+00:00, prior8high=0.174220, depth_time=2026-11-03T14:30:26+00:00, book20_bid_proxy_usdt=130647, book20_ask_proxy_usdt=156087, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.03%, turnover=71324516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T14:30:02+00:00, last15m_closed_end=2026-11-03T14:30+00:00, prior8high=3.945000, depth_time=2026-11-03T14:30:21+00:00, book20_bid_proxy_usdt=952819, book20_ask_proxy_usdt=3641115, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=82379641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T14:30:03+00:00, last15m_closed_end=2026-11-03T14:30+00:00, prior8high=200.480000, depth_time=2026-11-03T14:30:23+00:00, book20_bid_proxy_usdt=37791, book20_ask_proxy_usdt=72449, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=53723978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T14:30:03+00:00, last15m_closed_end=2026-11-03T14:30+00:00, prior8high=0.449000, depth_time=2026-11-03T14:30:18+00:00, book20_bid_proxy_usdt=319698, book20_ask_proxy_usdt=368563, funding_indicative=-0.000020, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.89%, turnover=13608829. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-03T14:30:02+00:00, last15m_closed_end=2026-11-03T14:30+00:00, prior8high=0.172500, depth_time=2026-11-03T14:30:11+00:00, book20_bid_proxy_usdt=128424, book20_ask_proxy_usdt=123911, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.47%, turnover=9013126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-03T14:30:03+00:00, last15m_closed_end=2026-11-03T14:30+00:00, prior8high=0.379000, depth_time=2026-11-03T14:30:29+00:00, book20_bid_proxy_usdt=875214, book20_ask_proxy_usdt=3720447, funding_indicative=-0.000052, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=49509013. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T14:30:03+00:00, last15m_closed_end=2026-11-03T14:30+00:00, prior8high=0.065540, depth_time=2026-11-03T14:30:16+00:00, book20_bid_proxy_usdt=246037, book20_ask_proxy_usdt=409277, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.74%, turnover=11499468. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
