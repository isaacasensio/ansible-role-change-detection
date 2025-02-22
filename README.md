change-detection
==========

Installs change-detection as a docker container service.


Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):


```
change_detection_image: ghcr.io/dgtlmoon/changedetection.io
```
The version of the changedetection image to run as a container.

```
change_detection_host_config_path: /etc/change-detection
```
Host path where the changedetection configuration will be stored.

```
change_detection_host_data_path: /var/lib/change-detection
```
Host path where the changedetection data will be stored.

```
change_detection_container_user: change-detection
```
user who will run the container

```
change_detection_host_port: 5000
```
host port exposed


Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - iasensio.change-detection

License
-------

MIT

