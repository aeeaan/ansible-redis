correcthorse.redis
=========

An ansible role for installing redis.

Role Variables
--------------

| Variable                              | Default                       | Notes                                         |
| :---                                  | :---                          | :---                                          |
| redis_bind_address			| 127.0.0.1			| 	  	       		    		|
| redis_port				| 6379				|						|
| redis_open_port			| false				|						|

Dependencies
------------

* correcthorse.common

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.redis }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
