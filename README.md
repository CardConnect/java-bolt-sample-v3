# Java Bolt Sample App V3

## Bolt v3 Desktop Client
To run, you need Java 1.8 installed:

`java -jar tokenmux-service-java-desktop-client-3.0.0-SNAPSHOT.jar`

Log output will end up in bolt.log in the current directory.

### Example client.properties:
```java
base.url = https://bolt-qa.cardpointe.com:6443/api/v3
api.key = aDlzqEdIK1EWFl6NqlEV2I1Iz0RghqRNdvFu19fWe2s=
merchant.id = 888888888880
hsn = TMCSCEMVSIG
connect.force = true
readcard.include.signature = true
readcard.amount.display = true
readcard.include.pin = true
readcard.beep = false
readcard.aid = credit
readmanual.include.signature = true
readmanual.expiration.date = true
readmanual.beep = false
authcard.include.signature = true
authcard.amount.display = true
authcard.beep = false
authcard.auth.merchant.id =
authcard.aid = credit
authcard.include.avs = true
authcard.include.pin = true
authcard.capture = true
authmanual.include.signature = true
authmanual.amount.display = true
authmanual.beep = false
authmanual.auth.merchant.id =
authmanual.include.avs = true
authmanual.include.cvv = true
authmanual.capture = true
```

See https://developer.cardconnect.com/bolt-p2pe for more details. 
