# Solution

primary id: license_key_id
iso date format e.g: 2020-07-01
or dateteime format: 2020-07-01T00:00:00-04:00

## Headers: 
* "Idempotency-Key": "93a7d7c4-8119-4997-9a0e-ad479d2b01c7"
* "Content-Type": "application/json; charset=utf-8"
                  
 
## Do we need previous license body?
We can support it - just pass body parameter on renew. Isv must check it correctness.
Or we can send previous "Idempotency-Key", if it was successfully processed. 
## Use date or datetime?
