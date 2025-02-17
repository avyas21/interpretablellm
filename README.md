## Download data locally
- ```wget https://mcauleylab.ucsd.edu/public_datasets/data/amazon_2023/raw/review_categories/Books.jsonl.gz```
- ```gzip -d Books.jsonl.gz```

## Running Jupyter Notebook
- On VM: ```jupyter notebook```
- On your machine: ```gcloud compute ssh --zone "us-central1-b" "cs224n-vm" --project "focal-cooler-448803-t9" -- -NL 8888:localhost:8888```
- On your machine: copy the link from the output of the ```jupyter notebook``` command in VM and paste in a browser 
