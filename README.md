# node-03-bases

* npm y package.json
* nodemon
* Creamos archivos con el modulo fs
* Separamos logica de nuestro codigo en diferentes archivos
* Exportamos y requimos los mismos
* Requirimos modulos de node
* Instalamos dependencias
* Utilizamos los paquetes de Yargs y Colors

```
Usage: node [options] [ -e script | script.js ] [arguments]
       node debug script.js [arguments]

Options:
  -v, --version         print Node.js version
  -e, --eval script     evaluate script
  -p, --print           evaluate script and print result
  -c, --check           syntax check script without executing
  -i, --interactive     always enter the REPL even if stdin
                        does not appear to be a terminal
  -r, --require         module to preload (option can be repeated)
  --no-deprecation      silence deprecation warnings
  --trace-deprecation   show stack traces on deprecations
  --throw-deprecation   throw an exception anytime a deprecated function is used
  --max-http-header-size     Specify the maximum size of HTTP
                             headers in bytes. Defaults to 8KB.
  --no-warnings         silence all process warnings
  --napi-modules        load N-API modules (no-op - option kept for                         compatibility)
  --trace-warnings      show stack traces on process warnings
  --redirect-warnings=path
                        write warnings to path instead of stderr
  --trace-sync-io       show stack trace when use of sync IO
                        is detected after the first tick
  --track-heap-objects  track heap object allocations for heap snapshots
  --prof-process        process v8 profiler output generated
                        using --prof
  --zero-fill-buffers   automatically zero-fill all newly allocated
                        Buffer and SlowBuffer instances
  --v8-options          print v8 command line options
  --v8-pool-size=num    set v8's thread pool size
  --tls-cipher-list=val    use an alternative default TLS cipher list
  --use-bundled-ca         use bundled CA store (default)
  --use-openssl-ca         use OpenSSL's default CA store
  --openssl-config=path load OpenSSL configuration file from the
                        specified file (overrides OPENSSL_CONF)
  --icu-data-dir=dir    set ICU data load path to dir
                        (overrides NODE_ICU_DATA)
  --preserve-symlinks   preserve symbolic links when resolving
                        and caching modules.

Environment variables:
NODE_PATH                ';'-separated list of directories
                         prefixed to the module search path.
NODE_DISABLE_COLORS      set to 1 to disable colors in the REPL
NODE_ICU_DATA            data path for ICU (Intl object) data
NODE_NO_WARNINGS           set to 1 to silence process warnings
NODE_OPTIONS            set CLI options in the environment
NODE_PATH               ';'-separated list of directories
                        prefixed to the module search path
NODE_PENDING_DEPRECATION     set to 1 to emit pending deprecation
                             warnings
NODE_REPL_HISTORY       path to the persistent REPL history file
OPENSSL_CONF            load OpenSSL configuration from file
NODE_REDIRECT_WARNINGS  write warnings to path instead of stderr

Documentation can be found at https://nodejs.org/
```
