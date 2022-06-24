add /etc/mysql/my.cnf
```
[mysqld]
innodb_buffer_pool_size=10M
```
 sample error log /var/log/mysql/error.log
 ```2022-06-24T14:53:46.223397Z 0 [Warning] TIMESTAMP with implicit DEFAULT value is deprecated. Please use --explicit_defaults_for_timestamp server option (see documentation for more details).
2022-06-24T14:53:46.225003Z 0 [Note] /usr/sbin/mysqld (mysqld 5.7.38-0ubuntu0.18.04.1) starting as process 9372 ...
2022-06-24T14:53:46.228723Z 0 [Note] InnoDB: PUNCH HOLE support available
2022-06-24T14:53:46.228742Z 0 [Note] InnoDB: Mutexes and rw_locks use GCC atomic builtins
2022-06-24T14:53:46.228746Z 0 [Note] InnoDB: Uses event mutexes
2022-06-24T14:53:46.228750Z 0 [Note] InnoDB: GCC builtin __atomic_thread_fence() is used for memory barrier
2022-06-24T14:53:46.228753Z 0 [Note] InnoDB: Compressed tables use zlib 1.2.11
2022-06-24T14:53:46.228756Z 0 [Note] InnoDB: Using Linux native AIO
2022-06-24T14:53:46.228966Z 0 [Note] InnoDB: Number of pools: 1
2022-06-24T14:53:46.229059Z 0 [Note] InnoDB: Using CPU crc32 instructions
2022-06-24T14:53:46.232056Z 0 [Note] InnoDB: Initializing buffer pool, total size = 128M, instances = 1, chunk size = 128M
2022-06-24T14:53:46.232086Z 0 [ERROR] InnoDB: mmap(137428992 bytes) failed; errno 12
2022-06-24T14:53:46.232093Z 0 [ERROR] InnoDB: Cannot allocate memory for the buffer pool
2022-06-24T14:53:46.232098Z 0 [ERROR] InnoDB: Plugin initialization aborted with error Generic error
2022-06-24T14:53:46.232102Z 0 [ERROR] Plugin 'InnoDB' init function returned error.
2022-06-24T14:53:46.232105Z 0 [ERROR] Plugin 'InnoDB' registration as a STORAGE ENGINE failed.
2022-06-24T14:53:46.232109Z 0 [ERROR] Failed to initialize builtin plugins.
2022-06-24T14:53:46.232111Z 0 [ERROR] Aborting

2022-06-24T14:53:46.236321Z 0 [Note] Binlog end
2022-06-24T14:53:46.236375Z 0 [Note] Shutting down plugin 'CSV'
2022-06-24T14:53:46.236690Z 0 [Note] /usr/sbin/mysqld: Shutdown complete```
