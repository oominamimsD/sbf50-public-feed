# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-22T00:30:43Z**
- feed_generated_utc: 2026-10-22T00:30:46+00:00
- source_sha256: `96b040f54816d4edbaeb5f5b4dd84510cca46e69c585c62e56fa20778afb1a55`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-22T00:30+00:00, close=84192.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IOST_USDT|0.000981|-32.99|22.57|-32.63|15121179|8.15|
|DOOD_USDT|0.002324|-18.28|63.89|-17.92|9109088|4.31|
|BR_USDT|0.484560|-10.52|18.83|-10.16|14426130|1.03|
|AKE_USDT|0.024544|-8.04|-5.16|-7.68|10895496|1.22|
|STRK_USDT|0.057040|-7.95|-26.09|-7.59|24512162|1.75|
|ZRO_USDT|1.937700|-7.60|2.31|-7.24|7389632|0.52|
|TIA_USDT|0.598200|-5.42|12.12|-5.06|40247086|1.67|
|ARB_USDT|0.189040|-3.84|3.78|-3.48|31752370|0.53|
|ICP_USDT|2.888000|-2.62|-3.63|-2.26|5717766|3.46|
|DOT_USDT|1.151700|-2.39|2.41|-2.03|17135509|0.87|
|AVAX_USDT|9.681000|-2.36|-1.38|-2.00|157948923|1.03|
|FET_USDT|0.196100|-2.24|-3.82|-1.88|7621010|5.10|
|OP_USDT|0.129000|-2.19|-6.75|-1.83|6853276|3.10|
|HBAR_USDT|0.084070|-2.17|0.08|-1.81|14106655|1.19|
|INJ_USDT|8.568000|-2.16|12.16|-1.80|50639154|1.17|
|LDO_USDT|0.406200|-2.16|0.09|-1.80|5235183|2.46|
|AAVE_USDT|155.560000|-1.86|-0.21|-1.50|133002357|0.64|
|TAO_USDT|272.400000|-1.84|1.65|-1.48|61789819|1.10|
|DOGE_USDT|0.082010|-1.72|0.03|-1.36|84109672|1.22|
|SUI_USDT|1.032300|-1.62|2.40|-1.26|65855787|0.97|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.024544|0.023696|0.024544|0.20|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.189040|0.187440|0.189040|0.60|N|Y/Y|Y/N|N|N|
|AVAX_USDT|9.681000|9.639000|9.681000|0.69|N|Y/Y|Y/N|N|N|
|BR_USDT|0.484560|0.479330|0.484560|0.57|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002324|0.002241|0.002324|0.48|N|Y/Y|N/N|N|N|
|DOT_USDT|1.151700|1.139000|1.151700|0.60|N|Y/Y|Y/N|N|N|
|FET_USDT|0.196100|0.195000|0.196100|1.22|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084070|0.083560|0.084070|0.96|N|Y/Y|Y/N|N|N|
|ICP_USDT|2.888000|2.880000|2.888000|2.97|N|Y/Y|Y/N|N|N|
|INJ_USDT|8.568000|8.575000|8.568000|0.60|N|Y/Y|Y/Y|N|N|
|IOST_USDT|0.000981|0.000946|0.000981|0.64|N|Y/Y|Y/N|N|N|
|OP_USDT|0.129000|0.128270|0.129010|0.81|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.057040|0.057160|0.057040|0.91|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.598200|0.595900|0.598400|0.93|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.937700|1.932700|1.937700|1.66|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=0.024855, depth_time=2026-10-22T00:30:15+00:00, book20_bid_proxy_usdt=16195, book20_ask_proxy_usdt=16749, funding_indicative=0.000050, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.04%, turnover=10895496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=0.192520, depth_time=2026-10-22T00:30:25+00:00, book20_bid_proxy_usdt=57065, book20_ask_proxy_usdt=69186, funding_indicative=0.000013, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.84%, turnover=31752370. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=9.790000, depth_time=2026-10-22T00:30:32+00:00, book20_bid_proxy_usdt=892235, book20_ask_proxy_usdt=846453, funding_indicative=0.000020, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=157948923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=0.498100, depth_time=2026-10-22T00:30:13+00:00, book20_bid_proxy_usdt=4322, book20_ask_proxy_usdt=3271, funding_indicative=-0.000261, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.52%, turnover=14426130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=0.002421, depth_time=2026-10-22T00:30:10+00:00, book20_bid_proxy_usdt=177085, book20_ask_proxy_usdt=138576, funding_indicative=-0.000135, next_funding_utc=2026-10-22T01:00:00+00:00, funding_cycle_h=1, 24h_change=-18.28%, turnover=9109088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=1.159800, depth_time=2026-10-22T00:30:29+00:00, book20_bid_proxy_usdt=336878, book20_ask_proxy_usdt=300228, funding_indicative=-0.000128, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=17135509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=0.197000, depth_time=2026-10-22T00:30:33+00:00, book20_bid_proxy_usdt=1872483, book20_ask_proxy_usdt=1407522, funding_indicative=0.000100, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=7621010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=0.084910, depth_time=2026-10-22T00:30:39+00:00, book20_bid_proxy_usdt=604827, book20_ask_proxy_usdt=843328, funding_indicative=-0.000012, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=14106655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=2.925000, depth_time=2026-10-22T00:30:26+00:00, book20_bid_proxy_usdt=1093570, book20_ask_proxy_usdt=1064996, funding_indicative=0.000040, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=5717766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=8.735000, depth_time=2026-10-22T00:30:42+00:00, book20_bid_proxy_usdt=280972, book20_ask_proxy_usdt=205927, funding_indicative=0.000215, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=50639154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IOST_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=0.001448, depth_time=2026-10-22T00:30:08+00:00, book20_bid_proxy_usdt=11485, book20_ask_proxy_usdt=12065, funding_indicative=-0.007138, next_funding_utc=2026-10-22T01:00:00+00:00, funding_cycle_h=1, 24h_change=-32.99%, turnover=15121179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=0.130270, depth_time=2026-10-22T00:30:37+00:00, book20_bid_proxy_usdt=105305, book20_ask_proxy_usdt=119106, funding_indicative=-0.000015, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=6853276. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=0.059630, depth_time=2026-10-22T00:30:18+00:00, book20_bid_proxy_usdt=630302, book20_ask_proxy_usdt=585032, funding_indicative=-0.000033, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.95%, turnover=24512162. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=0.615100, depth_time=2026-10-22T00:30:23+00:00, book20_bid_proxy_usdt=329367, book20_ask_proxy_usdt=266627, funding_indicative=-0.000152, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.42%, turnover=40247086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-22T00:30:00+00:00, last15m_closed_end=2026-10-22T00:30+00:00, prior8high=1.967500, depth_time=2026-10-22T00:30:20+00:00, book20_bid_proxy_usdt=68624, book20_ask_proxy_usdt=64769, funding_indicative=0.000017, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.60%, turnover=7389632. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
