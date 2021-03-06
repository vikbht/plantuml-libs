# AzureGateway
```text
elements/azure/FlatSymbols/CneEnterprise/AzureGateway
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureGateway icon](../../../../icons/azure/FlatSymbols/CneEnterprise/AzureGateway.png) | ![AzureGateway element](AzureGateway.element.png) | ![AzureGateway card](AzureGateway.card.png) |
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

' loads the AzureGateway element
include('elements/azure/FlatSymbols/CneEnterprise/AzureGateway')
AzureGateway('element', 'Gateway', 'an optional tech field')
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

' loads the AzureGateway element
include('elements/azure/FlatSymbols/CneEnterprise/AzureGateway')
AzureGateway('element', 'Gateway', 'an optional tech field')
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

' loads the AzureGateway card
include('elements/azure/FlatSymbols/CneEnterprise/AzureGateway')
AzureGatewayCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureGateway card
include('elements/azure/FlatSymbols/CneEnterprise/AzureGateway')
AzureGatewayCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
