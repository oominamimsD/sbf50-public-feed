# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T06:45:44Z**
- feed_generated_utc: 2026-10-30T06:45:47+00:00
- source_sha256: `a1f0f3f58500f899d62ed8926cfb2b54d93606c73f47109f32a47b5ec36a56c8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T06:45+00:00, close=78517.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T06:00+00:00, close=78524.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T04:00+00:00, close=78198.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CRV_USDT|0.274800|-18.21|-25.18|-14.28|8210077|3.64|
|TIA_USDT|0.460600|-16.13|-18.96|-12.20|19056777|2.17|
|PYTH_USDT|0.061730|-15.65|-16.78|-11.72|5285250|3.24|
|LDO_USDT|0.329700|-12.86|-13.80|-8.93|6546905|3.03|
|FARTCOIN_USDT|0.118390|-11.91|-17.11|-7.98|15370928|0.84|
|PENGU_USDT|0.007212|-11.30|-6.67|-7.37|10020315|1.39|
|APT_USDT|0.625100|-11.11|-19.04|-7.18|12725292|1.60|
|FET_USDT|0.164300|-11.09|-11.33|-7.16|14271115|6.08|
|ETHFI_USDT|0.605500|-10.89|-8.57|-6.96|6010844|1.65|
|BTW_USDT|1.467000|-10.44|-18.04|-6.51|11145800|3.41|
|TRUMPOFFICIAL_USDT|1.557000|-9.89|-10.72|-5.96|11195873|6.42|
|INJ_USDT|7.375000|-9.30|-7.02|-5.37|31340172|1.36|
|SEI_USDT|0.048590|-9.07|-16.32|-5.14|7369591|2.06|
|JASMY_USDT|0.003688|-6.68|-19.05|-2.75|5848923|5.42|
|SHIB_USDT|0.000005|-6.47|-5.65|-2.54|7958110|2.12|
|ETH_USDT|2247.430000|-5.09|-6.26|-1.16|2503432460|0.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.625100|0.615900|0.625100|2.57|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.467000|1.445300|1.466500|1.55|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.274800|0.267600|0.274800|1.16|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.605500|0.596800|0.605500|1.52|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118390|0.117800|0.118390|0.50|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.164300|0.160600|0.164400|1.69|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.375000|7.311000|7.374000|1.18|N|Y/Y|Y/Y|Y|N|
|JASMY_USDT|0.003688|0.003622|0.003685|0.32|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.329700|0.321100|0.329700|1.76|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007212|0.007118|0.007216|0.54|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.061730|0.060400|0.061730|0.43|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.048590|0.047950|0.048600|2.45|N|Y/Y|Y/Y|Y|N|
|SHIB_USDT|0.000005|0.000005|0.000005|0.27|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.460600|0.453800|0.460600|0.66|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.557000|1.545000|1.557000|0.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.628400, depth_time=2026-10-30T06:45:24+00:00, book20_bid_proxy_usdt=142417, book20_ask_proxy_usdt=137230, funding_indicative=-0.000066, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.11%, turnover=12725292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=1.528200, depth_time=2026-10-30T06:45:30+00:00, book20_bid_proxy_usdt=15867, book20_ask_proxy_usdt=11623, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.44%, turnover=11145800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.275900, depth_time=2026-10-30T06:45:08+00:00, book20_bid_proxy_usdt=450935, book20_ask_proxy_usdt=466409, funding_indicative=-0.000146, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-18.21%, turnover=8210077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.614200, depth_time=2026-10-30T06:45:26+00:00, book20_bid_proxy_usdt=252496, book20_ask_proxy_usdt=204252, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.89%, turnover=6010844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.120530, depth_time=2026-10-30T06:45:18+00:00, book20_bid_proxy_usdt=87277, book20_ask_proxy_usdt=54008, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.91%, turnover=15370928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T06:45:01+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.165700, depth_time=2026-10-30T06:45:23+00:00, book20_bid_proxy_usdt=1118777, book20_ask_proxy_usdt=749415, funding_indicative=-0.000232, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.09%, turnover=14271115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T06:45:01+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=7.440000, depth_time=2026-10-30T06:45:36+00:00, book20_bid_proxy_usdt=198042, book20_ask_proxy_usdt=150272, funding_indicative=-0.000027, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.30%, turnover=31340172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JASMY_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.003797, depth_time=2026-10-30T06:45:37+00:00, book20_bid_proxy_usdt=121995, book20_ask_proxy_usdt=83015, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.68%, turnover=5848923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.332300, depth_time=2026-10-30T06:45:15+00:00, book20_bid_proxy_usdt=363237, book20_ask_proxy_usdt=212234, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-12.86%, turnover=6546905. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.007269, depth_time=2026-10-30T06:45:21+00:00, book20_bid_proxy_usdt=151490, book20_ask_proxy_usdt=110967, funding_indicative=-0.000017, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.30%, turnover=10020315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.062440, depth_time=2026-10-30T06:45:14+00:00, book20_bid_proxy_usdt=193980, book20_ask_proxy_usdt=241730, funding_indicative=-0.000214, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.65%, turnover=5285250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.048740, depth_time=2026-10-30T06:45:38+00:00, book20_bid_proxy_usdt=152023, book20_ask_proxy_usdt=141113, funding_indicative=-0.000076, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.07%, turnover=7369591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SHIB_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.000005, depth_time=2026-10-30T06:45:43+00:00, book20_bid_proxy_usdt=133505, book20_ask_proxy_usdt=138953, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.47%, turnover=7958110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T06:45:01+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=0.465200, depth_time=2026-10-30T06:45:11+00:00, book20_bid_proxy_usdt=272714, book20_ask_proxy_usdt=239229, funding_indicative=0.000023, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.13%, turnover=19056777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T06:45:02+00:00, last15m_closed_end=2026-10-30T06:45+00:00, prior8high=1.573000, depth_time=2026-10-30T06:45:33+00:00, book20_bid_proxy_usdt=1142052, book20_ask_proxy_usdt=1593807, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.89%, turnover=11195873. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
