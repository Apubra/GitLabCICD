# GitLabCICD

sudo curl -L --output /usr/local/bin/gitlab-runner "https://gitlab-runner-downloads.s3.amazonaws.com/latest/binaries/gitlab-runner-linux-amd64"

sudo chmod +x /usr/local/bin/gitlab-runner

sudo gitlab-runner install --user=gitlab-runner --working-directory=/home/gitlab-runner
sudo gitlab-runner start

If need stop or restart runner:
sudo gitlab-runner stop
sudo gitlab-runner start

# Registering runners
sudo gitlab-runner register

Note: Use shell if you want to run the command instead of docker.

You can run multiple repo in single VM using one runner. Just register the new one.
