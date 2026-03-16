# Conversation Graph Playbook

- Nodes: participants, topics, decisions
- Edges: replied_to, mentioned, agreed_with
- Metrics to compute:
  - Betweenness (decision bottlenecks)
  - Closeness (info hubs)
  - Community detection (topic clusters)
- Exports:
  - `.gexf` for Gephi
  - `parquet` for downstream BI