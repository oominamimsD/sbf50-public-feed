# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T12:30:32Z**
- feed_generated_utc: 2026-10-31T12:30:34+00:00
- source_sha256: `bb4d51a84351066f2217011c060a9613a68be8ec9f3ee055918ecf4343125ca6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T12:30+00:00, close=77552.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011873|-37.24|-66.07|-37.21|11163634|3.37|
|Q_USDT|0.031860|-32.89|-73.07|-32.86|12727837|3.14|
|TRX_USDT|0.317620|-5.32|-3.55|-5.29|6975183|0.32|
|BEAT_USDT|0.100630|-4.29|38.62|-4.26|7409946|2.98|
|HYPE_USDT|88.442000|-4.22|12.80|-4.19|94461083|0.23|
|WLD_USDT|0.397000|-3.61|-25.43|-3.58|44762006|2.52|
|FET_USDT|0.161100|-3.30|-13.98|-3.27|5694090|6.21|
|BTW_USDT|1.163200|-3.02|-31.67|-2.99|8605722|5.17|
|DASH_USDT|47.970000|-2.18|-10.91|-2.15|9631833|2.08|
|LTC_USDT|54.970000|-1.34|-5.95|-1.31|5995252|3.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011873|0.010360|0.011859|1.13|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.100630|0.100290|0.100630|0.85|N|Y/N|N/N|Y|N|
|BTW_USDT|1.163200|1.118100|1.160600|2.51|N|N/Y|Y/Y|Y|N|
|DASH_USDT|47.970000|47.700000|47.970000|0.41|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161100|0.160400|0.161000|1.81|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.442000|86.995000|88.442000|0.70|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.970000|54.780000|54.940000|0.74|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031860|0.031390|0.031860|0.70|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.317620|0.315970|0.317620|1.14|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397000|0.394200|0.397000|1.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T12:30:02+00:00, last15m_closed_end=2026-10-31T12:30+00:00, prior8high=0.011724, depth_time=2026-10-31T12:30:09+00:00, book20_bid_proxy_usdt=5466, book20_ask_proxy_usdt=8563, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-37.24%, turnover=11163634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T12:30:02+00:00, last15m_closed_end=2026-10-31T12:30+00:00, prior8high=0.104340, depth_time=2026-10-31T12:30:16+00:00, book20_bid_proxy_usdt=10297, book20_ask_proxy_usdt=10303, funding_indicative=0.000251, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=7409946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T12:30:02+00:00, last15m_closed_end=2026-10-31T12:30+00:00, prior8high=1.204600, depth_time=2026-10-31T12:30:26+00:00, book20_bid_proxy_usdt=12263, book20_ask_proxy_usdt=16112, funding_indicative=-0.000246, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=8605722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T12:30:02+00:00, last15m_closed_end=2026-10-31T12:30+00:00, prior8high=48.200000, depth_time=2026-10-31T12:30:27+00:00, book20_bid_proxy_usdt=699644, book20_ask_proxy_usdt=702497, funding_indicative=-0.000122, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=9631833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T12:30:02+00:00, last15m_closed_end=2026-10-31T12:30+00:00, prior8high=0.162000, depth_time=2026-10-31T12:30:24+00:00, book20_bid_proxy_usdt=1319485, book20_ask_proxy_usdt=511288, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.30%, turnover=5694090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T12:30:02+00:00, last15m_closed_end=2026-10-31T12:30+00:00, prior8high=88.782000, depth_time=2026-10-31T12:30:19+00:00, book20_bid_proxy_usdt=54745, book20_ask_proxy_usdt=98079, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.22%, turnover=94461083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T12:30:02+00:00, last15m_closed_end=2026-10-31T12:30+00:00, prior8high=55.070000, depth_time=2026-10-31T12:30:31+00:00, book20_bid_proxy_usdt=1220590, book20_ask_proxy_usdt=1228237, funding_indicative=-0.000065, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=5995252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T12:30:02+00:00, last15m_closed_end=2026-10-31T12:30+00:00, prior8high=0.033250, depth_time=2026-10-31T12:30:10+00:00, book20_bid_proxy_usdt=48507, book20_ask_proxy_usdt=32307, funding_indicative=-0.000518, next_funding_utc=2026-10-31T13:00:00+00:00, funding_cycle_h=1, 24h_change=-32.89%, turnover=12727837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T12:30:02+00:00, last15m_closed_end=2026-10-31T12:30+00:00, prior8high=0.320970, depth_time=2026-10-31T12:30:14+00:00, book20_bid_proxy_usdt=73440, book20_ask_proxy_usdt=47112, funding_indicative=-0.001000, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.32%, turnover=6975183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T12:30:02+00:00, last15m_closed_end=2026-10-31T12:30+00:00, prior8high=0.397100, depth_time=2026-10-31T12:30:21+00:00, book20_bid_proxy_usdt=2564932, book20_ask_proxy_usdt=2925460, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=44762006. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
