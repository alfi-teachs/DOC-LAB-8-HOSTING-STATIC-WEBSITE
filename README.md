# DOC-LAB-8-HOSTING-STATIC-WEBSITE
# Step 1: Clone GitHub Repository

```bash
git clone https://github.com/alfi-teachs/DOC-LAB-8-HOSTING-STATIC-WEBSITE.git
```
# Step 2: Go Inside Project Folder
```bash
cd DOC-LAB-8-HOSTING-STATIC-WEBSITE
```
# Step 3: Build Docker Image
```bash
docker build -t gym .
```
# Step 5: Run Docker Container
```bash
docker run -d -p 2000:80 --name gym-container gym
```
