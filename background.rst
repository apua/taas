背景
====================

電腦伺服器 (server) 由非常多的零件 (unit) 構成, 因而有相當多測試需求, 例如
單元測試 (unit test) 與整合測試 (integration test).

成本考量, 零件 (unit) 的 開發/生產/測試 團隊, 往往也分散在不同的地區.
例如, 測試團隊可能會分散在印度與台灣的數個地區以降低人力成本.

分散於各地區的團隊需要自行準備 測試環境 (test environment) 與 待測物 (target).
例如, 測試團隊若要進行伺服器 (server) 與 VMware vSphere 的軟硬體整合測試,
團隊需自行準備符合 測試條件 (specification) 版本的 vSphere 軟體
(可能是開發中的版本), 架設符合 測試條件 (specification) 的網路環境
(eg: 1GbE/10GbE network), 並採購 待測物 (target) 以建立測試系統 (SUT).


角色
--------------------

test engineer
    (SME)
    設計維護 測試案例 (test case),
    並決定適當的 自動化測試工具 或 測試框架

test lead
    安排 測試案例 與 時程

tester
    準備 測試環境 (test environment) 與 待測物 (target) 並進行測試

test library developer
    開發 自動化測試工具


自動化
--------------------

為了執行任務, 各團隊還需要具備 維護相關知識 (domain knowledge) 的 人力資源,
並自行尋找適當的 自動化測試工具 或 測試框架 協助工作進行.


.. TODO:
    [ ] 如果文字表達不清楚, 或許為例子加入圖解
    [ ] 例子如果不符合現實, 就再修正
    [v] roles definition

