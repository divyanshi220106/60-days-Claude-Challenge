# Day 3 – Role-Based Prompting

## Objective

Learn how Role-Based Prompting improves AI-generated responses by assigning different personas before asking the same question.

---

## What is Role-Based Prompting?

Role-Based Prompting is a prompt engineering technique where you assign a specific role, profession, or expertise to an AI model before asking a question.

Instead of asking:

> How can I build an AI-powered Student Attendance System?

You can ask:

> You are a Startup Founder. How can I build an AI-powered Student Attendance System?

or

> You are a Senior Software Engineer. How can I build an AI-powered Student Attendance System?

This provides more focused and context-aware responses.

---

## Experiment Performed

### Question Used

How can I build an AI-powered Student Attendance System?

---

## 1. Without Role Prompt

### Prompt

```text
How can I build an AI-powered Student Attendance System?
```

### Output Summary

* Collect attendance data
* Create a database
* Build a web application
* Train an AI model
* Deploy the solution

### Observation

The answer was generic and lacked domain-specific insights.

---

## 2. Founder Role Prompt

### Prompt

```text
You are a startup founder.

How can I build an AI-powered Student Attendance System?
```

### Output Focus

* Market validation
* Customer pain points
* MVP strategy
* Revenue opportunities
* Product growth

### Observation

The response focused on business viability, monetization, and customer needs.

---

## 3. Developer Role Prompt

### Prompt

```text
You are a Senior Software Engineer.

How can I build an AI-powered Student Attendance System?
```

### Output Focus

* Face recognition
* OpenCV
* TensorFlow
* Backend APIs
* Database design
* Deployment architecture

### Observation

The response focused on technical implementation and system architecture.

---

## Response Comparison

| Aspect                  | No Role | Founder | Developer |
| ----------------------- | ------- | ------- | --------- |
| Business Perspective    | ❌       | ✅       | ❌         |
| Revenue Strategy        | ❌       | ✅       | ❌         |
| Technical Details       | ❌       | ❌       | ✅         |
| Architecture Design     | ❌       | ❌       | ✅         |
| Market Validation       | ❌       | ✅       | ❌         |
| Implementation Guidance | Basic   | Medium  | High      |

---

## Claude Usage Counter

### Activities Performed

* Installed Claude Usage Counter
* Explored dashboard interface
* Viewed message statistics
* Monitored token usage
* Understood usage tracking features

### Learning

The extension helps monitor Claude usage limits and provides insights into message and token consumption.

---

## Screenshots

Store screenshots inside:

```text
Day3/screenshots/
```

Example:

```text
screenshots/
├── no_role_prompt.png
├── founder_prompt.png
├── developer_prompt.png
└── usage_counter.png
```

---

## Key Learnings

* Different roles produce different perspectives.
* AI performs better when given clear context.
* Role-Based Prompting improves response quality.
* The same question can generate business-focused or technical-focused answers depending on the assigned role.

---

## Conclusion

Role-Based Prompting is a simple yet powerful prompt engineering technique that improves AI outputs by providing context and expertise.

### Formula

```text
Role-Based Prompting = Better Context = Better Responses
```

### Examples of Useful Roles

* Founder
* Product Manager
* Software Engineer
* Researcher
* Marketing Expert
* Data Scientist

---

## Repository Structure

```text
Day3/
│
├── README.md
├── day3.md
└── screenshots/
    ├── no_role_prompt.png
    ├── founder_prompt.png
    ├── developer_prompt.png
    └── usage_counter.png
```

---

## Author

**Anil Bajpai**

Day 3 of the #60DaysOfClaudeChallenge by ABTalks
