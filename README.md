# IVApi
This api is used to service a kubernetes cluster on GCP. The api partitions work to each individual node. Previously, the api served as a side by side with the client in the same pod while scraping was taking place. This would reduce the need to create a separate proxy as pods have different ip addresses. 
