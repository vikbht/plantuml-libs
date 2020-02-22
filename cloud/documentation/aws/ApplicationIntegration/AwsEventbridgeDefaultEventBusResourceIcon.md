# AwsEventbridgeDefaultEventBusResourceIcon
```text
elements/aws/ApplicationIntegration/AwsEventbridgeDefaultEventBusResourceIcon
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsEventbridgeDefaultEventBusResourceIcon icon](../../../icons/aws/ApplicationIntegration/AwsEventbridgeDefaultEventBusResourceIcon.png) | ![AwsEventbridgeDefaultEventBusResourceIcon element](AwsEventbridgeDefaultEventBusResourceIcon.element.png) | ![AwsEventbridgeDefaultEventBusResourceIcon card](AwsEventbridgeDefaultEventBusResourceIcon.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the AWS style
include('styles/aws')

' loads the AwsEventbridgeDefaultEventBusResourceIcon element
include('elements/aws/ApplicationIntegration/AwsEventbridgeDefaultEventBusResourceIcon')
AwsEventbridgeDefaultEventBusResourceIcon('element', 'Eventbridge Default Event Bus Resource Icon', 'an optional tech field')
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

' loads the AWS style
include('styles/aws')

' loads the AwsEventbridgeDefaultEventBusResourceIcon element
include('elements/aws/ApplicationIntegration/AwsEventbridgeDefaultEventBusResourceIcon')
AwsEventbridgeDefaultEventBusResourceIcon('element', 'Eventbridge Default Event Bus Resource Icon', 'an optional tech field')
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

' loads the AWS style
include('styles/gcp')

' loads the AwsEventbridgeDefaultEventBusResourceIcon card
include('elements/aws/ApplicationIntegration/AwsEventbridgeDefaultEventBusResourceIcon')
AwsEventbridgeDefaultEventBusResourceIconCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the GCP style
include('styles/gcp')

' loads the AwsEventbridgeDefaultEventBusResourceIcon card
include('elements/aws/ApplicationIntegration/AwsEventbridgeDefaultEventBusResourceIcon')
AwsEventbridgeDefaultEventBusResourceIconCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```