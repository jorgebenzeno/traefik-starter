Configurations

    Static configuration (https://docs.traefik.io/reference/static-configuration/overview/)
        3 ways to define it they're evaluated as named below)
            - In a config file
            - In the command-line arguments
            - As enviroments variables
         
    Dinamically Configurations
        File
            https://docs.traefik.io/reference/dynamic-configuration/file/
        Docker
            https://docs.traefik.io/reference/dynamic-configuration/docker/
        Consul
            https://docs.traefik.io/reference/dynamic-configuration/consul-catalog/


Providers 
    
    Configurations from Providers (https://docs.traefik.io/providers/overview/)
        - Routers
        - Services
        - Middlewares
        - Certificates
     
    4 groups of Providers
        - Label based (Docker)
        - Key-Value based (Consul Catalog)
        - Annotation based
        - File based (Manual - YAML/TOML format)
    
    In some case providers might undergo a sudden burst of changes, which would generate a lot of configuration change events.
        In order to mitigate that, the providers.providersThrottleDuration option can be set
    
    Disabled traefik services discovery
        traefik.enable
    
Port Detection
    
    https://docs.traefik.io/providers/docker/#port-detection

