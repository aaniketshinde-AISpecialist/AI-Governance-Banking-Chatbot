Risk	Existing Controls	Residual Risk	Residual Risk Rating
PII leakage to LLM provider	PII Redaction Filter + outbound payload inspection	Obfuscated or previously unseen sensitive data patterns may bypass detection mechanisms	Medium
AI hallucination in responses	API-grounded response architecture	LLM may still generate misleading narrative language around correct figures	Medium
Excess PII retained in logs	Automated retention enforcement	Legacy logs or failed deletion jobs may persist until detected through monitoring or audit activities	Low
Regulated query handled without human review	Hardcoded escalation rules	Edge-case queries may fall outside predefined escalation logic or classification thresholds	Medium
