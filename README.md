# Terraform Course

## Installation

    ### Docker

    Start Container

    ```bash
    docker run -it --rm --name terraform-basic ubuntu:22.04 bash
    ```

    install terraform

    ```bash
    apt-get update \
    && apt-get upgrade -y
    && apt-get install -y \
    curl wget ca-certificates apt-transport-https jq \
    software-properties-common git \
    && wget -O- https://apt.releases.hashicorp.com/gpg | gpg --dearmor | tee /usr/share/keyrings/hashicorp-archive-keyring.gpg \
    && echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] \
    https://apt.releases.hashicorp.com $(lsb_release -cs) main" | tee /etc/apt/sources.list.d/hashicorp.list \
    && apt-get update \
    && apt-get install terraform
    ```
