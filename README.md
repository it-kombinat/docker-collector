<p><img src="http://1000logos.net/wp-content/uploads/2017/07/Logo-Docker-500x394.jpg" alt="docker logo" title="docker" align="right" height="60" /></p>

Ansible-Role-SPL
=========

Deploy SPL as Docker Image

Requirements
------------

 - Ansible >= 2.4

Role Variables
--------------

container_name: splunk-demo
    docker_image: stackware/spl:1.7


| Name           | Default Value | Description                        |

| -------------- | ------------- | -----------------------------------|

| `container_name` | splunk-demo  | Name of the Container |

| `docker_image` | stackware/spl:1.8 | Docker Image (incl.tag) |

| `hec_token` | "token=abcd-efgh-123ada-0815" | HEC Token |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

## Author Information

You can find me on Twitter: [@itkombinat](https://twitter.com/itkombinat)
