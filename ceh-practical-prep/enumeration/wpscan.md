# wpscan

1. Scan Wordpress website for vulnerabilities, enumerate users, themes and plugins.
2. Usage:
   1. wpscan --url example.com
   2. wpscan --url example.com -e u \[Enumerate users]
   3. &#x20;wpscan --url example.com --passwords=rockyou.txt --usernames=admin,guest
   4. wpscan --url example.com -e vt --api-token YOUR\_TOKEN \[Enumerate themes]
   5. wpscan --url example.com -e vp --api-token YOUR\_TOKEN \[Enumerate plugins]
