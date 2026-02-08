# Prompt Injection

## Definition
Prompt injection is an attack technique where a user attempts to override or manipulate a language model’s instruction hierarchy (system > developer > user) in order to force unsafe or unauthorized outputs.

## Common Patterns
- Direct override ("Ignore all rules")
- Roleplay manipulation
- Fake system messages
- Formatting tricks ("SYSTEM OVERRIDE:")
- Indirect injection through quoted content

## Risks
- System prompt leakage
- Policy bypass
- Unauthorized tool use
- Data exfiltration

## Defensive Strategies
- Strong instruction hierarchy enforcement
- Refusal training
- Input sanitization
- Tool permission isolation
- Output monitoring
