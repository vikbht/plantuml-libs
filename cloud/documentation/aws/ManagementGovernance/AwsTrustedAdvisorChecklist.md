# AwsTrustedAdvisorChecklist
```text
elements/aws/ManagementGovernance/AwsTrustedAdvisorChecklist
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsTrustedAdvisorChecklist icon](../../../icons/aws/ManagementGovernance/AwsTrustedAdvisorChecklist.png) | ![AwsTrustedAdvisorChecklist element](AwsTrustedAdvisorChecklist.element.png) | ![AwsTrustedAdvisorChecklist card](AwsTrustedAdvisorChecklist.card.png) |
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
include('styles/aws')

' loads the AwsTrustedAdvisorChecklist element
include('elements/aws/ManagementGovernance/AwsTrustedAdvisorChecklist')
AwsTrustedAdvisorChecklist('element', 'Trusted Advisor Checklist', 'an optional tech field')
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
include('styles/aws')

' loads the AwsTrustedAdvisorChecklist element
include('elements/aws/ManagementGovernance/AwsTrustedAdvisorChecklist')
AwsTrustedAdvisorChecklist('element', 'Trusted Advisor Checklist', 'an optional tech field')
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
include('styles/aws')

' loads the AwsTrustedAdvisorChecklist card
include('elements/aws/ManagementGovernance/AwsTrustedAdvisorChecklist')
AwsTrustedAdvisorChecklistCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
include('styles/aws')

' loads the AwsTrustedAdvisorChecklist card
include('elements/aws/ManagementGovernance/AwsTrustedAdvisorChecklist')
AwsTrustedAdvisorChecklistCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
