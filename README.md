# LearnTrace

### An AI-Driven Knowledge Graph and Knowledge Tracing Framework for Skill Gap Detection and Personalized Learning

LearnTrace is a personalized learning platform that helps students understand their current skill level, identify knowledge gaps, and follow a learning path based on their needs.

Instead of only showing quiz scores, LearnTrace connects assessments, skills, learning history, practice, and skill relationships to build a better picture of what a learner knows.

---

## What Problem Does It Solve?

Most learning platforms tell students what they got wrong, but they do not always explain why they are struggling or what they should learn next.

LearnTrace focuses on:

- Finding skill gaps
- Understanding relationships between skills
- Estimating skill mastery
- Recommending what to learn next
- Tracking progress over time

---

## How LearnTrace Works

```mermaid
flowchart TD
    A[Learner] --> B[Select Learning Goal]
    B --> C[Assessment]
    C --> D[Analyze Performance]
    D --> E[Estimate Skill Mastery]
    E --> F[Knowledge Graph]
    F --> G[Find Skill Gaps]
    G --> H[Personalized Roadmap]
    H --> I[Learn and Practice]
    I --> J[Reassessment]
    J --> E