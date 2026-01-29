SOLID principles (By Robert C. Martin in 2000):
- S: Single Responsibility Principle
  - A class should have only one reason to change, meaning it should only have one job
- O: Open-Closed Principle
  - Software entities should be open for extension but closed for modification
  - = A class should be extendable without modifying existing code
- L: Liskov Substitution Principle = A subtype must be substitutable for its supertype
  - The subtype can only accept identical or wider ARGUMENTS
  - The subtype can only RETURN identical or narrower types
  - The subtype can only throw fewer or narrower EXCEPTIONS
  - The subtype methods must maintain or strengthen the supertype's INVARIANTS
  - The subtype shouldn't allow STATE CHANGES that the base class doesn't allow
  - The subtype can weaken (but not strengthen) any PRECONDITION for a method it overrides
- I: Interface Segregation Principle
  - Classes should not be forced to implement interfaces that they don't use
  - Large interfaces should be broken down into smaller interfaces
- D: Dependency Inversion Principle
  - Higher level modules should not rely on lower level modules

