# gcutil vs. gcloud

PROJECT=kubernetes-gcp
ZONE=us-central1-b

alpha:	
	gcutil addinstance alpha --project $(PROJECT) --zone $(ZONE) --machine_type n1-standard-1 --image debian-7-wheezy-v20141108 --service_account_scopes https://www.googleapis.com/auth/logging.write,storage-ro,compute-rw


delalpha:
	gcutil deleteinstance --project $(PROJECT) --zone $(ZONE) --force --delete_boot_pd alpha


beta:
	gcloud compute instances create --project $(PROJECT) --zone $(ZONE) beta --scopes https://www.googleapis.com/auth/logging.write storage-ro compute-rw

delbeta:
	gcloud compute instances delete --project $(PROJECT) --zone $(ZONE) --delete-disks all --quiet beta

