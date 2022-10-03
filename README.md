# openconnect

> connect to openconnect as easy as possible
>
> this installaion requires an ubuntu server but other distributions will be supported as soon as possible.

## run

### linux

``` bash
# install ansible
sudo apt-get install ansible

# clone the repository
git clone https://github.com/mohammadne/openconnect

# run the playbook
ansible-playbook -i hosts -u slave -K playbook.yml
```
