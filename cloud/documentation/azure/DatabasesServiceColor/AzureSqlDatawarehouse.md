# AzureSqlDatawarehouse
```text
elements/azure/DatabasesServiceColor/AzureSqlDatawarehouse
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureSqlDatawarehouse icon](../../../icons/azure/DatabasesServiceColor/AzureSqlDatawarehouse.png) | ![AzureSqlDatawarehouse element](AzureSqlDatawarehouse.element.png) | ![AzureSqlDatawarehouse card](AzureSqlDatawarehouse.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/azure')

' loads the AzureSqlDatawarehouse element
include('elements/azure/DatabasesServiceColor/AzureSqlDatawarehouse')
AzureSqlDatawarehouse('element', 'Sql Datawarehouse', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/azure')

' loads the AzureSqlDatawarehouse element
include('elements/azure/DatabasesServiceColor/AzureSqlDatawarehouse')
AzureSqlDatawarehouse('element', 'Sql Datawarehouse', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/azure')

' loads the AzureSqlDatawarehouse card
include('elements/azure/DatabasesServiceColor/AzureSqlDatawarehouse')
AzureSqlDatawarehouseCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/azure')

' loads the AzureSqlDatawarehouse card
include('elements/azure/DatabasesServiceColor/AzureSqlDatawarehouse')
AzureSqlDatawarehouseCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
