# LowTechFilter（原 FutaFilter）

一款專為臺灣人設計的廣告阻擋規則。

## 為何叫做 LowTechFilter？

這是致敬[美秀集團](https://streetvoice.com/bisiugroup/)。

## 討論群組

嘿，有使用上的問題嗎？  
歡迎到 Telegram 群組上討拍喔。  
https://t.me/adblock_tw

## 訂閱網址

### Adblock 語法（AdBlock, AdGuard）

> LowTechFilter 專門處理網頁上的 DOM 元素處理。例：側邊廣告欄

- <https://filter.futa.gg/filter.txt>

> 隱藏 Google 搜尋結果裡的
> [農場文](https://content-farm-terminator.blogspot.com/2018/12/about-content-farm-terminator.html)
> 專用清單

- <https://filter.futa.gg/hide_farm_from_search.txt>

> removeparam 專門移除網址後的追蹤碼。例：`fbclid=123abc`

- <https://filter.futa.gg/removeparam.txt>

> experimental 實驗性清單，公開測試封鎖對策是否對現行服務有影響，無偵錯能力使用者不建議使用。

- <https://filter.futa.gg/experimental.txt>

> PureView 實驗性清單，將網頁不必要的元素去除，只保留最純粹的瀏覽體驗。

- <https://filter.futa.gg/PureView/news.txt>
- （行動裝置版）<https://filter.futa.gg/PureView/news_mobile.txt>

### hosts 語法（AdGuard Home, Pi-hole, AdAway）

- <https://filter.futa.gg/hosts.txt>
- <https://filter.futa.gg/nofarm_hosts.txt>

> 純粹 domain 而已，若原先有訂閱 hosts.txt 則不需要另外訂閱，此為特定用途。

- <https://filter.futa.gg/hosts-domains.txt>

> 由台灣 165 反詐騙提供

- <https://filter.futa.gg/TW165.txt>

> 由台灣 165 反詐騙提供，並帶有覆寫功能（打開符合規則的網址後會提示已被 165 封鎖）。

- <https://filter.futa.gg/TW165-redirect.txt>

> 由台灣 165 反詐騙提供，純 domain 此為特定用途。

- <https://filter.futa.gg/TW165-domains.txt>

### Surge 語法

> Surge 專用的語法。

- <https://filter.futa.gg/Surge/filters.txt>

## 如何安裝

請參考 [wiki](https://github.com/FutaGuard/FutaFilter/wiki)

## Q&A

Q: 我用了這個規則之後發現我的噗浪連結打不開了欸！！！！\
A: 請服用這個 [userscript](https://greasyfork.org/en/scripts/40884-plurk-no-redirector)


## 贊助

歡迎贊助我們，所有贊助金額將完全用做 FutaGuard DNS 運作以及維護清單費用支出。
<https://core.newebpay.com/EPG/futaguard/FMaZ4E>
