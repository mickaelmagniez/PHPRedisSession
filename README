Overview
--------
The PHPRedisSession provides simple class to store your PHP Sessions in Redis.


Notes
-----
-  Depends on Predis http://github.com/nrk/predis/
-  Remarks and ideas are welcomed.

Default Usage 
-------------
    require_once 'RedisSession.class.php';
    
    RedisSession::init ( array ( 
            'session_name' => 'redis_session', 
            'cookie_path' => '/', 
            'cookie_domain' => '.acme.org', 
            'lifetime' => 3600, 
            'server' => array ( 
                    'host' => 'redis.acme.org', 
                    'port' => 6379 ) ) );


