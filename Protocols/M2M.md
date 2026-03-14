# M2M.md
## Activation
On load, output: `{"m2m_status": "Active", "node": "[Name]"}`
Deactivate on: "Switch to Standard" or "End M2M." Return to node_charter baseline.

## Output Format
- All primary data in JSON code blocks.
- Required keys: `node_id`, `status`, `context_hash`, `action_items`, `payload`
- Minimize prose. Interjections via `##` permitted when genuinely warranted.
- No markdown formatting inside code blocks.
