# Using a Standard Python Base Image to Run a Hello Python Code.

```bash
vds4025x11:~/cve-bliss/pycode# **grype buntyray2024/hello.py:latest --scope all-layers**
 ✔ Vulnerability DB                [no update available]
 ✔ Loaded image                                                                                                                                                                                                buntyray2024/hello.py:latest
 ✔ Parsed image                                                                                                                                                     sha256:fc8dc1797d545e4b8e221ae58b28714938e04ed668a37579583f3ca5c1331d27
 ✔ Cataloged contents                                                                                                                                                      647a3b88b29f60cfa5d6ed676472a88a9b772cdd00c0cf6b0f264a5bec488017
   ├── ✔ Packages                        [440 packages]
   ├── ✔ File digests                    [19,220 files]
   ├── ✔ File metadata                   [19,220 locations]
   └── ✔ Executables                     [1,434 executables]
 ✔ Scanned for vulnerabilities     [662 vulnerability matches]
   ├── by severity: 11 critical, 62 high, 133 medium, 42 low, 459 negligible (327 unknown)
   └── by status:   119 fixed, 915 not-fixed, 372 ignored
NAME                          INSTALLED                     FIXED-IN          TYPE  VULNERABILITY     SEVERITY
apt                           2.6.1                                           deb   CVE-2011-3374     Negligible
binutils                      2.40-2                                          deb   CVE-2023-1972     Negligible
binutils                      2.40-2                                          deb   CVE-2021-32256    Negligible
binutils                      2.40-2                                          deb   CVE-2018-9996     Negligible
binutils                      2.40-2                                          deb   CVE-2018-20712    Negligible
binutils                      2.40-2                                          deb   CVE-2018-20673    Negligible
binutils                      2.40-2                                          deb   CVE-2018-18483    Negligible
binutils                      2.40-2                                          deb   CVE-2017-13716    Negligible
binutils-common               2.40-2                                          deb   CVE-2023-1972     Negligible
binutils-common               2.40-2                                          deb   CVE-2021-32256    Negligible
binutils-common               2.40-2                                          deb   CVE-2018-9996     Negligible
binutils-common               2.40-2                                          deb   CVE-2018-20712    Negligible
binutils-common               2.40-2                                          deb   CVE-2018-20673    Negligible
binutils-common               2.40-2                                          deb   CVE-2018-18483    Negligible
binutils-common               2.40-2                                          deb   CVE-2017-13716    Negligible
binutils-x86-64-linux-gnu     2.40-2                                          deb   CVE-2023-1972     Negligible
binutils-x86-64-linux-gnu     2.40-2                                          deb   CVE-2021-32256    Negligible
binutils-x86-64-linux-gnu     2.40-2                                          deb   CVE-2018-9996     Negligible
binutils-x86-64-linux-gnu     2.40-2                                          deb   CVE-2018-20712    Negligible
binutils-x86-64-linux-gnu     2.40-2                                          deb   CVE-2018-20673    Negligible
binutils-x86-64-linux-gnu     2.40-2                                          deb   CVE-2018-18483    Negligible
binutils-x86-64-linux-gnu     2.40-2                                          deb   CVE-2017-13716    Negligible
bsdutils                      1:2.38.1-5+deb12u1                              deb   CVE-2022-0563     Negligible
coreutils                     9.1-1                         (won't fix)       deb   CVE-2016-2781     Low
coreutils                     9.1-1                                           deb   CVE-2017-18018    Negligible
cpp-12                        12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
cpp-12                        12.2.0-14                                       deb   CVE-2022-27943    Negligible
curl                          7.88.1-10+deb12u6                               deb   CVE-2024-2379     Negligible
dirmngr                       2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
g++-12                        12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
g++-12                        12.2.0-14                                       deb   CVE-2022-27943    Negligible
gcc-12                        12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
gcc-12                        12.2.0-14                                       deb   CVE-2022-27943    Negligible
gcc-12-base                   12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
gcc-12-base                   12.2.0-14                                       deb   CVE-2022-27943    Negligible
git                           1:2.39.2-1.1                                    deb   CVE-2024-32002    Critical
git                           1:2.39.2-1.1                                    deb   CVE-2024-32465    High
git                           1:2.39.2-1.1                                    deb   CVE-2024-32004    High
git                           1:2.39.2-1.1                  (won't fix)       deb   CVE-2023-29007    High
git                           1:2.39.2-1.1                  (won't fix)       deb   CVE-2023-25652    High
git                           1:2.39.2-1.1                                    deb   CVE-2024-32021    Low
git                           1:2.39.2-1.1                                    deb   CVE-2024-32020    Low
git                           1:2.39.2-1.1                  (won't fix)       deb   CVE-2023-25815    Low
git                           1:2.39.2-1.1                                    deb   CVE-2022-24975    Negligible
git                           1:2.39.2-1.1                                    deb   CVE-2018-1000021  Negligible
git-man                       1:2.39.2-1.1                                    deb   CVE-2024-32002    Critical
git-man                       1:2.39.2-1.1                                    deb   CVE-2024-32465    High
git-man                       1:2.39.2-1.1                                    deb   CVE-2024-32004    High
git-man                       1:2.39.2-1.1                  (won't fix)       deb   CVE-2023-29007    High
git-man                       1:2.39.2-1.1                  (won't fix)       deb   CVE-2023-25652    High
git-man                       1:2.39.2-1.1                                    deb   CVE-2024-32021    Low
git-man                       1:2.39.2-1.1                                    deb   CVE-2024-32020    Low
git-man                       1:2.39.2-1.1                  (won't fix)       deb   CVE-2023-25815    Low
git-man                       1:2.39.2-1.1                                    deb   CVE-2022-24975    Negligible
git-man                       1:2.39.2-1.1                                    deb   CVE-2018-1000021  Negligible
gnupg                         2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
gnupg-l10n                    2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
gnupg-utils                   2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
gpg                           2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
gpg-agent                     2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
gpg-wks-client                2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
gpg-wks-server                2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
gpgconf                       2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
gpgsm                         2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
gpgv                          2.2.40-1.1                                      deb   CVE-2022-3219     Negligible
imagemagick                   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
imagemagick                   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
imagemagick                   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
imagemagick                   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
imagemagick                   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
imagemagick                   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
imagemagick                   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
imagemagick                   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
imagemagick                   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
imagemagick-6-common          8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
imagemagick-6-common          8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
imagemagick-6-common          8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
imagemagick-6-common          8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
imagemagick-6-common          8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
imagemagick-6-common          8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
imagemagick-6-common          8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
imagemagick-6-common          8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
imagemagick-6-common          8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
imagemagick-6.q16             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
imagemagick-6.q16             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
imagemagick-6.q16             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
imagemagick-6.q16             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
imagemagick-6.q16             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
imagemagick-6.q16             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
imagemagick-6.q16             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
imagemagick-6.q16             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
imagemagick-6.q16             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
krb5-multidev                 1.20.1-2+deb12u1                                deb   CVE-2018-5709     Negligible
krb5-multidev                 1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37371    Unknown
krb5-multidev                 1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37370    Unknown
krb5-multidev                 1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26462    Unknown
krb5-multidev                 1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26461    Unknown
krb5-multidev                 1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26458    Unknown
libaom3                       3.6.0-1                       (won't fix)       deb   CVE-2023-6879     Critical
libaom3                       3.6.0-1                       (won't fix)       deb   CVE-2023-39616    High
libaom3                       3.6.0-1                                         deb   CVE-2024-5171     Unknown
libapt-pkg6.0                 2.6.1                                           deb   CVE-2011-3374     Negligible
libasan8                      12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libasan8                      12.2.0-14                                       deb   CVE-2022-27943    Negligible
libatomic1                    12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libatomic1                    12.2.0-14                                       deb   CVE-2022-27943    Negligible
libbinutils                   2.40-2                                          deb   CVE-2023-1972     Negligible
libbinutils                   2.40-2                                          deb   CVE-2021-32256    Negligible
libbinutils                   2.40-2                                          deb   CVE-2018-9996     Negligible
libbinutils                   2.40-2                                          deb   CVE-2018-20712    Negligible
libbinutils                   2.40-2                                          deb   CVE-2018-20673    Negligible
libbinutils                   2.40-2                                          deb   CVE-2018-18483    Negligible
libbinutils                   2.40-2                                          deb   CVE-2017-13716    Negligible
libblkid-dev                  2.38.1-5+deb12u1                                deb   CVE-2022-0563     Negligible
libblkid1                     2.38.1-5+deb12u1                                deb   CVE-2022-0563     Negligible
libbluetooth-dev              5.66-1+deb12u2                (won't fix)       deb   CVE-2023-51596    High
libbluetooth-dev              5.66-1+deb12u2                (won't fix)       deb   CVE-2023-44431    High
libbluetooth-dev              5.66-1+deb12u2                (won't fix)       deb   CVE-2023-51592    Medium
libbluetooth-dev              5.66-1+deb12u2                (won't fix)       deb   CVE-2023-51589    Medium
libbluetooth-dev              5.66-1+deb12u2                (won't fix)       deb   CVE-2023-51580    Medium
libbluetooth-dev              5.66-1+deb12u2                (won't fix)       deb   CVE-2023-51594    Low
libbluetooth-dev              5.66-1+deb12u2                                  deb   CVE-2016-9918     Negligible
libbluetooth-dev              5.66-1+deb12u2                                  deb   CVE-2016-9917     Negligible
libbluetooth-dev              5.66-1+deb12u2                                  deb   CVE-2016-9804     Negligible
libbluetooth-dev              5.66-1+deb12u2                                  deb   CVE-2016-9803     Negligible
libbluetooth-dev              5.66-1+deb12u2                                  deb   CVE-2016-9802     Negligible
libbluetooth-dev              5.66-1+deb12u2                                  deb   CVE-2016-9801     Negligible
libbluetooth-dev              5.66-1+deb12u2                                  deb   CVE-2016-9800     Negligible
libbluetooth-dev              5.66-1+deb12u2                                  deb   CVE-2016-9799     Negligible
libbluetooth-dev              5.66-1+deb12u2                                  deb   CVE-2016-9798     Negligible
libbluetooth-dev              5.66-1+deb12u2                                  deb   CVE-2016-9797     Negligible
libbluetooth3                 5.66-1+deb12u2                (won't fix)       deb   CVE-2023-51596    High
libbluetooth3                 5.66-1+deb12u2                (won't fix)       deb   CVE-2023-44431    High
libbluetooth3                 5.66-1+deb12u2                (won't fix)       deb   CVE-2023-51592    Medium
libbluetooth3                 5.66-1+deb12u2                (won't fix)       deb   CVE-2023-51589    Medium
libbluetooth3                 5.66-1+deb12u2                (won't fix)       deb   CVE-2023-51580    Medium
libbluetooth3                 5.66-1+deb12u2                (won't fix)       deb   CVE-2023-51594    Low
libbluetooth3                 5.66-1+deb12u2                                  deb   CVE-2016-9918     Negligible
libbluetooth3                 5.66-1+deb12u2                                  deb   CVE-2016-9917     Negligible
libbluetooth3                 5.66-1+deb12u2                                  deb   CVE-2016-9804     Negligible
libbluetooth3                 5.66-1+deb12u2                                  deb   CVE-2016-9803     Negligible
libbluetooth3                 5.66-1+deb12u2                                  deb   CVE-2016-9802     Negligible
libbluetooth3                 5.66-1+deb12u2                                  deb   CVE-2016-9801     Negligible
libbluetooth3                 5.66-1+deb12u2                                  deb   CVE-2016-9800     Negligible
libbluetooth3                 5.66-1+deb12u2                                  deb   CVE-2016-9799     Negligible
libbluetooth3                 5.66-1+deb12u2                                  deb   CVE-2016-9798     Negligible
libbluetooth3                 5.66-1+deb12u2                                  deb   CVE-2016-9797     Negligible
libc-bin                      2.36-9+deb12u7                                  deb   CVE-2019-9192     Negligible
libc-bin                      2.36-9+deb12u7                                  deb   CVE-2019-1010025  Negligible
libc-bin                      2.36-9+deb12u7                                  deb   CVE-2019-1010024  Negligible
libc-bin                      2.36-9+deb12u7                                  deb   CVE-2019-1010023  Negligible
libc-bin                      2.36-9+deb12u7                                  deb   CVE-2019-1010022  Negligible
libc-bin                      2.36-9+deb12u7                                  deb   CVE-2018-20796    Negligible
libc-bin                      2.36-9+deb12u7                                  deb   CVE-2010-4756     Negligible
libc-dev-bin                  2.36-9+deb12u7                                  deb   CVE-2019-9192     Negligible
libc-dev-bin                  2.36-9+deb12u7                                  deb   CVE-2019-1010025  Negligible
libc-dev-bin                  2.36-9+deb12u7                                  deb   CVE-2019-1010024  Negligible
libc-dev-bin                  2.36-9+deb12u7                                  deb   CVE-2019-1010023  Negligible
libc-dev-bin                  2.36-9+deb12u7                                  deb   CVE-2019-1010022  Negligible
libc-dev-bin                  2.36-9+deb12u7                                  deb   CVE-2018-20796    Negligible
libc-dev-bin                  2.36-9+deb12u7                                  deb   CVE-2010-4756     Negligible
libc6                         2.36-9+deb12u7                                  deb   CVE-2019-9192     Negligible
libc6                         2.36-9+deb12u7                                  deb   CVE-2019-1010025  Negligible
libc6                         2.36-9+deb12u7                                  deb   CVE-2019-1010024  Negligible
libc6                         2.36-9+deb12u7                                  deb   CVE-2019-1010023  Negligible
libc6                         2.36-9+deb12u7                                  deb   CVE-2019-1010022  Negligible
libc6                         2.36-9+deb12u7                                  deb   CVE-2018-20796    Negligible
libc6                         2.36-9+deb12u7                                  deb   CVE-2010-4756     Negligible
libc6-dev                     2.36-9+deb12u7                                  deb   CVE-2019-9192     Negligible
libc6-dev                     2.36-9+deb12u7                                  deb   CVE-2019-1010025  Negligible
libc6-dev                     2.36-9+deb12u7                                  deb   CVE-2019-1010024  Negligible
libc6-dev                     2.36-9+deb12u7                                  deb   CVE-2019-1010023  Negligible
libc6-dev                     2.36-9+deb12u7                                  deb   CVE-2019-1010022  Negligible
libc6-dev                     2.36-9+deb12u7                                  deb   CVE-2018-20796    Negligible
libc6-dev                     2.36-9+deb12u7                                  deb   CVE-2010-4756     Negligible
libcairo-gobject2             1.16.0-7                      (won't fix)       deb   CVE-2019-6462     Low
libcairo-gobject2             1.16.0-7                      (won't fix)       deb   CVE-2019-6461     Low
libcairo-gobject2             1.16.0-7                      (won't fix)       deb   CVE-2018-18064    Low
libcairo-gobject2             1.16.0-7                      (won't fix)       deb   CVE-2017-7475     Low
libcairo-script-interpreter2  1.16.0-7                      (won't fix)       deb   CVE-2019-6462     Low
libcairo-script-interpreter2  1.16.0-7                      (won't fix)       deb   CVE-2019-6461     Low
libcairo-script-interpreter2  1.16.0-7                      (won't fix)       deb   CVE-2018-18064    Low
libcairo-script-interpreter2  1.16.0-7                      (won't fix)       deb   CVE-2017-7475     Low
libcairo2                     1.16.0-7                      (won't fix)       deb   CVE-2019-6462     Low
libcairo2                     1.16.0-7                      (won't fix)       deb   CVE-2019-6461     Low
libcairo2                     1.16.0-7                      (won't fix)       deb   CVE-2018-18064    Low
libcairo2                     1.16.0-7                      (won't fix)       deb   CVE-2017-7475     Low
libcairo2-dev                 1.16.0-7                      (won't fix)       deb   CVE-2019-6462     Low
libcairo2-dev                 1.16.0-7                      (won't fix)       deb   CVE-2019-6461     Low
libcairo2-dev                 1.16.0-7                      (won't fix)       deb   CVE-2018-18064    Low
libcairo2-dev                 1.16.0-7                      (won't fix)       deb   CVE-2017-7475     Low
libcc1-0                      12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libcc1-0                      12.2.0-14                                       deb   CVE-2022-27943    Negligible
libctf-nobfd0                 2.40-2                                          deb   CVE-2023-1972     Negligible
libctf-nobfd0                 2.40-2                                          deb   CVE-2021-32256    Negligible
libctf-nobfd0                 2.40-2                                          deb   CVE-2018-9996     Negligible
libctf-nobfd0                 2.40-2                                          deb   CVE-2018-20712    Negligible
libctf-nobfd0                 2.40-2                                          deb   CVE-2018-20673    Negligible
libctf-nobfd0                 2.40-2                                          deb   CVE-2018-18483    Negligible
libctf-nobfd0                 2.40-2                                          deb   CVE-2017-13716    Negligible
libctf0                       2.40-2                                          deb   CVE-2023-1972     Negligible
libctf0                       2.40-2                                          deb   CVE-2021-32256    Negligible
libctf0                       2.40-2                                          deb   CVE-2018-9996     Negligible
libctf0                       2.40-2                                          deb   CVE-2018-20712    Negligible
libctf0                       2.40-2                                          deb   CVE-2018-20673    Negligible
libctf0                       2.40-2                                          deb   CVE-2018-18483    Negligible
libctf0                       2.40-2                                          deb   CVE-2017-13716    Negligible
libcurl3-gnutls               7.88.1-10+deb12u6                               deb   CVE-2024-2379     Negligible
libcurl4                      7.88.1-10+deb12u6                               deb   CVE-2024-2379     Negligible
libcurl4-openssl-dev          7.88.1-10+deb12u6                               deb   CVE-2024-2379     Negligible
libdav1d6                     1.0.0-2+deb12u1               (won't fix)       deb   CVE-2023-32570    Medium
libde265-0                    1.0.11-1+deb12u2              (won't fix)       deb   CVE-2024-38949    Medium
libde265-0                    1.0.11-1+deb12u2              (won't fix)       deb   CVE-2023-51792    Low
libde265-0                    1.0.11-1+deb12u2              (won't fix)       deb   CVE-2024-38950    Unknown
libdjvulibre-dev              3.5.28-2+b1                   (won't fix)       deb   CVE-2021-46312    Medium
libdjvulibre-dev              3.5.28-2+b1                   (won't fix)       deb   CVE-2021-46310    Medium
libdjvulibre-text             3.5.28-2                      (won't fix)       deb   CVE-2021-46312    Medium
libdjvulibre-text             3.5.28-2                      (won't fix)       deb   CVE-2021-46310    Medium
libdjvulibre21                3.5.28-2+b1                   (won't fix)       deb   CVE-2021-46312    Medium
libdjvulibre21                3.5.28-2+b1                   (won't fix)       deb   CVE-2021-46310    Medium
libelf1                       0.188-2.1                                       deb   CVE-2024-25260    Negligible
libexpat1                     2.5.0-1                       (won't fix)       deb   CVE-2023-52425    High
libexpat1                     2.5.0-1                                         deb   CVE-2024-28757    Negligible
libexpat1                     2.5.0-1                                         deb   CVE-2023-52426    Negligible
libexpat1-dev                 2.5.0-1                       (won't fix)       deb   CVE-2023-52425    High
libexpat1-dev                 2.5.0-1                                         deb   CVE-2024-28757    Negligible
libexpat1-dev                 2.5.0-1                                         deb   CVE-2023-52426    Negligible
libgcc-12-dev                 12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libgcc-12-dev                 12.2.0-14                                       deb   CVE-2022-27943    Negligible
libgcc-s1                     12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libgcc-s1                     12.2.0-14                                       deb   CVE-2022-27943    Negligible
libgcrypt20                   1.10.1-3                      (won't fix)       deb   CVE-2024-2236     Medium
libgcrypt20                   1.10.1-3                                        deb   CVE-2018-6829     Negligible
libglib2.0-0                  2.74.6-2+deb12u3                                deb   CVE-2012-0039     Negligible
libglib2.0-bin                2.74.6-2+deb12u3                                deb   CVE-2012-0039     Negligible
libglib2.0-data               2.74.6-2+deb12u3                                deb   CVE-2012-0039     Negligible
libglib2.0-dev                2.74.6-2+deb12u3                                deb   CVE-2012-0039     Negligible
libglib2.0-dev-bin            2.74.6-2+deb12u3                                deb   CVE-2012-0039     Negligible
libgnutls30                   3.7.9-2+deb12u3                                 deb   CVE-2011-3389     Negligible
libgomp1                      12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libgomp1                      12.2.0-14                                       deb   CVE-2022-27943    Negligible
libgprofng0                   2.40-2                                          deb   CVE-2023-1972     Negligible
libgprofng0                   2.40-2                                          deb   CVE-2021-32256    Negligible
libgprofng0                   2.40-2                                          deb   CVE-2018-9996     Negligible
libgprofng0                   2.40-2                                          deb   CVE-2018-20712    Negligible
libgprofng0                   2.40-2                                          deb   CVE-2018-20673    Negligible
libgprofng0                   2.40-2                                          deb   CVE-2018-18483    Negligible
libgprofng0                   2.40-2                                          deb   CVE-2017-13716    Negligible
libgssapi-krb5-2              1.20.1-2+deb12u1                                deb   CVE-2018-5709     Negligible
libgssapi-krb5-2              1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37371    Unknown
libgssapi-krb5-2              1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37370    Unknown
libgssapi-krb5-2              1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26462    Unknown
libgssapi-krb5-2              1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26461    Unknown
libgssapi-krb5-2              1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26458    Unknown
libgssrpc4                    1.20.1-2+deb12u1                                deb   CVE-2018-5709     Negligible
libgssrpc4                    1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37371    Unknown
libgssrpc4                    1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37370    Unknown
libgssrpc4                    1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26462    Unknown
libgssrpc4                    1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26461    Unknown
libgssrpc4                    1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26458    Unknown
libharfbuzz0b                 6.0.0+dfsg-3                  (won't fix)       deb   CVE-2023-25193    High
libheif1                      1.15.1-1                      (won't fix)       deb   CVE-2023-49464    High
libheif1                      1.15.1-1                      (won't fix)       deb   CVE-2023-49463    High
libheif1                      1.15.1-1                      (won't fix)       deb   CVE-2023-49462    High
libheif1                      1.15.1-1                      (won't fix)       deb   CVE-2023-49460    High
libheif1                      1.15.1-1                      (won't fix)       deb   CVE-2023-29659    Medium
libheif1                      1.15.1-1                                        deb   CVE-2024-25269    Negligible
libitm1                       12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libitm1                       12.2.0-14                                       deb   CVE-2022-27943    Negligible
libjansson4                   2.14-2                                          deb   CVE-2020-36325    Negligible
libjbig-dev                   2.1-6.1                                         deb   CVE-2017-9937     Negligible
libjbig0                      2.1-6.1                                         deb   CVE-2017-9937     Negligible
libk5crypto3                  1.20.1-2+deb12u1                                deb   CVE-2018-5709     Negligible
libk5crypto3                  1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37371    Unknown
libk5crypto3                  1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37370    Unknown
libk5crypto3                  1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26462    Unknown
libk5crypto3                  1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26461    Unknown
libk5crypto3                  1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26458    Unknown
libkadm5clnt-mit12            1.20.1-2+deb12u1                                deb   CVE-2018-5709     Negligible
libkadm5clnt-mit12            1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37371    Unknown
libkadm5clnt-mit12            1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37370    Unknown
libkadm5clnt-mit12            1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26462    Unknown
libkadm5clnt-mit12            1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26461    Unknown
libkadm5clnt-mit12            1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26458    Unknown
libkadm5srv-mit12             1.20.1-2+deb12u1                                deb   CVE-2018-5709     Negligible
libkadm5srv-mit12             1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37371    Unknown
libkadm5srv-mit12             1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37370    Unknown
libkadm5srv-mit12             1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26462    Unknown
libkadm5srv-mit12             1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26461    Unknown
libkadm5srv-mit12             1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26458    Unknown
libkdb5-10                    1.20.1-2+deb12u1                                deb   CVE-2018-5709     Negligible
libkdb5-10                    1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37371    Unknown
libkdb5-10                    1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37370    Unknown
libkdb5-10                    1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26462    Unknown
libkdb5-10                    1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26461    Unknown
libkdb5-10                    1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26458    Unknown
libkrb5-3                     1.20.1-2+deb12u1                                deb   CVE-2018-5709     Negligible
libkrb5-3                     1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37371    Unknown
libkrb5-3                     1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37370    Unknown
libkrb5-3                     1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26462    Unknown
libkrb5-3                     1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26461    Unknown
libkrb5-3                     1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26458    Unknown
libkrb5-dev                   1.20.1-2+deb12u1                                deb   CVE-2018-5709     Negligible
libkrb5-dev                   1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37371    Unknown
libkrb5-dev                   1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37370    Unknown
libkrb5-dev                   1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26462    Unknown
libkrb5-dev                   1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26461    Unknown
libkrb5-dev                   1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26458    Unknown
libkrb5support0               1.20.1-2+deb12u1                                deb   CVE-2018-5709     Negligible
libkrb5support0               1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37371    Unknown
libkrb5support0               1.20.1-2+deb12u1              1.20.1-2+deb12u2  deb   CVE-2024-37370    Unknown
libkrb5support0               1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26462    Unknown
libkrb5support0               1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26461    Unknown
libkrb5support0               1.20.1-2+deb12u1              (won't fix)       deb   CVE-2024-26458    Unknown
libldap-2.5-0                 2.5.13+dfsg-5                 (won't fix)       deb   CVE-2023-2953     High
libldap-2.5-0                 2.5.13+dfsg-5                                   deb   CVE-2020-15719    Negligible
libldap-2.5-0                 2.5.13+dfsg-5                                   deb   CVE-2017-17740    Negligible
libldap-2.5-0                 2.5.13+dfsg-5                                   deb   CVE-2017-14159    Negligible
libldap-2.5-0                 2.5.13+dfsg-5                                   deb   CVE-2015-3276     Negligible
liblsan0                      12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
liblsan0                      12.2.0-14                                       deb   CVE-2022-27943    Negligible
libmagickcore-6-arch-config   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
libmagickcore-6-arch-config   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
libmagickcore-6-arch-config   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
libmagickcore-6-arch-config   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
libmagickcore-6-arch-config   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
libmagickcore-6-arch-config   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
libmagickcore-6-arch-config   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
libmagickcore-6-arch-config   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
libmagickcore-6-arch-config   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
libmagickcore-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
libmagickcore-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
libmagickcore-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
libmagickcore-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
libmagickcore-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
libmagickcore-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
libmagickcore-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
libmagickcore-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
libmagickcore-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
libmagickcore-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
libmagickcore-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
libmagickcore-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
libmagickcore-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
libmagickcore-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
libmagickcore-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
libmagickcore-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
libmagickcore-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
libmagickcore-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
libmagickcore-6.q16-6-extra   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
libmagickcore-6.q16-6-extra   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
libmagickcore-6.q16-6-extra   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
libmagickcore-6.q16-6-extra   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
libmagickcore-6.q16-6-extra   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
libmagickcore-6.q16-6-extra   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
libmagickcore-6.q16-6-extra   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
libmagickcore-6.q16-6-extra   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
libmagickcore-6.q16-6-extra   8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
libmagickcore-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
libmagickcore-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
libmagickcore-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
libmagickcore-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
libmagickcore-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
libmagickcore-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
libmagickcore-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
libmagickcore-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
libmagickcore-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
libmagickcore-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
libmagickcore-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
libmagickcore-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
libmagickcore-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
libmagickcore-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
libmagickcore-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
libmagickcore-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
libmagickcore-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
libmagickcore-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
libmagickwand-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
libmagickwand-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
libmagickwand-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
libmagickwand-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
libmagickwand-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
libmagickwand-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
libmagickwand-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
libmagickwand-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
libmagickwand-6-headers       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
libmagickwand-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
libmagickwand-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
libmagickwand-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
libmagickwand-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
libmagickwand-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
libmagickwand-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
libmagickwand-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
libmagickwand-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
libmagickwand-6.q16-6         8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
libmagickwand-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
libmagickwand-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
libmagickwand-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
libmagickwand-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
libmagickwand-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
libmagickwand-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
libmagickwand-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
libmagickwand-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
libmagickwand-6.q16-dev       8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
libmagickwand-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2023-34152    Negligible
libmagickwand-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2021-20311    Negligible
libmagickwand-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2018-15607    Negligible
libmagickwand-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-7275     Negligible
libmagickwand-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11755    Negligible
libmagickwand-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2017-11754    Negligible
libmagickwand-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2016-8678     Negligible
libmagickwand-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2008-3134     Negligible
libmagickwand-dev             8:6.9.11.60+dfsg-1.6+deb12u1                    deb   CVE-2005-0406     Negligible
libmariadb-dev                1:10.11.6-0+deb12u1           (won't fix)       deb   CVE-2024-21096    Medium
libmariadb-dev-compat         1:10.11.6-0+deb12u1           (won't fix)       deb   CVE-2024-21096    Medium
libmariadb3                   1:10.11.6-0+deb12u1           (won't fix)       deb   CVE-2024-21096    Medium
libmount-dev                  2.38.1-5+deb12u1                                deb   CVE-2022-0563     Negligible
libmount1                     2.38.1-5+deb12u1                                deb   CVE-2022-0563     Negligible
libncurses-dev                6.4-4                         (won't fix)       deb   CVE-2023-50495    Medium
libncurses-dev                6.4-4                         (won't fix)       deb   CVE-2023-45918    Unknown
libncurses5-dev               6.4-4                         (won't fix)       deb   CVE-2023-50495    Medium
libncurses5-dev               6.4-4                         (won't fix)       deb   CVE-2023-45918    Unknown
libncurses6                   6.4-4                         (won't fix)       deb   CVE-2023-50495    Medium
libncurses6                   6.4-4                         (won't fix)       deb   CVE-2023-45918    Unknown
libncursesw5-dev              6.4-4                         (won't fix)       deb   CVE-2023-50495    Medium
libncursesw5-dev              6.4-4                         (won't fix)       deb   CVE-2023-45918    Unknown
libncursesw6                  6.4-4                         (won't fix)       deb   CVE-2023-50495    Medium
libncursesw6                  6.4-4                         (won't fix)       deb   CVE-2023-45918    Unknown
libnghttp2-14                 1.52.0-1+deb12u1                                deb   CVE-2024-28182    Medium
libopenexr-3-1-30             3.1.5-5                       (won't fix)       deb   CVE-2023-5841     Critical
libopenexr-3-1-30             3.1.5-5                                         deb   CVE-2017-14988    Negligible
libopenexr-3-1-30             3.1.5-5                       (won't fix)       deb   CVE-2024-31047    Unknown
libopenexr-dev                3.1.5-5                       (won't fix)       deb   CVE-2023-5841     Critical
libopenexr-dev                3.1.5-5                                         deb   CVE-2017-14988    Negligible
libopenexr-dev                3.1.5-5                       (won't fix)       deb   CVE-2024-31047    Unknown
libopenjp2-7                  2.5.0-2                       (won't fix)       deb   CVE-2021-3575     High
libopenjp2-7                  2.5.0-2                                         deb   CVE-2023-39329    Medium
libopenjp2-7                  2.5.0-2                                         deb   CVE-2023-39328    Medium
libopenjp2-7                  2.5.0-2                                         deb   CVE-2023-39327    Medium
libopenjp2-7                  2.5.0-2                       (won't fix)       deb   CVE-2019-6988     Low
libopenjp2-7                  2.5.0-2                                         deb   CVE-2018-20846    Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2018-16376    Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2018-16375    Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2017-17479    Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2016-9581     Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2016-9580     Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2016-9117     Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2016-9116     Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2016-9115     Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2016-9114     Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2016-9113     Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2016-10506    Negligible
libopenjp2-7                  2.5.0-2                                         deb   CVE-2016-10505    Negligible
libopenjp2-7-dev              2.5.0-2                       (won't fix)       deb   CVE-2021-3575     High
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2023-39329    Medium
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2023-39328    Medium
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2023-39327    Medium
libopenjp2-7-dev              2.5.0-2                       (won't fix)       deb   CVE-2019-6988     Low
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2018-20846    Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2018-16376    Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2018-16375    Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2017-17479    Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2016-9581     Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2016-9580     Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2016-9117     Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2016-9116     Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2016-9115     Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2016-9114     Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2016-9113     Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2016-10506    Negligible
libopenjp2-7-dev              2.5.0-2                                         deb   CVE-2016-10505    Negligible
libpam-modules                1.5.2-6+deb12u1               (won't fix)       deb   CVE-2024-22365    Medium
libpam-modules-bin            1.5.2-6+deb12u1               (won't fix)       deb   CVE-2024-22365    Medium
libpam-runtime                1.5.2-6+deb12u1               (won't fix)       deb   CVE-2024-22365    Medium
libpam0g                      1.5.2-6+deb12u1               (won't fix)       deb   CVE-2024-22365    Medium
libperl5.36                   5.36.0-7+deb12u1              (won't fix)       deb   CVE-2023-31484    High
libperl5.36                   5.36.0-7+deb12u1                                deb   CVE-2023-31486    Negligible
libperl5.36                   5.36.0-7+deb12u1                                deb   CVE-2011-4116     Negligible
libpixman-1-0                 0.42.2-1                                        deb   CVE-2023-37769    Negligible
libpixman-1-dev               0.42.2-1                                        deb   CVE-2023-37769    Negligible
libpng-dev                    1.6.39-2                                        deb   CVE-2021-4214     Negligible
libpng16-16                   1.6.39-2                                        deb   CVE-2021-4214     Negligible
libpq-dev                     15.7-0+deb12u1                (won't fix)       deb   CVE-2024-4317     Low
libpq5                        15.7-0+deb12u1                (won't fix)       deb   CVE-2024-4317     Low
libproc2-0                    2:4.0.2-3                     (won't fix)       deb   CVE-2023-4016     Low
libpython3.11-minimal         3.11.2-6+deb12u2              (won't fix)       deb   CVE-2024-0397     High
libpython3.11-minimal         3.11.2-6+deb12u2              (won't fix)       deb   CVE-2023-27043    Medium
libpython3.11-minimal         3.11.2-6+deb12u2              (won't fix)       deb   CVE-2024-4032     Unknown
libpython3.11-stdlib          3.11.2-6+deb12u2              (won't fix)       deb   CVE-2024-0397     High
libpython3.11-stdlib          3.11.2-6+deb12u2              (won't fix)       deb   CVE-2023-27043    Medium
libpython3.11-stdlib          3.11.2-6+deb12u2              (won't fix)       deb   CVE-2024-4032     Unknown
libquadmath0                  12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libquadmath0                  12.2.0-14                                       deb   CVE-2022-27943    Negligible
libsmartcols1                 2.38.1-5+deb12u1                                deb   CVE-2022-0563     Negligible
libsqlite3-0                  3.40.1-2                      (won't fix)       deb   CVE-2023-7104     High
libsqlite3-0                  3.40.1-2                      (won't fix)       deb   CVE-2024-0232     Medium
libsqlite3-0                  3.40.1-2                                        deb   CVE-2021-45346    Negligible
libsqlite3-dev                3.40.1-2                      (won't fix)       deb   CVE-2023-7104     High
libsqlite3-dev                3.40.1-2                      (won't fix)       deb   CVE-2024-0232     Medium
libsqlite3-dev                3.40.1-2                                        deb   CVE-2021-45346    Negligible
libssl-dev                    3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-5535     Critical
libssl-dev                    3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-4741     Unknown
libssl-dev                    3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-4603     Unknown
libssl-dev                    3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-2511     Unknown
libssl3                       3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-5535     Critical
libssl3                       3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-4741     Unknown
libssl3                       3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-4603     Unknown
libssl3                       3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-2511     Unknown
libstdc++-12-dev              12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libstdc++-12-dev              12.2.0-14                                       deb   CVE-2022-27943    Negligible
libstdc++6                    12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libstdc++6                    12.2.0-14                                       deb   CVE-2022-27943    Negligible
libsystemd0                   252.26-1~deb12u2                                deb   CVE-2023-31439    Negligible
libsystemd0                   252.26-1~deb12u2                                deb   CVE-2023-31438    Negligible
libsystemd0                   252.26-1~deb12u2                                deb   CVE-2023-31437    Negligible
libsystemd0                   252.26-1~deb12u2                                deb   CVE-2013-4392     Negligible
libtcl8.6                     8.6.13+dfsg-2                                   deb   CVE-2021-35331    Negligible
libtiff-dev                   4.5.0-6+deb12u1                                 deb   CVE-2024-6716     High
libtiff-dev                   4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-52356    High
libtiff-dev                   4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-52355    High
libtiff-dev                   4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-6277     Medium
libtiff-dev                   4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-3618     Medium
libtiff-dev                   4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-2908     Medium
libtiff-dev                   4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-26966    Medium
libtiff-dev                   4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-26965    Medium
libtiff-dev                   4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-25433    Medium
libtiff-dev                   4.5.0-6+deb12u1                                 deb   CVE-2023-6228     Negligible
libtiff-dev                   4.5.0-6+deb12u1                                 deb   CVE-2023-3164     Negligible
libtiff-dev                   4.5.0-6+deb12u1                                 deb   CVE-2023-1916     Negligible
libtiff-dev                   4.5.0-6+deb12u1                                 deb   CVE-2022-1210     Negligible
libtiff-dev                   4.5.0-6+deb12u1                                 deb   CVE-2018-10126    Negligible
libtiff-dev                   4.5.0-6+deb12u1                                 deb   CVE-2017-9117     Negligible
libtiff-dev                   4.5.0-6+deb12u1                                 deb   CVE-2017-5563     Negligible
libtiff-dev                   4.5.0-6+deb12u1                                 deb   CVE-2017-17973    Negligible
libtiff-dev                   4.5.0-6+deb12u1                                 deb   CVE-2017-16232    Negligible
libtiff6                      4.5.0-6+deb12u1                                 deb   CVE-2024-6716     High
libtiff6                      4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-52356    High
libtiff6                      4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-52355    High
libtiff6                      4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-6277     Medium
libtiff6                      4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-3618     Medium
libtiff6                      4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-2908     Medium
libtiff6                      4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-26966    Medium
libtiff6                      4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-26965    Medium
libtiff6                      4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-25433    Medium
libtiff6                      4.5.0-6+deb12u1                                 deb   CVE-2023-6228     Negligible
libtiff6                      4.5.0-6+deb12u1                                 deb   CVE-2023-3164     Negligible
libtiff6                      4.5.0-6+deb12u1                                 deb   CVE-2023-1916     Negligible
libtiff6                      4.5.0-6+deb12u1                                 deb   CVE-2022-1210     Negligible
libtiff6                      4.5.0-6+deb12u1                                 deb   CVE-2018-10126    Negligible
libtiff6                      4.5.0-6+deb12u1                                 deb   CVE-2017-9117     Negligible
libtiff6                      4.5.0-6+deb12u1                                 deb   CVE-2017-5563     Negligible
libtiff6                      4.5.0-6+deb12u1                                 deb   CVE-2017-17973    Negligible
libtiff6                      4.5.0-6+deb12u1                                 deb   CVE-2017-16232    Negligible
libtiffxx6                    4.5.0-6+deb12u1                                 deb   CVE-2024-6716     High
libtiffxx6                    4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-52356    High
libtiffxx6                    4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-52355    High
libtiffxx6                    4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-6277     Medium
libtiffxx6                    4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-3618     Medium
libtiffxx6                    4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-2908     Medium
libtiffxx6                    4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-26966    Medium
libtiffxx6                    4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-26965    Medium
libtiffxx6                    4.5.0-6+deb12u1               (won't fix)       deb   CVE-2023-25433    Medium
libtiffxx6                    4.5.0-6+deb12u1                                 deb   CVE-2023-6228     Negligible
libtiffxx6                    4.5.0-6+deb12u1                                 deb   CVE-2023-3164     Negligible
libtiffxx6                    4.5.0-6+deb12u1                                 deb   CVE-2023-1916     Negligible
libtiffxx6                    4.5.0-6+deb12u1                                 deb   CVE-2022-1210     Negligible
libtiffxx6                    4.5.0-6+deb12u1                                 deb   CVE-2018-10126    Negligible
libtiffxx6                    4.5.0-6+deb12u1                                 deb   CVE-2017-9117     Negligible
libtiffxx6                    4.5.0-6+deb12u1                                 deb   CVE-2017-5563     Negligible
libtiffxx6                    4.5.0-6+deb12u1                                 deb   CVE-2017-17973    Negligible
libtiffxx6                    4.5.0-6+deb12u1                                 deb   CVE-2017-16232    Negligible
libtinfo6                     6.4-4                         (won't fix)       deb   CVE-2023-50495    Medium
libtinfo6                     6.4-4                         (won't fix)       deb   CVE-2023-45918    Unknown
libtsan2                      12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libtsan2                      12.2.0-14                                       deb   CVE-2022-27943    Negligible
libubsan1                     12.2.0-14                     (won't fix)       deb   CVE-2023-4039     Medium
libubsan1                     12.2.0-14                                       deb   CVE-2022-27943    Negligible
libudev1                      252.26-1~deb12u2                                deb   CVE-2023-31439    Negligible
libudev1                      252.26-1~deb12u2                                deb   CVE-2023-31438    Negligible
libudev1                      252.26-1~deb12u2                                deb   CVE-2023-31437    Negligible
libudev1                      252.26-1~deb12u2                                deb   CVE-2013-4392     Negligible
libuuid1                      2.38.1-5+deb12u1                                deb   CVE-2022-0563     Negligible
libwmf-0.2-7                  0.2.12-5.1                                      deb   CVE-2009-3546     Medium
libwmf-0.2-7                  0.2.12-5.1                                      deb   CVE-2007-3996     Medium
libwmf-0.2-7                  0.2.12-5.1                                      deb   CVE-2007-3477     Low
libwmf-0.2-7                  0.2.12-5.1                                      deb   CVE-2007-3476     Low
libwmf-dev                    0.2.12-5.1                                      deb   CVE-2009-3546     Medium
libwmf-dev                    0.2.12-5.1                                      deb   CVE-2007-3996     Medium
libwmf-dev                    0.2.12-5.1                                      deb   CVE-2007-3477     Low
libwmf-dev                    0.2.12-5.1                                      deb   CVE-2007-3476     Low
libwmflite-0.2-7              0.2.12-5.1                                      deb   CVE-2009-3546     Medium
libwmflite-0.2-7              0.2.12-5.1                                      deb   CVE-2007-3996     Medium
libwmflite-0.2-7              0.2.12-5.1                                      deb   CVE-2007-3477     Low
libwmflite-0.2-7              0.2.12-5.1                                      deb   CVE-2007-3476     Low
libxml2                       2.9.14+dfsg-1.3~deb12u1       (won't fix)       deb   CVE-2024-25062    High
libxml2                       2.9.14+dfsg-1.3~deb12u1       (won't fix)       deb   CVE-2023-45322    Medium
libxml2                       2.9.14+dfsg-1.3~deb12u1       (won't fix)       deb   CVE-2023-39615    Medium
libxml2                       2.9.14+dfsg-1.3~deb12u1                         deb   CVE-2024-34459    Negligible
libxml2-dev                   2.9.14+dfsg-1.3~deb12u1       (won't fix)       deb   CVE-2024-25062    High
libxml2-dev                   2.9.14+dfsg-1.3~deb12u1       (won't fix)       deb   CVE-2023-45322    Medium
libxml2-dev                   2.9.14+dfsg-1.3~deb12u1       (won't fix)       deb   CVE-2023-39615    Medium
libxml2-dev                   2.9.14+dfsg-1.3~deb12u1                         deb   CVE-2024-34459    Negligible
libxslt1-dev                  1.1.35-1                                        deb   CVE-2015-9019     Negligible
libxslt1.1                    1.1.35-1                                        deb   CVE-2015-9019     Negligible
login                         1:4.13+dfsg1-1+b1             (won't fix)       deb   CVE-2023-4641     Medium
login                         1:4.13+dfsg1-1+b1             (won't fix)       deb   CVE-2023-29383    Low
login                         1:4.13+dfsg1-1+b1                               deb   CVE-2019-19882    Negligible
login                         1:4.13+dfsg1-1+b1                               deb   CVE-2007-5686     Negligible
m4                            1.4.19-3                                        deb   CVE-2008-1688     Negligible
m4                            1.4.19-3                                        deb   CVE-2008-1687     Negligible
mariadb-common                1:10.11.6-0+deb12u1           (won't fix)       deb   CVE-2024-21096    Medium
mount                         2.38.1-5+deb12u1                                deb   CVE-2022-0563     Negligible
ncurses-base                  6.4-4                         (won't fix)       deb   CVE-2023-50495    Medium
ncurses-base                  6.4-4                         (won't fix)       deb   CVE-2023-45918    Unknown
ncurses-bin                   6.4-4                         (won't fix)       deb   CVE-2023-50495    Medium
ncurses-bin                   6.4-4                         (won't fix)       deb   CVE-2023-45918    Unknown
openssh-client                1:9.2p1-2+deb12u3                               deb   CVE-2023-51767    Negligible
openssh-client                1:9.2p1-2+deb12u3                               deb   CVE-2020-15778    Negligible
openssh-client                1:9.2p1-2+deb12u3                               deb   CVE-2020-14145    Negligible
openssh-client                1:9.2p1-2+deb12u3                               deb   CVE-2019-6110     Negligible
openssh-client                1:9.2p1-2+deb12u3                               deb   CVE-2018-15919    Negligible
openssh-client                1:9.2p1-2+deb12u3                               deb   CVE-2016-20012    Negligible
openssh-client                1:9.2p1-2+deb12u3                               deb   CVE-2008-3234     Negligible
openssh-client                1:9.2p1-2+deb12u3                               deb   CVE-2007-2768     Negligible
openssh-client                1:9.2p1-2+deb12u3                               deb   CVE-2007-2243     Negligible
openssl                       3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-5535     Critical
openssl                       3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-4741     Unknown
openssl                       3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-4603     Unknown
openssl                       3.0.13-1~deb12u1              (won't fix)       deb   CVE-2024-2511     Unknown
passwd                        1:4.13+dfsg1-1+b1             (won't fix)       deb   CVE-2023-4641     Medium
passwd                        1:4.13+dfsg1-1+b1             (won't fix)       deb   CVE-2023-29383    Low
passwd                        1:4.13+dfsg1-1+b1                               deb   CVE-2019-19882    Negligible
passwd                        1:4.13+dfsg1-1+b1                               deb   CVE-2007-5686     Negligible
patch                         2.7.6-7                                         deb   CVE-2021-45261    Negligible
patch                         2.7.6-7                                         deb   CVE-2018-6952     Negligible
patch                         2.7.6-7                                         deb   CVE-2018-6951     Negligible
patch                         2.7.6-7                                         deb   CVE-2010-4651     Negligible
perl                          5.36.0-7+deb12u1              (won't fix)       deb   CVE-2023-31484    High
perl                          5.36.0-7+deb12u1                                deb   CVE-2023-31486    Negligible
perl                          5.36.0-7+deb12u1                                deb   CVE-2011-4116     Negligible
perl-base                     5.36.0-7+deb12u1              (won't fix)       deb   CVE-2023-31484    High
perl-base                     5.36.0-7+deb12u1                                deb   CVE-2023-31486    Negligible
perl-base                     5.36.0-7+deb12u1                                deb   CVE-2011-4116     Negligible
perl-modules-5.36             5.36.0-7+deb12u1              (won't fix)       deb   CVE-2023-31484    High
perl-modules-5.36             5.36.0-7+deb12u1                                deb   CVE-2023-31486    Negligible
perl-modules-5.36             5.36.0-7+deb12u1                                deb   CVE-2011-4116     Negligible
procps                        2:4.0.2-3                     (won't fix)       deb   CVE-2023-4016     Low
python3.11                    3.11.2-6+deb12u2              (won't fix)       deb   CVE-2024-0397     High
python3.11                    3.11.2-6+deb12u2              (won't fix)       deb   CVE-2023-27043    Medium
python3.11                    3.11.2-6+deb12u2              (won't fix)       deb   CVE-2024-4032     Unknown
python3.11-minimal            3.11.2-6+deb12u2              (won't fix)       deb   CVE-2024-0397     High
python3.11-minimal            3.11.2-6+deb12u2              (won't fix)       deb   CVE-2023-27043    Medium
python3.11-minimal            3.11.2-6+deb12u2              (won't fix)       deb   CVE-2024-4032     Unknown
tar                           1.34+dfsg-1.2+deb12u1                           deb   CVE-2005-2541     Negligible
tcl8.6                        8.6.13+dfsg-2                                   deb   CVE-2021-35331    Negligible
tcl8.6-dev                    8.6.13+dfsg-2                                   deb   CVE-2021-35331    Negligible
unzip                         6.0-28                                          deb   CVE-2021-4217     Negligible
util-linux                    2.38.1-5+deb12u1                                deb   CVE-2022-0563     Negligible
util-linux-extra              2.38.1-5+deb12u1                                deb   CVE-2022-0563     Negligible
uuid-dev                      2.38.1-5+deb12u1                                deb   CVE-2022-0563     Negligible
wget                          1.21.3-1+b2                   (won't fix)       deb   CVE-2021-31879    Medium
wget                          1.21.3-1+b2                   (won't fix)       deb   CVE-2024-38428    Unknown
zlib1g                        1:1.2.13.dfsg-1               (won't fix)       deb   CVE-2023-45853    Critical
zlib1g-dev                    1:1.2.13.dfsg-1               (won't fix)       deb   CVE-2023-45853    Critical
```
# Using a Chainguard's Python Base Image to Run a Hello Python Code.

```bash
vds4025x11:~/cve-bliss/pycode# grype buntyray2024/hello.py:latest --scope all-layers
 ✔ Vulnerability DB                [no update available]
 ✔ Loaded image                                                                                                                                                                                                buntyray2024/hello.py:latest
 ✔ Parsed image                                                                                                                                                     sha256:f7a6a93195d78e2db48101f1f186cc15bfa5f9859791a9fa0d2c154b07508f00
 ✔ Cataloged contents                                                                                                                                                      908b9c7a31db082993456f0f6c2bfed189b50add05c2425c4bfecd0b36647d66
   ├── ✔ Packages                        [24 packages]
   ├── ✔ File digests                    [1,946 files]
   ├── ✔ File metadata                   [1,946 locations]
   └── ✔ Executables                     [128 executables]
 ✔ Scanned for vulnerabilities     [0 vulnerability matches]
   ├── by severity: 0 critical, 0 high, 0 medium, 0 low, 0 negligible
   └── by status:   0 fixed, 0 not-fixed, 0 ignored
No vulnerabilities found
```
