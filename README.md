# cloud-functions

How to run:

```
gcloud functions deploy go-http-function \                                        
--gen2 \
--runtime=go120 \
--region=us-central1 \
--source=. \
--entry-point=HelloGet \
--trigger-http \
--allow-unauthenticated
```