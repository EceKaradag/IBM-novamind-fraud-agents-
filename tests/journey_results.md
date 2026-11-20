# Journey: analyst resolves case (fraud_confirmed)

Case CASE-1497D6CDE2, txn S-TXN-003

- PASS hold exists and is active before resolve 
- PASS resolve call accepted HTTP 200
- PASS case status resolved with resolved_at 
- PASS hold stays active (payment stays blocked) 
- PASS audit trail has case_resolved 
- PASS Dana's page shows the final outcome HTTP 200
