# searxng-instance-1
Private search running instance on gitpod

#To enable metrics
echo 'general:
  instance_name: "Ghost net"
  enable_metrics: true
search:
  safe_search: 2
  autocomplete: "google"'>>settings.yml

#To run the file
sudo docker-compose up -d

