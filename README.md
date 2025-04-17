# Netdata Demo Project
## Objectives
### To monitor system resources and their usage via Netdata
## Tools used
### Docker
### Netdata
## Procedure
### Run a docker container containing Netdata by pulling its image from dockerhub.
### docker run -d --name=netdata -p 19999:19999 netdata/netdata
<img width="778" alt="pulling img" src="https://github.com/user-attachments/assets/59a264fc-bebc-494a-9c99-553986844da7" />
### Visit localhost:19999 to monitor the container and its resources using netdata

### Metrics

<img width="1277" alt="metric" src="https://github.com/user-attachments/assets/314d6153-5e95-46c0-9aa3-e7a8414c91a1" />

### Alerts

<img width="1280" alt="alerts" src="https://github.com/user-attachments/assets/4ea738f1-9032-4b39-bbdc-348678bc0692" />

### Nodes

<img width="1276" alt="nodes" src="https://github.com/user-attachments/assets/97c4ecb7-32d9-4c83-822b-f9a193f02b7c" />
