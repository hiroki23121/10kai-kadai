# 10kai-kadai
@startuml
left to right direction
rectangle el-Campus {
    usecase "小テスト" as f1
    usecase "お知らせ閲覧" as f2
    usecase "課題提出" as f3
}
:Student:-->f1
:Student:-->f2
:Student:-->f3
@enduml