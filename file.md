
```
gcloud config set project drabhishekt3
```
```
git clone https://github.com/abhirocksadek-cmd/mcp.git
```
#adk web --allow_origins='*'


```
# Run the deployment command
uvx --from google-adk==1.14.0 \
adk deploy cloud_run \
  --project=$PROJECT_ID \
  --region=europe-west1 \
  --service_name=travelo \
  --with_ui \
  . \
  -- \
  --labels=ddr-tutorial=codelab-adk \
  --service-account=$SERVICE_ACCOUNT
```

