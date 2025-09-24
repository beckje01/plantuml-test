# PlantUML Diagrams

Here is the first diagram, which links to the second diagram.

```plantuml
@startuml first-diagram
Alice -> Bob: Authentication Request [[#second-diagram]]
Bob -> Alice: Authentication Response
@enduml
```

<a name="second-diagram"></a>
## Second Diagram

Here is the second diagram.

```plantuml
@startuml second-diagram
actor User
User -> System: Do something
@enduml
```
