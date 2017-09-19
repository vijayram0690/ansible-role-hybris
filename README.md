    Ansible Role For Hybris
    =======================
    提供了如下按顺序ansible task的tags，可选择执行来完成Hybris部署过程中的可持续集成：
    ###### 1. install
    `Hybris与Jrebel的安装与部署，数据库驱动下载`


    Requirements
    ------------
    各个模块需要的linux软件依赖如下：

    ###### 1. install
    `unzip`


    Role Variables
    --------------

    A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

    Dependencies
    ------------

    A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

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

    An optional section for the role authors to include contact information, or a website (HTML is not allowed).