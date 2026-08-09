# Maker guardrails (short version)

I keep this short so people read it.

## Environment

If your org has a dev/test/prod setup, don’t ship the important stuff only from Default. I’ve seen production flows trapped there with no clear owner.

## DLP

Check connectors before you promise a delivery date. A blocked connector on Friday afternoon is an avoidable failure.

## License

Premium connector or AI Builder capacity is a conversation with the platform owner *before* the demo to the VP.

## Defaults I ask for on anything “real”

1. Named owner and a backup  
2. A failure path that notifies someone  
3. No keys sitting in a Compose step  
4. Data in a list or Dataverse — not one person’s desktop Excel  
5. Ten lines on what the happy path is  

## Stop and escalate

Restricted data, posting into finance/HR systems of record, or anything that needs true 24/7 support. Citizen development isn’t a workaround for those.
