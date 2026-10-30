# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T23:00:27Z**
- feed_generated_utc: 2026-10-30T23:00:29+00:00
- source_sha256: `7a952226126f52fa691011077a43506332b1a0b91ffd20e53d62f999e42443c3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T23:00+00:00, close=76917, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T23:00+00:00, close=76917, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T20:00+00:00, close=76903, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013192|-31.38|-62.30|-30.55|5218925|2.27|
|BLESS_USDT|0.009556|-29.24|17.09|-28.41|12571203|3.14|
|EVAA_USDT|1.119000|-12.72|113.18|-11.89|6629669|1.79|
|BTW_USDT|1.143600|-4.66|-32.82|-3.83|10125859|3.50|
|LIT_USDT|2.736500|-4.45|-17.67|-3.62|8606527|0.36|
|HYPE_USDT|89.244000|-3.35|13.82|-2.52|145069043|0.11|
|TRX_USDT|0.328540|-2.33|-0.24|-1.50|10719520|0.30|
|XMR_USDT|589.920000|-1.93|-2.81|-1.10|10470926|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013192|0.013039|0.013192|0.46|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009556|0.009276|0.009541|1.22|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.143600|1.135400|1.142500|0.45|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.119000|1.082800|1.118200|0.41|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|89.244000|89.002000|89.196000|0.30|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.736500|2.686200|2.736500|0.10|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.328540|0.328970|0.328540|1.18|N|Y/Y|Y/N|Y|N|
|XMR_USDT|589.920000|591.060000|589.610000|1.80|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-30T23:00:03+00:00, last15m_closed_end=2026-10-30T23:00+00:00, prior8high=0.014036, depth_time=2026-10-30T23:00:08+00:00, book20_bid_proxy_usdt=15392, book20_ask_proxy_usdt=7120, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-31.38%, turnover=5218925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-30T23:00:03+00:00, last15m_closed_end=2026-10-30T23:00+00:00, prior8high=0.010060, depth_time=2026-10-30T23:00:11+00:00, book20_bid_proxy_usdt=9013, book20_ask_proxy_usdt=17379, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-29.24%, turnover=12571203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T23:00:03+00:00, last15m_closed_end=2026-10-30T23:00+00:00, prior8high=1.249500, depth_time=2026-10-30T23:00:14+00:00, book20_bid_proxy_usdt=11779, book20_ask_proxy_usdt=20738, funding_indicative=-0.000247, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.66%, turnover=10125859. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T23:00:03+00:00, last15m_closed_end=2026-10-30T23:00+00:00, prior8high=1.132500, depth_time=2026-10-30T23:00:13+00:00, book20_bid_proxy_usdt=15103, book20_ask_proxy_usdt=12369, funding_indicative=0.000151, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.72%, turnover=6629669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T23:00:03+00:00, last15m_closed_end=2026-10-30T23:00+00:00, prior8high=90.590000, depth_time=2026-10-30T23:00:21+00:00, book20_bid_proxy_usdt=135614, book20_ask_proxy_usdt=250226, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=145069043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T23:00:03+00:00, last15m_closed_end=2026-10-30T23:00+00:00, prior8high=2.741100, depth_time=2026-10-30T23:00:15+00:00, book20_bid_proxy_usdt=35455, book20_ask_proxy_usdt=20231, funding_indicative=0.000050, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.45%, turnover=8606527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-30T23:00:03+00:00, last15m_closed_end=2026-10-30T23:00+00:00, prior8high=0.330990, depth_time=2026-10-30T23:00:24+00:00, book20_bid_proxy_usdt=116339, book20_ask_proxy_usdt=83697, funding_indicative=-0.000271, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=10719520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-30T23:00:03+00:00, last15m_closed_end=2026-10-30T23:00+00:00, prior8high=600.250000, depth_time=2026-10-30T23:00:26+00:00, book20_bid_proxy_usdt=6648, book20_ask_proxy_usdt=6386, funding_indicative=0.000315, next_funding_utc=2026-10-31T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=10470926. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
