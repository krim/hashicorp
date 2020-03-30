# How to execute:

1. Edit hosts to use your own servers:
2. Run the playbook to install `consult` + `nomad`
    ```bash
    ansible-playbook hashistack.yml
    ```
3. Run the `app`(default redis app which provided by `nomad init`)
    ```bash
    ansible-playbook apps.yml
    ```
