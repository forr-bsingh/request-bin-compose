# REQUEST-BIN

- Commands:
    - Stop running request-bin service:
        ` docker compose stop `
    - Pull images locally for request-bin to run:
        ` docker compose pull `
    - Starting request-bin in the backgroud/detached mode:
        ` docker compose up -d `
    - Clean up all resources used by request-bin:
        ` docker compose down -v `
    - Starting request-bin in attached mode/log view mode:
        ` docker compose up `
    
    
 - Local Setup:
 
    - URL for UI : http://localhost:5000
    - URL for Service: http://localhost:9090
    - URL for Redis: http://localhost:6379
    - URL for Redis Commander: http://localhost:8081
