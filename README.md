THIS REPO CONTAINS VULNERABLE CODE. IT IS TO BE USED ONLY FOR DEMONSTRATION PURPOSES.

The image with tag `vulnerable` or `1.0` is compiled with OpenSSL version 1.0.1f, which is vulnerable to the vulnerability known as Heartbleed (CVE-2014-0160). As such, it should not be used for anything remotely production. The intent is to provide demonstrations on how containers change how applications are patched and updated.

The image with tag `non-vulnerable` or `1.1` is compiled with OpenSSL version 1.0.1u, which has no known vulnerabilities (as of 20 Sept 2017).
