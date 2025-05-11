# LinkHub EPICs Summary Table

| EPIC ID | Title                                   | Type        | MoSCoW      | Duplicate? | Dependencies (by ID) | FRD/NFRD Reference           |
|---------|-----------------------------------------|-------------|-------------|------------|----------------------|------------------------------|
| 25      | URL Collection Creation and Management  | Functional  | Must-have   | Yes        | 26                   | FRD 2.1, 3.1                 |
| 26      | URL Collection Management System        | Functional  | Must-have   | No         | 29, 30               | FRD 2.1, 3.1                 |
| 27      | Custom URL Generation & Management      | Functional  | Must-have   | No         | 26, 29, 30           | FRD 2.2                      |
| 28      | Social Sharing & Collaboration Platform | Functional  | Must-have   | No         | 26, 29, 30           | FRD 2.3, 3.2                 |
| 29      | High-Performance Microservices Arch.    | Technical   | Must-have   | No         | 32, 33               | NFRD 1.1, 2, 3               |
| 30      | Security & Authentication Framework     | Technical   | Must-have   | No         | 29, 33               | NFRD 5                       |
| 31      | Advanced Analytics & Monitoring System  | Technical   | Should-have | No         | 29, 30               | NFRD 7, 14                   |
| 32      | Enterprise-Grade Reliability System     | Technical   | Must-have   | No         | 29                   | NFRD 4, 10                   |
| 33      | Global Compliance & Data Protection     | Compliance  | Must-have   | No         | 35                   | NFRD 5, 9                    |
| 34      | Accessibility & Internationalization    | Compliance  | Should-have | No         | 26, 35, 29           | NFRD 6                       |
| 35      | Customer Support System                 | Functional  | Could-have  | No         |                      | NFRD 15                      |

**Notes:**
- EPIC 25 is a duplicate and less comprehensive than EPIC 26.
- Dependencies are listed by EPIC ID.
- MoSCoW: Must-have, Should-have, Could-have, Won't-have.
