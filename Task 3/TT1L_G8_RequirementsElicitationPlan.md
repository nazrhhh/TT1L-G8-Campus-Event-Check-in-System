# Requirements Elicitation Plan

## 1. Introduction to the Kano Model Approach

The Kano Model is a theory for product development and customer satisfaction that categorizes requirements based on how they influence stakeholder satisfaction. For our Campus Event Check-in System, this model helps us distinguish:

* **Basic/Threshold/Must-be Attributes (Dissatisfiers)**: Essential requirements that cause dissatisfaction if missing.
* **Performance/One-dimensional Attributes (Satisfiers)**: Directly impact user satisfaction in proportion to implementation quality.
* **Excitement/Attractive Attributes (Delighters)**: Unexpected features that increase satisfaction when present but are not expected.

The system serves three main user roles—Students, Event Organizers, and University Admins—and integrates with existing student identification and payment processing systems.

Given the variety of stakeholder roles and expectations, the Kano Model ensures we meet basic system expectations while also identifying high-impact improvements. Each requirement gathered is systematically categorized under the Kano Model to prioritize stakeholder needs, ensuring that the system addresses foundational expectations while identifying high-impact features that delight users.

## 2. Justification for Selected Elicitation Techniques

This elicitation plan focuses on four carefully selected techniques: questionnaires, brainstorming, observation, and perspective-based reading. These were chosen based on their suitability for the project's goals and the accessibility of our stakeholders.

* **Questionnaires**: These are distributed to students, event organizers, and university admins. They are effective for capturing structured, large-scale feedback quickly. Predefined questions ensure clarity and standardization, making it easier to analyze patterns and prioritize features within the Kano model.

* **Brainstorming**: Conducted within the team and optionally with select stakeholders, this method encourages open-ended idea generation for delighter features. It helps uncover innovative functionalities that may not emerge through structured questions.

* **Observation**: Direct observation of current event check-in processes helps identify pain points and opportunities for improvement. By watching how students, event organizers, and administrators interact with existing systems, we can identify unstated needs that stakeholders may not articulate through questionnaires.

* **Perspective-Based Reading**: This technique involves examining requirements from different stakeholder perspectives (students, event organizers, administrators). Each team member adopts a specific stakeholder role and reviews potential requirements from that perspective, helping to ensure comprehensive coverage of needs across all user types.

Together, these four methods provide a balanced combination of structured data, creative input, and contextual understanding, enabling comprehensive requirement elicitation aligned with the Kano classification.

## 3. Sample Stakeholder Questionnaire

**Students:**

1. How often do you participate in campus events?
2. What methods do you currently use to register for events?
3. Would you prefer a digital check-in using your Student ID or QR code?
4. What types of payment methods do you use/prefer (e-wallet, card, bank transfer)?
5. Would receiving automated reminders or confirmations improve your event experience?

**Event Organizers:**

6. What difficulties have you experienced with event check-ins or payments in the past?
7. What features would make the system easier or more engaging for you?
8. Would you find a dashboard for tracking attendance and participation useful?
9. What are your requirements for generating reports after events?
10. How would you prefer to manage event creation and approval workflows?

**University Admins:**

11. What are your privacy or data concerns using a centralized check-in system?
12. What system-wide analytics would be most valuable for university planning?
13. What integration requirements do you have with existing university systems?
14. What security protocols must be implemented for student data protection?
15. What additional feedback would you like to share about your expectations?

## 4. Kano Classification of Requirements

| **Requirement Description** | **Kano Category** | **Stakeholder Source** |
|----------------------------|-------------------|------------------------|
| Secure Student ID login and identity verification | Dissatisfier | Students, IT Dept, Admins |
| QR code scanning for quick check-in | Satisfier | Students, Event Organizers |
| Integration with e-wallet and bank payment systems | Dissatisfier | Students, Finance Dept, Admins |
| Attendance tracking dashboard for organizers | Satisfier | Event Organizers, Admins |
| Event creation and approval workflow | Dissatisfier | Event Organizers, Admins |
| Real-time notifications for registration/payment success | Satisfier | Students, Event Organizers, Admins |
| Loyalty points system for event attendance | Delighter | Students, Event Organizers |
| Automated reminders synced with calendar apps | Delighter | Students, Event Organizers |
| Rating system or feedback option post-event | Delighter | Students, Event Organizers, Admins |
| Role-based access control for system users | Dissatisfier | IT Dept, Admins, Event Organizers |
| System-wide analytics and reporting tools | Satisfier | Event Organizers, Admins |

The above Kano classification includes a clear linkage to the source technique used to gather each requirement. This mapping ensures that each elicited requirement is backed by the most suitable method based on the stakeholder's role and the nature of the information required.
