# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T11:00:35Z**
- feed_generated_utc: 2026-10-20T11:00:39+00:00
- source_sha256: `6866860e71c8d4f47f72b123c3e4798eb5499dfb438560e45d8260ce8ec271ab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T11:00+00:00, close=81518.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T11:00+00:00, close=81518.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.068020|-21.85|308.23|-21.37|9118483|1.77|
|NEAR_USDT|4.678000|-5.07|-15.69|-4.59|164862910|2.14|
|SAND_USDT|0.056910|-4.44|-8.34|-3.96|5334770|1.76|
|ARB_USDT|0.189810|-3.98|0.71|-3.50|93659893|0.53|
|ATOM_USDT|1.720000|-2.93|-5.90|-2.45|5032114|5.81|
|AKE_USDT|0.029913|-2.77|27.07|-2.29|5876164|0.33|
|UNI_USDT|7.146000|-2.64|-3.66|-2.16|9904632|1.40|
|QNT_USDT|193.730000|-1.91|-15.17|-1.43|74418236|0.52|
|SEI_USDT|0.059810|-1.82|-9.88|-1.34|5651717|1.67|
|TAO_USDT|263.810000|-1.67|-7.85|-1.19|56500024|1.14|
|FILECOIN_USDT|1.006300|-1.67|-13.42|-1.19|6256864|0.99|
|STRK_USDT|0.056370|-1.50|-37.82|-1.02|18354748|1.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068020|0.066550|0.068132|0.52|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.029913|0.030372|0.029823|1.24|N|Y/N|N/N|Y|N|
|ARB_USDT|0.189810|0.188610|0.189810|0.42|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.720000|1.711000|1.720000|0.31|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.006300|0.999300|1.006300|0.41|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.678000|4.654000|4.678000|1.36|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.730000|191.280000|193.730000|0.58|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.056910|0.056320|0.056910|2.66|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059810|0.059410|0.059810|0.51|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.056370|0.055460|0.056370|1.30|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.810000|261.790000|263.800000|0.68|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.146000|7.093000|7.146000|0.45|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=0.072535, depth_time=2026-10-20T11:00:07+00:00, book20_bid_proxy_usdt=3133, book20_ask_proxy_usdt=4014, funding_indicative=0.000047, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.85%, turnover=9118483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=0.035392, depth_time=2026-10-20T11:00:20+00:00, book20_bid_proxy_usdt=14720, book20_ask_proxy_usdt=17687, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=5876164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=0.190590, depth_time=2026-10-20T11:00:15+00:00, book20_bid_proxy_usdt=76117, book20_ask_proxy_usdt=115336, funding_indicative=0.000099, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=93659893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=1.731000, depth_time=2026-10-20T11:00:17+00:00, book20_bid_proxy_usdt=1598561, book20_ask_proxy_usdt=1003928, funding_indicative=0.000067, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=5032114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=1.009400, depth_time=2026-10-20T11:00:27+00:00, book20_bid_proxy_usdt=592489, book20_ask_proxy_usdt=709145, funding_indicative=-0.000015, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=6256864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=4.756000, depth_time=2026-10-20T11:00:11+00:00, book20_bid_proxy_usdt=4241064, book20_ask_proxy_usdt=4434898, funding_indicative=0.000077, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.07%, turnover=164862910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=193.820000, depth_time=2026-10-20T11:00:24+00:00, book20_bid_proxy_usdt=120892, book20_ask_proxy_usdt=84445, funding_indicative=0.000049, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=74418236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=0.056960, depth_time=2026-10-20T11:00:13+00:00, book20_bid_proxy_usdt=1050576, book20_ask_proxy_usdt=1051459, funding_indicative=-0.001722, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.44%, turnover=5334770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=0.059910, depth_time=2026-10-20T11:00:26+00:00, book20_bid_proxy_usdt=277548, book20_ask_proxy_usdt=394546, funding_indicative=-0.000015, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=5651717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=0.056500, depth_time=2026-10-20T11:00:33+00:00, book20_bid_proxy_usdt=634023, book20_ask_proxy_usdt=738459, funding_indicative=0.000039, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=18354748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=263.770000, depth_time=2026-10-20T11:00:29+00:00, book20_bid_proxy_usdt=140536, book20_ask_proxy_usdt=70324, funding_indicative=0.000044, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=56500024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T11:00:03+00:00, last15m_closed_end=2026-10-20T11:00+00:00, prior8high=7.157000, depth_time=2026-10-20T11:00:22+00:00, book20_bid_proxy_usdt=1732687, book20_ask_proxy_usdt=2121784, funding_indicative=0.000079, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=9904632. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
