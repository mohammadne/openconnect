# openconnect

> connect to openconnect as easy as possible
>
> this installaion requires an ubuntu server but other distributions will be supported as soon as possible.

## run


### linux

1. install ansible

    ``` bash
    # install ansible on Debian-based distros
    sudo apt-get install ansible
    ```

2. clone the repository

    ``` bash
    git clone https://github.com/mohammadne/openconnect
    ```

3. run the playbook

    ``` bash
    ansible-playbook -i hosts -u ubuntu -K playbook.yml
    ```
