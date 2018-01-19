sa-logstash
===========
[![Build Status](https://travis-ci.org/softasap/sa-logstash.svg?branch=master)](https://travis-ci.org/softasap/sa-logstash)

Installs Logstash, an open source, server-side data processing pipeline that ingests data from a multitude of sources simultaneously, transforms it, and then sends it to your favorite “stash.”

Example of usage:

Simple

```YAML

vars:

roles:
     - {
         role: "sa-logstash"
       }


```

Advanced

see box-example for full featured lamp install.

```YAML

vars:

roles:
     - {
         role: "sa-logstash"
       }


```


Usage with ansible galaxy workflow
----------------------------------

If you installed the `sa-logstash` role using the command


`
   ansible-galaxy install softasap.sa-logstash
`

the role will be available in the folder `library/softasap.sa-logstash`
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-logstash"
       }

```




Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html
