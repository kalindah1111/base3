# base3
Analyzing Daily Transaction Growth on Base Using On-Chain Data  Base frequently leads the L2 ecosystem by daily active users.
import requests
import json

API_KEY = "YOUR_KEY"
query_id = "YOUR_DUNE_QUERY_ID"

resp = requests.post(
    f"https://api.dune.com/api/v1/query/{query_id}/execute",
    headers={"X-Dune-API-Key": API_KEY}
)

print(resp.json())
What growth trends do you observe?
