# AzureSettings
```text
elements/azure/FlatSymbols/CneEnterprise/AzureSettings
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureSettings icon](../../../../icons/azure/FlatSymbols/CneEnterprise/AzureSettings.png) | ![AzureSettings element](AzureSettings.element.png) | ![AzureSettings card](AzureSettings.card.png) |
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

' loads the AzureSettings element
include('elements/azure/FlatSymbols/CneEnterprise/AzureSettings')
AzureSettings('element', 'Settings', 'an optional tech field')
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

' loads the AzureSettings element
include('elements/azure/FlatSymbols/CneEnterprise/AzureSettings')
AzureSettings('element', 'Settings', 'an optional tech field')
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

' loads the AzureSettings card
include('elements/azure/FlatSymbols/CneEnterprise/AzureSettings')
AzureSettingsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AzureSettings card
include('elements/azure/FlatSymbols/CneEnterprise/AzureSettings')
AzureSettingsCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
