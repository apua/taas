摘要
====================

硬體生產的品質仰賴分工合作的測試團隊.
TaaS 架構集中待測系統 (SUT) 進而 分享資源 (share resource)
降低測試成本, 同時藉由一致的測試框架讓 test engineer 專注
提升 測試可靠性 (integrity).

本論文將探討 TaaS 架構的設計與實作.


keywords:

- TaaS
- CDN
- distributed system
- automated test framework
- deployment automation
- iCalendar
- NewSQL


.. TODO:
    [ ] review keywords (candidates above)
    [ ] review abstract; 或許不應該把範圍寫太大
        大可以在 summray 或 future works 把範圍再提升
    [ ] 好像應該把整份文件的焦點都放在 *測試* 比較好
        晚點全部更正


..  Drafts:


    #.  本論文針對軟硬體測試, 提出方法架構分散式結構的服務,
        以提升整體效率並降低各方面成本,
        滿足跨地區/上百人團隊/高價值設備/time-critical(?) 的需求

    #.  硬體的開發/製造/測試, 往往分散在不同的區域, 由不同的團隊與專業人士分工合作,
        各團隊需要準備必要的硬體環境以進行各自的工作.
        此論文提出一分散式架構 TaaS -- "Test as a Service",
        使不同區域的團隊分享開發資源, 降低 生產/架設/維護/... 等各方面成本.
