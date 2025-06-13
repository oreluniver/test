# PlantUML

```plantuml
@startuml
class Car {
  color
  model
  +start()
  #run()
  #stop()
}

Car <|- Bus
Car *-down- Tire
Car *-down- Engine
Bus o-down- Driver
@enduml
```

![Диаграмма классов](https://www.plantuml.com/plantuml/png/SoWkIImgAStDKRWmvSAE2nikRBxO02Jt0E46XGkxBko-iE5YuyN62_ikREBYIiv9B2vMS4uiKgZcKb18pi_9BmBIkVafgJb0MXjib8OcaAbSL9e7OHINv1S0MRLSN21jDZMw2awbnM2sbcvAVdcUha98Pb4gYe1hNdfcNYeNK9r2FbJ8fIYpBBM8YyiXDIy5w5O0 "Диаграмма классов")

<img src="https://www.plantuml.com/plantuml/png/SoWkIImgAStDKRWmvSAE2nikRBxO02Jt0E46XGkxBko-iE5YuyN62_ikREBYIiv9B2vMS4uiKgZcKb18pi_9BmBIkVafgJb0MXjib8OcaAbSL9e7OHINv1S0MRLSN21jDZMw2awbnM2sbcvAVdcUha98Pb4gYe1hNdfcNYeNK9r2FbJ8fIYpBBM8YyiXDIy5w5O0">

# yUML

<img src="http://yuml.me/diagram/scruffy/class/[note: You can stick notes on diagrams too!{bg:wheat}],[Customer]<>1-orders 0..*>[Order], [Order]++*-*>[LineItem], [Order]-1>[DeliveryMethod], [Order]*-*>[Product], [Category]<->[Product], [DeliveryMethod]^[National], [DeliveryMethod]^[International]" >

# Mermaid

```
flowchart TB
А --> B
C --- D
E -.-> F
G ==> H
I --o J
K --x L
```


```mermaid
flowchart TB
А --> B
C --- D
E -.-> F
G ==> H
I --o J
K --x L
```
