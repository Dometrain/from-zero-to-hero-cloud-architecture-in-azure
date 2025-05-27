# Design Principles

## Scalability
- Prefer horizontal scaling over vertical scaling 
- Strive for independent scaling on own resource demands
- Decouple components
- Create stateless services

## Reliability
- Design for failure
- Graceful degradation
- Decouple components

## Cost
- Pay for consumption, not capacity (pay-as-you-go)
- Don't introduce components that you do not really need

## Security 
- Defense in depth 
- Principle of least privilige

## Overall
- Prefer asynchronous processing for resource-heavy tasks