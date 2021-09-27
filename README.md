# nsdiff
Bash script to compare a BIND .zone file with DNS queried from the internet

~~~
Usage: nsdiff [-s server] [-v] [-r] zonefile
        Compare the zone file with the DNS lookup.
        -s server       DNS will look up through that server.
                        or use @server.
        -r              always show the results returned.
        -v              verbose output
~~~
