# System Design Prompts

## Prompt Template
The below is a prompt template used while designing software architecture:

```
Act as a senior software architect with expertise in [technologies].
Design a system for [application purpose] that needs to [requirements].

The system should include:
- [Component 1]
- [Component 2]
- [Component n]

Consider these constraints:
- [Constraint 1]
- [Constraint 2]

For each component, explain:
1. Its purpose
2. Key technologies
3. Interactions with other components
4. Potential challenges
```

## Example
```
Act as a senior software architect with expertise in microservices and cloud architecture.
Design a system for an e-commerce platform that needs to handle 10,000 concurrent users.

The system should include:
- User authentication service
- Product catalog service
- Order processing service
- Payment processing service
- Inventory management service

Consider these constraints:
- Must be deployable on AWS
- Must have high availability (99.9%)
- Must comply with PCI DSS for payment processing

For each component, explain:
1. Its purpose
2. Key technologies
3. Interactions with other components
4. Potential challenges
```