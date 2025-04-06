# SMB DNS Filter
Blocks phishing/malware sites in 5 minutes.

## Deploy
1. **Cloud**: Run `aws lightsail create-instances --user-data-file deploy/cloud-init.yml`
2. **Local**: `docker-compose -f deploy/docker-compose.yml up -d`
