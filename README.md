### management summary


# Hexagonale Architektur
Allem voran DDD
Ports & Adapters
Clean Architecture
Layered Architectrue

Gemeinsamheiten der Architekturen (Nomiklatur; Schichten heißen ähnlich)

Schnittstellen - Vllt. wäre der Begriff "Übergang" im Kontext von hexagonalen Architekturen geeigneter um nicht an technischen Java Interfaces erinnert zu werden.  

## Motivation
Warum hexagonale Architekturen
Was ist das Problem mit POJOs (anemic model)
Was ist das problem mit Spring Boot

## Synthetisches fachliches Beispiel als Voraussetzung für die Applikation
Um konkret zu werden schauen wir uns folgenden UseCase an:


## Überführung in eine klassische Spring Boot Applikation
Hier auf Code eingehen und First-Class-Sitizen von Spring Boot erklären:

@Service
```java
@Service
public class Service{
        // ... 
}
```
@RestController
```java
@RestController
public class WebController{
        // ... 
}
```
@Repository
```java
@SpringBootApplication
public class Application{
        // ... 
}
```


## Transfer in hexagonale Architektur


## Tradeoff
Viel mehr Code !? - Stimmt das wirklich?
Komplex? Hürde zu groß?


## Was gibt es noch?
Axon Framework

Governance Tools wie jQAssistant und ArchUnit eignen sich um auf die anvisierte Architektur zu prüfen.

## Fazit 
Sich besinnen patterns zu lernen und zu berücksichtigen. Development by Framework hinterfragen.