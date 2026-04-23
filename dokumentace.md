17.3. instalace void linux na server intel nuc (oznacen SPARE O2), vytvoreni partitions na disku,  omylem nakofigurovany cesky jazyk


19.3. nastaveni ssh, pristup pomoci klicu, pokus o nastaveni mdns (z neznameho duvodu nefunguje)

16.4 Vytvorily jsme dockerfile, pri sudo docker run -d -p 8080:80 nas-nginx-docker dost8v8me error
docker: Error response from daemon: failed to set up container networking: driver failed programming external connectivity on endpoint vigilant_noether (71e35ccd1918bd08850e9008fbf169f876cfbf7feb7bdb85be4eb363851e4f4f): Unable to enable DNAT rule:  (iptables failed: iptables --wait -t nat -A DOCKER -p tcp -d 0/0 --dport 8080 -j DNAT --to-destination 172.17.0.2:80 ! -i docker0: iptables: No chain/target/match by that name.
23.4. Problém s IP tables se nepodařilo vyřešit, Dockerfile jsme zazálohovaly a přeinstalovaly systém na fedora linux
