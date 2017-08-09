解決方案與價值
====================

本論文將提出一個 TaaS - Test as a Service 架構.
TaaS 提供平台讓使用者取用別的團隊的硬體資源, 部署測試環境, 與進行測試.
包含三個部分:

- resource management (including resource reservation)
- auto deployment
- test harness (test framework)

透過抽象化硬體資源, 此架構令分散各處的硬體資源可共享, 進而降低生產/維護的成本.

.. PaaS


.. 這個架構提供整合的線上測試框架讓使用者設計與執行 測試案例,
.. 並將軟硬體資源抽象化 供分散各處的團隊共享使用.

.. 在這個架構下, 由於硬體資源共享, 減少不必要的生產/維護成本;
.. 除此之外, 統一的測試框架讓使用者專注改進 test integrity.


..  solution: TaaS

..  update with Johnny:
    -   會找 JDP (join design parter) 是為了 cost down
        cost down 的內容正就是人力
    -   事實上 JDP 的工作包含開發生產, 所以使用 TaaS 架構的話,
        data center 理應會在 JDP 那邊
    -   TaaS 的第一個價值 -- as a service,
        tester 想測就測, 不必為測試環境奔波
    -   要解釋集中測試資源的好處:

        *   減少生產維護成本
        *   維護與設置 測試環境 專業化, 集中價值, 減少 domain knowledge 分散

    -   從 PO 的角度, 認同 improvement of test integrity.
        提供 TaaS 服務集中所有 test case 有助改進 test case 之中的偏差,
        增進 test integrity
