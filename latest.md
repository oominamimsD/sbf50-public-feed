# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T00:30:35Z**
- feed_generated_utc: 2026-11-01T00:30:37+00:00
- source_sha256: `a04f3d0ce36ccafc7217020a0f9369f14c3a3b819b1e0c33a35fd6b599e566da`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T00:30+00:00, close=77570.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T00:00+00:00, close=77522.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.009520|-9.88|17.34|-9.89|7802838|1.05|
|BTW_USDT|1.074700|-4.20|-38.28|-4.21|5483394|0.93|
|Q_USDT|0.030960|-3.49|-60.77|-3.50|10528747|3.23|
|ENA_USDT|0.189200|-2.47|1.29|-2.48|45135345|0.53|
|ZEC_USDT|1254.440000|-2.34|9.53|-2.35|1037088011|0.08|
|FET_USDT|0.159700|-2.20|-7.31|-2.21|5845097|6.26|
|TRX_USDT|0.307230|-1.63|-6.59|-1.64|10682927|0.65|
|AKE_USDT|0.010960|-1.59|-62.50|-1.60|11466668|0.91|
|WLD_USDT|0.398700|-1.40|-13.70|-1.41|34220241|2.51|
|FARTCOIN_USDT|0.120380|-1.31|-1.31|-1.32|6416494|0.83|
|XLM_USDT|0.169500|-1.30|0.64|-1.31|21428273|0.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010960|0.010836|0.010960|0.75|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009520|0.009300|0.009520|0.54|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.074700|1.066200|1.074700|1.32|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.189200|0.187820|0.189200|1.04|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120380|0.119850|0.120380|1.12|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.159700|0.159200|0.159700|0.20|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.030960|0.030800|0.030960|1.35|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.307230|0.300760|0.307230|0.91|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398700|0.397300|0.398700|1.45|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.169500|0.169370|0.169500|0.79|N|N/N|N/N|Y|N|
|ZEC_USDT|1254.440000|1243.100000|1254.440000|0.77|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=0.011276, depth_time=2026-11-01T00:30:27+00:00, book20_bid_proxy_usdt=16210, book20_ask_proxy_usdt=14959, funding_indicative=-0.000267, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.59%, turnover=11466668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=0.009571, depth_time=2026-11-01T00:30:08+00:00, book20_bid_proxy_usdt=14157, book20_ask_proxy_usdt=14912, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.88%, turnover=7802838. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=1.111500, depth_time=2026-11-01T00:30:10+00:00, book20_bid_proxy_usdt=18367, book20_ask_proxy_usdt=19376, funding_indicative=-0.000187, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.20%, turnover=5483394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=0.190190, depth_time=2026-11-01T00:30:16+00:00, book20_bid_proxy_usdt=225567, book20_ask_proxy_usdt=124583, funding_indicative=0.000007, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.47%, turnover=45135345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=0.120900, depth_time=2026-11-01T00:30:32+00:00, book20_bid_proxy_usdt=77720, book20_ask_proxy_usdt=79688, funding_indicative=0.000050, next_funding_utc=2026-11-01T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=6416494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=0.160600, depth_time=2026-11-01T00:30:22+00:00, book20_bid_proxy_usdt=1574107, book20_ask_proxy_usdt=920315, funding_indicative=-0.000133, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=5845097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=0.032150, depth_time=2026-11-01T00:30:14+00:00, book20_bid_proxy_usdt=40778, book20_ask_proxy_usdt=42703, funding_indicative=-0.000910, next_funding_utc=2026-11-01T01:00:00+00:00, funding_cycle_h=1, 24h_change=-3.49%, turnover=10528747. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=0.304860, depth_time=2026-11-01T00:30:23+00:00, book20_bid_proxy_usdt=88509, book20_ask_proxy_usdt=64927, funding_indicative=-0.001379, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=10682927. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=0.400300, depth_time=2026-11-01T00:30:29+00:00, book20_bid_proxy_usdt=2617201, book20_ask_proxy_usdt=2998693, funding_indicative=0.000090, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=34220241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=0.170240, depth_time=2026-11-01T00:30:34+00:00, book20_bid_proxy_usdt=183347, book20_ask_proxy_usdt=194499, funding_indicative=-0.000058, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=21428273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T00:30:00+00:00, last15m_closed_end=2026-11-01T00:30+00:00, prior8high=1279.850000, depth_time=2026-11-01T00:30:18+00:00, book20_bid_proxy_usdt=189004, book20_ask_proxy_usdt=159462, funding_indicative=-0.000057, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=1037088011. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
