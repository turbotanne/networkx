# Moderator Alerts

Pseudo:
```python
if graph.degree(node) > DEGREE_THRESHOLD and sentiment < -0.4:
    send_alert(node, conversation_id)
```

- Combine betweenness + negative sentiment to spot tension clusters.
- Send Slack DM with top quote + speaker context.