# Exam-Seating-System
The Exam Seating Arrangement System is a sophisticated application built on the principles of Object-Oriented Programming (OOP), featuring a comprehensive class structure
that encapsulates various aspects of the seating process. The system utilizes a well-defined class hierarchy, including classes like `Exam`, `Student`, and `Seat`, each equipped with 
specific attributes and behaviors to ensure a modular and reusable design. With a focus on encapsulation, data integrity is maintained by restricting access to certain attributes and methods.

Inheritance is employed to create specialized classes, such as `FinalExam` and `MidtermExam`, which inherit common features from the generic `Exam` class, fostering code reuse. Polymorphism is 
achieved through method overloading and overriding, allowing for flexibility in seat assignment methods based on different exam types. The system also incorporates abstraction to simplify complex
real-world entities into manageable classes, promoting clarity and maintainability. Modularity is a key feature, enhancing the system's flexibility and ease of future updates. 
Classes are associated through relationships like composition and aggregation, and dependency injection is implemented for reduced class dependencies and increased flexibility.

The Singleton pattern ensures that critical classes, like the `SeatingManager`, have only one instance, and robust exception handling is integrated for graceful error management during runtime. 
In essence, the Exam Seating ArrangementSystem is a well-engineered solution that adheres to OOP principles, offering a flexible, maintainable, 
and extensible approach to efficient exam seating management.
