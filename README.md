# Hi, I'm Dev 👋
### Software Development Student | Java Enthusiast | Melbourne, VIC

I am currently building my skills in Software Development with a focus on Object-Oriented Programming and Java. I'm actively looking for entry-level IT/Support roles to apply my technical troubleshooting and coding skills in a professional environment.

- 🛠️ **Current Focus:** Java, OOP Design, and System Documentation.
- 🤝 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/devanshgambhir55555)
- 🔭 **Project Highlight:** WorldWanderer Travel Portal
```mermaid
classDiagram
    class Flight {
        +String flightNumber
        +String airline
        +double price
        +displayDetails()
    }
    class SearchCriteria {
        +String destination
        +Date date
        +int passengers
    }
    class FlightComparisonModule {
        +list<Flight> results
        +comparePrices()
    }
    FlightComparisonModule --> Flight : manages
    FlightComparisonModule ..> SearchCriteria : uses
