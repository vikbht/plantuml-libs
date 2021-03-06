# AwsFirewallManager
```text
elements/aws/SecurityIdentityCompliance/AwsFirewallManager
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AwsFirewallManager icon](../../../icons/aws/SecurityIdentityCompliance/AwsFirewallManager.png) | ![AwsFirewallManager element](AwsFirewallManager.element.png) | ![AwsFirewallManager card](AwsFirewallManager.card.png) |
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

' loads the AwsFirewallManager element
include('elements/aws/SecurityIdentityCompliance/AwsFirewallManager')
AwsFirewallManager('element', 'Firewall Manager', 'an optional tech field')
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

' loads the AwsFirewallManager element
include('elements/aws/SecurityIdentityCompliance/AwsFirewallManager')
AwsFirewallManager('element', 'Firewall Manager', 'an optional tech field')
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

' loads the AwsFirewallManager card
include('elements/aws/SecurityIdentityCompliance/AwsFirewallManager')
AwsFirewallManagerCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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

' loads the AwsFirewallManager card
include('elements/aws/SecurityIdentityCompliance/AwsFirewallManager')
AwsFirewallManagerCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
