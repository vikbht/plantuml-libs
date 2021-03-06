# AzureManagementPoint
```text
elements/azure/FlatSymbols/CneSystemCenter/AzureManagementPoint
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureManagementPoint icon](../../../../icons/azure/FlatSymbols/CneSystemCenter/AzureManagementPoint.png) | ![AzureManagementPoint element](AzureManagementPoint.element.png) | ![AzureManagementPoint card](AzureManagementPoint.card.png) |
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

' loads the AzureManagementPoint element
include('elements/azure/FlatSymbols/CneSystemCenter/AzureManagementPoint')
AzureManagementPoint('element', 'Management Point', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../../"

' loads the library
!include ../../../../library.puml

' loads the style
include('styles/azure')

' loads the AzureManagementPoint element
include('elements/azure/FlatSymbols/CneSystemCenter/AzureManagementPoint')
AzureManagementPoint('element', 'Management Point', 'an optional tech field')
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

' loads the AzureManagementPoint card
include('elements/azure/FlatSymbols/CneSystemCenter/AzureManagementPoint')
AzureManagementPointCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../../"

' loads the library
!include ../../../../library.puml

' loads the style
include('styles/azure')

' loads the AzureManagementPoint card
include('elements/azure/FlatSymbols/CneSystemCenter/AzureManagementPoint')
AzureManagementPointCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
