| Field                | Required?       | Why?                          |
| -------------------- | --------------- | ----------------------------- |
| Incident Number      | Yes             | Unique identifier             |
| Caller               | Yes             | Employee identification       |
| Short Description    | Yes             | Quick summary                 |
| Description          | Yes             | AI analyzes this              |
| Category             | AI Prediction   | Hardware/Software/Network     |
| Subcategory          | AI Prediction   | More detailed classification  |
| Assignment Group     | AI Prediction   | Correct support team          |
| Impact               | Business Rules  | Business impact               |
| Urgency              | Business Rules  | Time sensitivity              |
| Priority             | Business Rules  | Derived from Impact + Urgency |
| Suggested Resolution | AI              | Recommended action            |
| State                | Workflow        | Tracks progress               |
| Resolution Notes     | Engineer/System | Final resolution              |