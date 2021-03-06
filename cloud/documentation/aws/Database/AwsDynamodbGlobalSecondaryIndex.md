# AwsDynamodbGlobalSecondaryIndex
```text
elements/aws/Database/AwsDynamodbGlobalSecondaryIndex
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsDynamodbGlobalSecondaryIndex icon](../../../icons/aws/Database/AwsDynamodbGlobalSecondaryIndex.png) | ![AwsDynamodbGlobalSecondaryIndex element](AwsDynamodbGlobalSecondaryIndex.element.png) | ![AwsDynamodbGlobalSecondaryIndex card](AwsDynamodbGlobalSecondaryIndex.card.png) |
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

' loads the AwsDynamodbGlobalSecondaryIndex element
include('elements/aws/Database/AwsDynamodbGlobalSecondaryIndex')
AwsDynamodbGlobalSecondaryIndex('element', 'Dynamodb Global Secondary Index', 'an optional tech field')
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

' loads the AwsDynamodbGlobalSecondaryIndex element
include('elements/aws/Database/AwsDynamodbGlobalSecondaryIndex')
AwsDynamodbGlobalSecondaryIndex('element', 'Dynamodb Global Secondary Index', 'an optional tech field')
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

' loads the AwsDynamodbGlobalSecondaryIndex card
include('elements/aws/Database/AwsDynamodbGlobalSecondaryIndex')
AwsDynamodbGlobalSecondaryIndexCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsDynamodbGlobalSecondaryIndex card
include('elements/aws/Database/AwsDynamodbGlobalSecondaryIndex')
AwsDynamodbGlobalSecondaryIndexCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
