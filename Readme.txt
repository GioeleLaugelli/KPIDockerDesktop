
Aprire CMD e modificare i seguenti setting:
    wsl -d docker-desktop
    sysctl -w vm.max_map_count=262144
dopodichè andare nella folder dove è presente il docker-compose e lanciare il seguente comando:
    docker compose up
Le utenze possono essere trovate nel file .env
Per l'utenza di Jenkins verrà promptata una password in fase di installazione
