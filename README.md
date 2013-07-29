Custom configuration tree for nginx (/etc/nginx).
/etc/nginx/
          |_conf.d  ( server configurations - log_format, gzip, ssl...etc )
          |_inc     ( sites configuratoins )
          |_pki     ( certificates )
          |_sides.d ( default site and static example )

Beter structured and use a lot of includes.
Example of static site added.

Default website and example com root directories:
/srv/www/
        |_default
        |_static.example.com
