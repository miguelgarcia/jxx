# jxx

Configure a custom values files and runs JX
All options after -- are passed directly to jx

Options:
--nginx-class=nginx: The ingress nginx class
-h or --help: Shows this message
-j or --jx=jx: Uses the provided jx executable

Example:
./jxx --nginx-class=nginx-internal -- install --ingress-service=...

