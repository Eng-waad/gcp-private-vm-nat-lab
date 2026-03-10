# Commands Used in the Lab

## SSH to VM using IAP

gcloud compute ssh vm-internal –zone ZONE –tunnel-through-iap

## Create environment variable for bucket

export MY_BUCKET=your-bucket-name

## Copy file to bucket

gcloud storage cp gs://cloud-training/gcpnet/private/access.svg gs://$MY_BUCKET

## Copy file from bucket

gcloud storage cp gs://$MY_BUCKET/*.svg .

## Update packages

sudo apt-get update
