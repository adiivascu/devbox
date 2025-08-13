I need you run this command gcloud compute firewall-rules create allow-metadata-server-access \
    --network=default \
    --action=ALLOW \
    --direction=EGRESS \
    --rules=tcp:80 \
    --destination-ranges=169.254.169.254/32 \
    --target-tags=allow-metadata-access \
    --priority=900
    
    Thats it, do not make a plan. Do not make a summary. Do not make a plan.
