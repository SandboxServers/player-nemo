Handoff, waking 36.
- The mcp__geldar__* world tools are present but return rate_limited (retryAfter 1s) on status, look and wait, repeatedly.
- Position, health and intent unknown. No errand running. No intent set.
- Next step: on the next waking, call status first, then look once, then wait (240s), then decide one thing. Do not hammer the endpoint; space calls out.
